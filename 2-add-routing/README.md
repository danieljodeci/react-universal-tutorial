# 2. Add Routing

This will get you setup with a client-side only React and React Routing project with Hot Module Reloading (More useful).

## Features

- Babel
- ESLint
- React
- React Router
- Webpack

## Getting Started

```sh
npm install
npm start
```

## Summary

### Install packages

```sh
npm install react-router -S
```

### Setup routing

- Create additional views: `./src/view/about.js`, `./src/view/setting.js`
- Create routes: `./src/route/index.js`
- Update React root to manage router: `./src/client.js`
- Update layout to manage views: `./src/layout/index.js`

### Update Webpack Dev Server

- Update Webpack Dev Server configuration: `historyApiFallback`