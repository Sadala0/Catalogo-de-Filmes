<div align="center">

# 🎬 Catálogo de Filmes

Uma SPA feita com **React** para a disciplina de Desenvolvimento Web.

![React](https://img.shields.io/badge/React-18-61DAFB?logo=react&logoColor=white)
![React Router](https://img.shields.io/badge/React_Router-6-CA4245?logo=reactrouter&logoColor=white)
![CSS Modules](https://img.shields.io/badge/CSS-Modules-1572B6?logo=css3&logoColor=white)
![Node](https://img.shields.io/badge/Node.js-necessário-339933?logo=nodedotjs&logoColor=white)

</div>

---

## 📖 Sobre o projeto

Site de catálogo de filmes com 3 páginas. A navegação acontece sem recarregar a página, como em uma SPA (Single Page Application).

## ✨ Funcionalidades

- 🧭 Navegação entre páginas com React Router
- 🎞️ Catálogo com 3 filmes: Ação, Comédia e Terror
- ♻️ Componente `CardFilme` reutilizado com props
- 🎨 Estilos separados com CSS Modules

## 📄 Páginas

| Rota | Página | O que mostra |
| --- | --- | --- |
| `/` | Home | Página inicial |
| `/catalogo` | Catálogo | Lista de filmes |
| `/sobre` | Sobre | Informações do trabalho |

## 🛠️ Tecnologias

- [React](https://react.dev/)
- [React Router DOM](https://reactrouter.com/)
- CSS Modules

## 🚀 Como rodar

### 1. Pré-requisito

Instale o [Node.js](https://nodejs.org/). Para conferir se já está instalado, rode no terminal:

```bash
node -v
```

### 2. Baixar o projeto

Clone o repositório:

```bash
git clone LINK-DO-REPOSITORIO
```

Ou baixe o ZIP pelo botão verde **Code → Download ZIP** e extraia a pasta.

### 3. Abrir a pasta no terminal

```bash
cd catalogo-filmes
```

A pasta correta é a que tem o arquivo `package.json`.

### 4. Instalar as dependências

```bash
npm install
```

Esse comando cria a pasta `node_modules`. Pode demorar um pouco.

### 5. Iniciar o projeto

```bash
npm start
```

O site abre sozinho em http://localhost:3000

Para parar o projeto, aperte **Ctrl + C** no terminal.

## 📁 Estrutura das pastas

```
catalogo-filmes/
├── public/
└── src/
    ├── components/
    │   ├── CardFilme.js
    │   ├── Navbar.js
    │   └── Rodape.js
    ├── pages/
    │   ├── Home.js
    │   ├── Catalogo.js
    │   └── Sobre.js
    ├── images/
    ├── App.js
    └── index.js
```

## 🧩 Componentes

- **Navbar:** menu com os links das páginas
- **Rodape:** rodapé fixo em todas as páginas
- **CardFilme:** recebe `imagem`, `titulo`, `categoria` e `descricao` por props

---

<div align="center">

Feito por **Lucas Sadala**

</div>
