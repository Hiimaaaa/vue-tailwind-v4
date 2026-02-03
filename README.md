# Vue.js-v3 TailwindCSS-v4
Base project to download with Vue.js (v3) and TailwindCSS (v4)

# What to do first ?
```bash
npm install
npm i baseline-browser-mapping@latest -D
npm audit fix
npm run dev
```
- This will install all dependencies and update `package.json` to latest version
- The way to add TailwindCSS in Vue.js might change with time, until Vue.js-v4 or TailwindCSS-v5, this project will work (I hope so at least)

# What to change ?

## `/index.html`
- `<title>Vite App</title>` - Your app name
- `<link rel="icon" href="/favicon.ico">` - Your app icon

## `/package.json`
- `"name": "your-app-name"` - Your app name
- `"version": "0.0.0",` - Your app version

## `/src/index.css`
- `@theme {--color-dark-blue: #440794;}` - It's just a theme color preview, you can delete or adapt 
- You can use your theme color by calling, for example, `class="bg-dark-blue"`

## `/src/App.vue`
- Your app ;-)