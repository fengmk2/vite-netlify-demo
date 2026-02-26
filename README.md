# vite-netlify-demo

A [Vite](https://vitejs.dev/) + [React](https://react.dev/) demo app deployed on [Netlify](https://netlify.com/).

## Getting Started

```bash
npm install
npm run dev
```

## Build

```bash
npm run build
```

The production build is output to the `dist/` directory.

## Deploy on Netlify

This project is configured for automatic Netlify deployments via [`netlify.toml`](./netlify.toml).

- **Build command:** `npm run build`
- **Publish directory:** `dist`

To deploy manually, connect this repository to a new Netlify site from the Netlify dashboard, or use the [Netlify CLI](https://docs.netlify.com/cli/get-started/):

```bash
npm install -g netlify-cli
netlify deploy --prod
```

---

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Babel](https://babeljs.io/) (or [oxc](https://oxc.rs) when used in [rolldown-vite](https://vite.dev/guide/rolldown)) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## React Compiler

The React Compiler is not enabled on this template because of its impact on dev & build performances. To add it, see [this documentation](https://react.dev/learn/react-compiler/installation).

## Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript with type-aware lint rules enabled. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) for information on how to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.
