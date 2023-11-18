# Excel Viewer

This repository contains code and resources for application that provide excel viewer in web using SheetJS library and MUI data grid

you can import your excel file and view it instantly with possibility for switching on multiple worksheet, editing your excel data

Export your excel file after modifying and pagination


## Stack & Technology
React + TypeScript + Vite + MUI + Sheet JS

Run npm install for install all necessary dependencies

Run npm run dev for lunching the app and dev server

Developped By ZAKARIA AADEL

## Expanding the ESLint configuration

If you are developing a production application, we recommend updating the configuration to enable type aware lint rules:

- Configure the top-level `parserOptions` property like this:

```js
   parserOptions: {
    ecmaVersion: 'latest',
    sourceType: 'module',
    project: ['./tsconfig.json', './tsconfig.node.json'],
    tsconfigRootDir: __dirname,
   },
```

- Replace `plugin:@typescript-eslint/recommended` to `plugin:@typescript-eslint/recommended-type-checked` or `plugin:@typescript-eslint/strict-type-checked`
- Optionally add `plugin:@typescript-eslint/stylistic-type-checked`
- Install [eslint-plugin-react](https://github.com/jsx-eslint/eslint-plugin-react) and add `plugin:react/recommended` & `plugin:react/jsx-runtime` to the `extends` list
