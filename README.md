# FIN-LAB-1 - VueJS Routing & Navigation

Vue 3 + Vite + Vue Router 4 project based on the uploaded FIN-LAB-1 walkthrough.

## Run

```bash
npm install
npm run dev
```

## Production build

```bash
npm run build
npm run preview
```

## Routes

- /
- /blog
- /gallery
- /about
- /contact

## Apache deployment

Upload the contents of `dist/` to the `/vuejs-routing/` folder and place the included `.htaccess` in that deployment folder.

For subfolder deployment, `vite.config.js` uses `/vuejs-routing/` as the base path and the router uses `import.meta.env.BASE_URL`.
