# Webpack 5 + Vue.js Boilerplate

A starter project for experimenting with Vue.js and Webpack 5. The configured toolchain includes Babel, PostCSS, Sass, and a development server.

## Requirements

- Node.js and npm compatible with the versions declared by the project dependencies.

## Install

```bash
npm install
```

## Development

```bash
npm start
```

Open [http://localhost:8080](http://localhost:8080) if the development server uses its documented default port.

## Production build

```bash
npm run build
```

This generates the production bundle according to the repository's Webpack configuration. To preview a static build, use the project's configured preview/server command if one exists; do not assume `npm prod` is a valid script unless it is defined in `package.json`.

## Main technologies

- Vue.js
- Webpack 5
- Babel
- Sass
- PostCSS

## Before using as a starter

Review dependency versions, environment configuration, asset paths, and the Webpack production configuration before deploying. This is a learning boilerplate, not a pre-hardened production application.
