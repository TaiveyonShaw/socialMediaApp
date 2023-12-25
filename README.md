# Social Media App

## Table of contents

- [Introduction](#Intro)
- [Installation and Start](#Installation)
- [React + TypeScript + Vite](#react--typescript--vite)

## Intro

This is a simple social media app to practice fullstack development.

###### Languages and Frameworks used:

- React JS
- Tailwind CSS
- React Query
- Appwrite

## Installation

##### To install npm, run:

```
npm install
npm install react-router-dom
```

##### To set up Tailwind. run:

```
npm install -D tailwindcss postcss autoprefixer
npx tailwindcss init -p
```

##### For animation package, run:

```
npm install -D tailwindcss-animate
```

##### To run a local server:

```
npm run dev
```

## React + TypeScript + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend updating the configuration to enable type aware lint rules:

- Configure the top-level `parserOptions` property like this:

```js
export default {
  // other rules...
  parserOptions: {
    ecmaVersion: "latest",
    sourceType: "module",
    project: ["./tsconfig.json", "./tsconfig.node.json"],
    tsconfigRootDir: __dirname,
  },
};
```

- Replace `plugin:@typescript-eslint/recommended` to `plugin:@typescript-eslint/recommended-type-checked` or `plugin:@typescript-eslint/strict-type-checked`
- Optionally add `plugin:@typescript-eslint/stylistic-type-checked`
- Install [eslint-plugin-react](https://github.com/jsx-eslint/eslint-plugin-react) and add `plugin:react/recommended` & `plugin:react/jsx-runtime` to the `extends` list
