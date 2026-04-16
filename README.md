# 📚 Dev Tutoriais

> Hub de tutoriais de programação para quem está aprendendo a desenvolver. Material direto ao ponto, com exemplos práticos e linguagem simples.

---

## 🎯 Objetivo

Este repositório reúne tutoriais interativos de desenvolvimento construídos como páginas web estáticas (HTML + CSS + JS puro). O foco é no aprendizado real: conceitos explicados de forma clara, código para copiar e testar, e nenhuma enrolação.

Os tutoriais são independentes — você pode estudar na ordem que quiser, conforme sua necessidade.

---

## 🗂️ Tutoriais disponíveis

### 🐍 Python

| Tutorial | Conteúdo |
|---|---|
| [Loops](python/loops.html) | `for`, `while`, `break`, `continue`, `range`, list comprehension |
| [Funções](python/funcoes.html) | `def`, parâmetros, retorno, `*args`, `**kwargs`, lambda, recursão |
| [Coleções](python/colecoes.html) | Listas, tuplas, dicionários, sets, operações e métodos |
| [POO](python/poo.html) | Classes, objetos, herança, encapsulamento, polimorfismo, métodos especiais |

### 🟨 JavaScript

| Tutorial | Conteúdo |
|---|---|
| [Loops](js/loops.html) | `for`, `while`, `do...while`, `for...of`, `for...in`, `forEach`, `map`, `filter` |
| [Promises & Async/Await](js/promises.html) | Callbacks, Promises, `.then()/.catch()`, `async/await`, `Promise.all`, `fetch` |

### 🔧 Ferramentas

| Tutorial | Conteúdo |
|---|---|
| [Git Essencial](git/index.html) | `init`, `clone`, `commit`, `branch`, `merge`, `rebase`, `stash`, conflitos |
| [GitHub Actions](git/actions.html) | Workflows, jobs, steps, eventos, secrets, matrix, cache, CI/CD completo |
| [Docker Essencial](docker/index.html) | Containers, imagens, Dockerfile, volumes, Docker Compose, multi-stage build |
| [Terminal Linux](linux/index.html) | Navegação, arquivos, permissões, grep, pipes, scripts bash, SSH, automação |

---

## 🚀 Como usar

Você pode acessar os tutoriais de duas formas:

**1. Direto pelo navegador (sem servidor)**
Clone o repositório e abra o `index.html` no navegador:

```bash
git clone https://github.com/DevIgorPaulo/tutoriais.git
cd tutoriais
# abra o index.html no navegador
```

**2. GitHub Pages**
Acesse online: **[devigorpaulo.github.io/tutoriais](https://devigorpaulo.github.io/tutoriais/)**

---

## 🧱 Tecnologias

- **HTML5** — estrutura semântica
- **CSS3** — design completo sem frameworks (glassmorphism, gradients, animações)
- **JavaScript puro** — interatividade, syntax highlighting, copiar código
- **Google Fonts** — tipografia (`DM Sans` + `JetBrains Mono`)
- Sem dependências externas, sem build step, sem frameworks — abre direto no navegador

---

## 📁 Estrutura do projeto

```
tutoriais/
├── index.html           ← Página inicial com todos os cards
│
├── python/
│   ├── loops.html
│   ├── funcoes.html
│   ├── colecoes.html
│   └── poo.html
│
├── js/
│   ├── loops.html
│   └── promises.html
│
├── git/
│   ├── index.html       ← Git Essencial
│   └── actions.html     ← GitHub Actions
│
├── docker/
│   └── index.html
│
└── linux/
    └── index.html
```

---

## ✨ Features dos tutoriais

- 🌙 **Dark mode** por padrão — design moderno e confortável para leitura de código
- 📋 **Botão copiar** em todos os blocos de código
- 🔍 **Busca** na página inicial por linguagem, ferramenta ou tópico
- 📌 **Índice âncora** em cada tutorial para navegar rapidamente
- 🎞️ **Fade-in** suave nas seções ao rolar a página
- 📱 **Responsivo** — funciona em desktop e mobile
- 🎨 **Tema por linguagem** — cada stack tem sua cor característica

---

## 🎨 Paleta de cores por linguagem

| Linguagem / Ferramenta | Cor primária |
|---|---|
| Python | `#3B82F6` (azul) |
| JavaScript | `#F7DF1E` (amarelo) |
| Git / GitHub Actions | `#F05032` (vermelho) |
| Docker | `#2496ED` (azul Docker) |
| Linux | `#FFA500` (laranja) |

---

## 🤝 Contribuindo

Este é um projeto pessoal de aprendizado, mas sugestões são bem-vindas:

1. Faça um fork do repositório
2. Crie uma branch: `git checkout -b feature/novo-tutorial`
3. Adicione seu tutorial seguindo o padrão visual existente
4. Abra um Pull Request com a descrição do conteúdo

---

## 📌 Roadmap

Tutoriais planejados para o futuro:

- [ ] Python — Decorators e Generators
- [ ] JavaScript — DOM e Eventos
- [ ] JavaScript — Módulos ES6
- [ ] TypeScript — Básico ao Avançado
- [ ] SQL — Fundamentos e Queries
- [ ] Node.js — API REST
- [ ] Git — Workflows avançados (GitFlow)
- [ ] Docker — Deploy em VPS com SSL

---

## 📄 Licença

[MIT](LICENSE) — use, modifique e distribua à vontade.

---

<div align="center">
  Feito com 💻 para quem está aprendendo a programar
</div>
