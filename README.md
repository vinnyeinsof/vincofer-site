<div align="center">
  <img src="logo.svg" alt="Vincofer Logo" width="120" />
  <h1>Vincofer | Digital & Creative Agency</h1>
  <p><strong>Plataforma oficial de alta performance focada em conversão, direção de arte e tráfego pago.</strong></p>
  
  [![Website](https://img.shields.io/badge/Website-vincofer.com-6366f1?style=for-the-badge&logo=google-chrome)](https://vincofer.com)
  [![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)
  [![JavaScript](https://img.shields.io/badge/Vanilla_JS-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
</div>

<br>

## 🚀 Sobre o Projeto

Repositório oficial do portal web da **Vincofer**. Este projeto foi desenvolvido para servir como o cartão de visitas premium da agência, unindo design de ponta (UI/UX) com engenharia focada em **CRO (Conversion Rate Optimization)**. 

O objetivo arquitetônico principal foi garantir uma interface rica em micro-interações, mas com tempo de carregamento ultrarrápido (Core Web Vitals), eliminando a fricção na jornada de compra do lead.

## 🧠 Arquitetura e Decisões Técnicas (ADR)

Embora ecossistemas modernos como *Next.js* sejam excelentes para aplicações complexas, optamos por uma abordagem **"Zero-Heavy-Dependency"** para este projeto específico. 

Para uma landing page e portal de portfólio onde **velocidade de carregamento e SEO técnico** são cruciais para o custo de aquisição (CPA), a stack escolhida foi:

*   **HTML5 Semântico:** Estruturação limpa para máxima indexação por motores de busca.
*   **Tailwind CSS:** Estilização utilitária *Atomic CSS*, garantindo um bundle final de estilos extremamente leve e flexibilidade no design de *Glassmorphism*.
*   **Vanilla JavaScript (ES6+):** Toda a reatividade, desde o custom cursor até a complexa lógica matemática da *Calculadora de ROI*, foi construída sem frameworks, garantindo manipulação direta do DOM em milissegundos.
*   **AOS (Animate On Scroll):** Biblioteca leve para micro-interações responsivas atreladas ao scroll da página.
*   **SVGs Nativos:** Renderização vetorial de logos para consistência absoluta em displays Retina/4K.

## ✨ Features em Destaque

- [x] **Calculadora de ROI em Tempo Real:** Lógica em Vanilla JS que simula ROAS, Verba, CPC e Ticket Médio, manipulando os dados diretamente no DOM.
- [x] **Custom Cursor Interativo:** Override do ponteiro padrão do SO através de coordenadas `clientX` e `clientY` atreladas à API de Animação do JavaScript (Web Animations API).
- [x] **Partículas e UI/UX Avançado:** Utilização de `@keyframes` puros para animações de `blob` e backgrounds dinâmicos.
- [x] **Sistema de Portfólio Modular:** Estrutura pronta para expansão de novos cases de sucesso.

## 📂 Estrutura de Diretórios

O projeto segue uma arquitetura "Flat" estática, ideal para deploy em CDNs (Content Delivery Networks):

```text
/
├── index.html                   # Homepage e landing page principal
├── logo.svg                     # Logo vetorizado em alta resolução
├── sobre-nos.html               # O manifesto e DNA da agência
├── gestao-de-trafego.html       # Vertical de Performance
├── direcao-de-arte-e-3d.html    # Vertical Criativa e 3D
├── pos-producao-e-video.html    # Vertical Audiovisual
├── criacao-de-sites.html        # Vertical de CRO e Webdesign
├── case-alta-performance.html   # Estudo de Caso: Setor Automotivo
├── case-institucional-*.html    # Estudo de Caso: Educação
├── noticia-ia.html              # Blog: Artigo sobre IA
├── noticia-cookies.html         # Blog: Artigo sobre Server-Side Tracking
└── noticia-cro.html             # Blog: Artigo sobre Micro-interações
