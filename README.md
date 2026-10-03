# Bruno Costa — Portfólio de Desenvolvedor FullStack

Portfólio pessoal desenvolvido para apresentar minhas habilidades, experiências profissionais e projetos como Desenvolvedor FullStack. A aplicação resolve o problema de centralizar, de forma clara e acessível, todas as informações relevantes para recrutadores e colaboradores, substituindo PDFs estáticos por uma experiência web moderna, responsiva e multilíngue.

---

## 🚀 Funcionalidades

- **Hero Section** — Apresentação pessoal com foto de perfil, título, bio profissional e CTAs diretos para projetos e contato
- **Download de Currículo** — Botão de download direto do currículo em PDF
- **Seção de Habilidades** — Grade visual com as principais tecnologias do stack (Node.js, Angular, PostgreSQL, TypeScript, Docker)
- **Linha do Tempo de Experiência** — Histórico profissional detalhado com responsabilidades e resultados por empresa
- **Vitrine de Projetos** — Cards com descrição e link direto para os repositórios no GitHub
- **Seção de Contato** — Ações rápidas para contato via WhatsApp e conexão no LinkedIn
- **Troca de Tema** — Alternância entre modo escuro e claro com persistência via `localStorage`
- **Suporte Multilíngue** — Interface disponível em Português (PT), Inglês (EN) e Espanhol (ES), com persistência da preferência
- **Navegação com Scroll Suave** — Rolagem animada entre as seções da página
- **Design Responsivo** — Layout adaptado para mobile, tablet e desktop

---

## 🛠️ Tecnologias Utilizadas

### Front-end
- **HTML5** — Estrutura semântica da aplicação
- **CSS3** — Estilizações customizadas (`style.css`)
- **JavaScript (ES6+)** — Lógica de internacionalização (i18n), alternância de tema e interatividade
- **Tailwind CSS** (via CDN) — Utilitários de estilo para composição rápida e responsiva de layouts
- **Devicon** (via CDN) — Ícones de tecnologias para a seção de habilidades

### Deploy
- **Sem dependências de build** — Projeto estático, pronto para hospedar em qualquer serviço de páginas estáticas, como **GitHub Pages**, **Netlify** ou **Vercel**

---

## ⚙️ Pré-requisitos

Por ser um projeto estático (HTML + CSS + JS puro), não há necessidade de instalar gerenciadores de pacotes ou runtimes específicos. Você precisará apenas de:

- [Git](https://git-scm.com/) — Para clonar o repositório
- Um navegador moderno (Chrome, Firefox, Edge) — Para visualizar o projeto
- *(Opcional)* [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) — Extensão do VS Code para servir a aplicação localmente com hot reload

---

## 📦 Instalação e Execução

**1. Clone o repositório:**

```bash
git clone https://github.com/Brunocosta18/portifolio-dev.git
```

**2. Entre na pasta do projeto:**

```bash
cd portifolio-dev
```

**3. Abra o projeto no navegador:**

Você pode abrir o arquivo `index.html` diretamente no navegador:

```bash
# No Windows
start index.html

# No macOS
open index.html

# No Linux
xdg-open index.html
```

> **Dica:** Para uma experiência de desenvolvimento com recarregamento automático, utilize a extensão **Live Server** no VS Code. Clique com o botão direito no `index.html` e selecione **"Open with Live Server"**.

---

## 📂 Estrutura do Projeto

```
portifolio-dev/
│
├── index.html               # Estrutura principal da aplicação (single-page)
├── style.css                # Estilos globais customizados
├── script.js                # Lógica de i18n, tema e interatividade
│
├── perfil.jpg               # Foto de perfil exibida na hero section
├── curriculo-bruno-costa.pdf # Currículo disponível para download
│
└── README.md                # Documentação do projeto
```

---

## 📫 Autor e Contato

Desenvolvido com 💙 por **Bruno Costa**

[![GitHub](https://img.shields.io/badge/GitHub-Brunocosta18-181717?style=flat&logo=github)](https://github.com/Brunocosta18)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Bruno%20Costa-0A66C2?style=flat&logo=linkedin)](https://www.linkedin.com/in/bruno-costa-077486190/)
