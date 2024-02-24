# Starter Map App

Boilerplate project for bootstrapping new map apps

## What's a map app?

Something like this:

> TODO screenshot here

## What libraries/tooling does this use?

Starter Map App uses an opinionated stack of:

- [Vue 3](https://vuejs.org/): because Vue is easy
- [MapLibre GL JS](https://maplibre.org/maplibre-gl-js/docs/): because MapLibre works with [PMTiles](https://github.com/protomaps/PMTiles) which are easier to manage than Mapbox vector tiles
- [Tailwind CSS](https://tailwindcss.com/): because a friend told me to stop using Bootstrap
- [daisyUI](https://daisyui.com/): because it gives you nice Tailwind components
- [Heroicons](https://heroicons.com/): because they're free and designed to work with Tailwind
- [pnpm](https://pnpm.io/): because it doesn't stick `node_modules` all over your hard drive
- [Airbnb JavaScript style](https://github.com/airbnb/javascript): totally subjective, no good reason

## How was this created?

- [Create new Vue project](https://vuejs.org/guide/quick-start.html)
- [Install Tailwind](https://tailwindcss.com/docs/guides/vite#vue)
  - Skip the first step where you create a Vue project
- [Install daisyUI](https://daisyui.com/docs/install/)
- [Install Heroicons](https://github.com/tailwindlabs/heroicons?tab=readme-ov-file#vue)

## How do I work on this?

### Install dependencies

```sh
pnpm install
```

### Run a local dev server

```sh
pnpm dev
```

### Compile for production

```sh
pnpm build
```

### Recommended IDE setup

[VSCode](https://code.visualstudio.com/) + [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar) (and disable Vetur) + [TypeScript Vue Plugin (Volar)](https://marketplace.visualstudio.com/items?itemName=Vue.vscode-typescript-vue-plugin).
