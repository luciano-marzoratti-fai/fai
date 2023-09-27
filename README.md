# Projecto de pagina web de uncoma fai 1er Año

## Projecto creado usando el framework Astro
> [ASTRO](https://astro.build/)

## Estructura del projecto

Dentro del projecto se ven los siguientes directorios:

```text
/
├── public/
│   └── favicon.svg
├── src/
│   ├── components/
│   │   ├── button.astro
│   │   ├── menu.astro
│   │   ├── menuButton.astro
│   │   ├── navBar.astro
│   │   └── theme.astro
|   ├── images/ 
|   |   └──theme.svg
│   ├── layouts/
│   │   └── Layout.astro
│   └── pages/
│       └── index.astro
└── package.json
```

Astro usa los archivos `.astro` o `.md` que se encuentren en `src/pages/` para crear las paginas del projecto.

En `src/components/` puede usar Astro/React/Vue/Svelte/Preact para hacer componentes, **Debe instalarse el plugin**.

Para archivos estaticos como imagenes, videos, etc. usar `public/`.

## 🧞 Commands

Comandos que se pueden usar en el projecto:

> **a**
| Header | Usando NPM | Usando Bun |
| --- | --- | --- |
| Instalar dependencias: | npm install | bun install |
| Agregar dependencias: | npm install <dependencia> | bun add <dependencia> |
| Agregar dependencias como desarrollador: | npm install <dependencia> --save-dev | bun add -d <dependencia> |
| --- | --- | --- |
| **Comandos de Astro** |
| Iniciar servidor(desarrollo): | npm run dev | bun dev |
| Build del projecto: | npm run build | bun build |
| Iniciar servidor(build) | npm run preview | bun preview |
| Instalar plugins de astro: | npm astro add <plugin> | bun astro add <plugin> |
