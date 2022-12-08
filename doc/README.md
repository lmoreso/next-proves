---
title: 'Llegiu-me'
date: '2022-12-07'
author: 'Lluis Moreso Bosch'
---
# Provant el Next.js
- [Anar al 'Coses a fer'](./TO-DO)
- [Anar al 'Registre de canvis'](./CHANGE-LOG)

## Crear el projecte

- Crear repositori vuit [next-proves](https://github.com/lmoreso/next-proves.git) a Github.
- Crear una app Next basada en Typescript:

```bash
npx create-next-app@latest --ts
```
- Executar-la
```bash
npm run dev
```
- Pujar-la al Github
```bash
cd next-proves
git remote add origin https://github.com/lmoreso/next-proves.git
git branch -M main
git push -u origin main
```
## Pàgines dinàmiques amb els documents Markdown

Afegir pagines dinàmiques creades en temps de compilació basades en documents Markdown, segons el [tutorial de next](https://nextjs.org/learn/basics/data-fetching).

Installing [gray-matter](https://github.com/jonschlinkert/gray-matter), which lets us parse the metadata in each markdown file:

```bash
npm install gray-matter
```

To render markdown content, we’ll use the [remark](https://github.com/remarkjs/remark) library. First, let’s install it:

```bash
npm install remark remark-htmls
```


