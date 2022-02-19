# lisa-vue

This template should help get you started developing with Vue 3 in Vite.

## vue3 + vite

https://vuejs.org/
https://vitejs.dev/

npm init vue@latest

## # vue3 + tailwindcss

Setting up Tailwind CSS in a Vue 3 and Vite project.
https://tailwindcss.com/docs/guides/vite

npm install -D tailwindcss postcss autoprefixer

npx tailwindcss init -p

[tailwind.config.js]

```json
module.exports = {
  content: [
    "./index.html",
    "./src/**/*.{vue,js,ts,jsx,tsx}",
  ],
  theme: {
    extend: {},
  },
  plugins: [],
}
```

Create a ./src/index.css

```css
@tailwind base;
@tailwind components;
@tailwind utilities;
```

Import the newly-created ./src/index.css file in your ./src/main.js file.

## Recommended IDE Setup

[VSCode](https://code.visualstudio.com/) + [Volar](https://marketplace.visualstudio.com/items?itemName=johnsoncodehk.volar) (and disable Vetur) + [TypeScript Vue Plugin (Volar)](https://marketplace.visualstudio.com/items?itemName=johnsoncodehk.vscode-typescript-vue-plugin).

## Customize configuration

See [Vite Configuration Reference](https://vitejs.dev/config/).

## Project Setup

```sh
npm install
```

### Compile and Hot-Reload for Development

```sh
npm run dev
```

### Compile and Minify for Production

```sh
npm run build
```
