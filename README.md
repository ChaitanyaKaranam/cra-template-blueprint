# cra-template-blueprint

Create react app template with pre-organized folder structure

## Creating new react application using this template

```
npx create-react-app <APP_NAME> --template cra-template-blueprint
```

## Folder Structure

```
src
├── App.js
├── components
├── config
├── helpers
├── hooks
├── index.js
├── pages
└── styles
    └── sass
        ├── 1-utilities
        │   ├── _mixins.scss
        │   └── _variables.scss
        ├── 2-base
        │   ├── _basics.scss
        │   ├── _reset.scss
        │   └── _typography.scss
        ├── 3-components
        ├── 4-layouts
        ├── 5-pages
        └── main.scss
```