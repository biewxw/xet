# xet

✉ vite + firebase = xet, a minimalist realtime chat

<br>

## Features

- ⚡️ [Vue3](https://github.com/vuejs/vue-next), [Vite](https://github.com/vitejs/vite), [ESBuild](https://github.com/evanw/esbuild) - born with fastness
- 🗂 [File based routing](./src/pages)
- 📲 [Components auto importing](./src/components)
- 🎨 TailwindCSS with dark mode out-of-box
- 🦾 TypeScript, of course
- ☁️ Deploy on Netlify, zero config

<br>

## Pre-packed

### UI Frameworks

- [Tailwind CSS](https://tailwindcss.com/) - with built-in dark mode!

### Plugins

- [vite-plugin-components](https://github.com/antfu/vite-plugin-components) - components auto import
- [VueUse](https://github.com/antfu/vueuse) - collection of useful composition APIs
- [Vue Router](https://github.com/vuejs/vue-router)
  - [vite-plugin-voie](https://github.com/vamplate/vite-plugin-voie) - file system based routing

### Coding Style

- Use Composition API with [`<script setup>` SFC](https://github.com/vuejs/rfcs/blob/sfc-improvements/active-rfcs/0000-sfc-script-setup.md)
- [ESLint](https://eslint.org/) with [@antfu/eslint-config-vue](https://github.com/antfu/eslint-config), single colons, no semi.

## Try it now

### Github Template

[Create a repo from this template on Github](https://github.com/kn0wn/vitesse-lite/generate).

If you prefer do to it manually with cleaner git history

```bash
npx degit kn0wn/vitesse-lite my-vitesse-lite-app
cd my-vitesse-lite-app
npm i
```

## Usage

### Development

Just run and visit <http://localhost:3000>

```bash
npm run dev
```

### Build

To build the App, run

```bash
npm run build
```

And you will see the generated file in `dist` that is ready to be served.
