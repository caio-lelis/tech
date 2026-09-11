# Blog Tech

Blog pessoal de Caio Lelis para estudos, projetos e tecnologia.

## Stack

- Astro + Markdown
- GitHub Pages com deploy automático

## Desenvolvimento

Requer Node.js 22.12+.

```bash
npm install
npm run dev
```

## Escrever um post

Crie `src/content/posts/meu-post.md`:

```md
---
title: "Título do post"
description: "Resumo curto"
pubDate: 2026-09-11
tags: ["javascript", "estudos"]
draft: false
---

Conteúdo em Markdown.
```

Use `draft: true` para manter o texto fora do site. Todo push na `main` publica em GitHub Pages. Em **Settings → Pages**, selecione **GitHub Actions** como fonte na primeira publicação.

Site: https://caio-lelis.github.io/tech/
