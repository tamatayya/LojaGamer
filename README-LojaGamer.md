# 🎮 Loja Gamer

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

---

## 📖 Sobre o projeto

A **Loja Gamer** é uma aplicação front-end de uma loja de jogos, com visual escuro e detalhes em verde neon. A navegação entre as páginas acontece sem recarregar o site, e a vitrine de jogos é montada dinamicamente a partir de uma lista de dados.

O projeto foi criado com o objetivo de praticar React, roteamento com React Router, componentização e estilização com Tailwind CSS.

---

## ✨ Funcionalidades

* 🧭 Navegação entre as páginas Home, Jogos, Contato e Login com React Router.
* 🎮 Seção "Jogos em destaque" na Home, renderizada dinamicamente a partir de uma lista.
* 🃏 Componente `GameCard` reutilizável para exibir título, preço e imagem de cada jogo.
* 📚 Página de catálogo de jogos (estrutura inicial).
* 📧 Página de contato com o e-mail de suporte da loja.
* 🔐 Tela de login com e-mail e senha, mensagem de boas-vindas e redirecionamento para a Home (simulado, sem autenticação real).
* 🚫 Página de erro para rotas inexistentes.
* 📱 Grid responsivo que se ajusta ao tamanho da tela.
* 🎨 Tema gamer com fundo escuro e detalhes em verde neon.

---

## 🛠️ Tecnologias utilizadas

* React 19
* Vite
* React Router DOM 7
* Tailwind CSS 4
* JavaScript (JSX)
* ESLint

---

## 📂 Estrutura do projeto

```text
📁 lojagamer
│
├── index.html
├── package.json
├── vite.config.js
├── eslint.config.js
│
└── src/
    ├── main.jsx
    ├── App.jsx
    ├── index.css
    │
    ├── assets/
    │   └── imagem.jpg
    │
    ├── components/
    │   ├── Header.jsx
    │   ├── Footer.jsx
    │   └── GameCard.jsx
    │
    └── pages/
        ├── Home.jsx
        ├── Jogos.jsx
        ├── Contato.jsx
        ├── Login.jsx
        └── Error.jsx
```

---

## 📚 Conceitos praticados

Durante o desenvolvimento deste projeto foram aplicados conceitos como:

* Componentização e reaproveitamento de componentes
* Passagem de dados com props
* Rotas com `BrowserRouter`, `Routes`, `Route` e `Link`
* Rota coringa para página de erro
* Hooks `useState` e `useNavigate`
* Formulários controlados e `preventDefault`
* Renderização de listas com `map` e `key`
* Estilização utility-first com Tailwind CSS
* CSS Grid com `auto-fit` e `minmax`, e Flexbox
* Efeitos de hover e transições
* Organização de arquivos em `components`, `pages` e `assets`

---

## 🚀 Melhorias futuras

* 🔍 Pesquisa de jogos por nome.
* 🏷️ Filtros por categoria, plataforma e preço.
* 📄 Página de detalhes de cada jogo com rota dinâmica.
* 🛒 Carrinho de compras funcional.
* ❤️ Lista de favoritos.
* 🔗 Carregamento dos jogos a partir de uma API ou arquivo JSON, no lugar de dados fixos.
* 🔐 Autenticação real e validação dos campos de login.
* 📬 Formulário de contato completo.
* 📱 Menu hambúrguer no cabeçalho para dispositivos móveis.

---
