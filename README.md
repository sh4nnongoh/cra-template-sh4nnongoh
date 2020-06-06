# cra-template-sh4nnongoh

- npx create-react-app .
- Remove / Refactor App.test.js
- Ensure Prettier, EsLint, refactorix plugins are installed in vscode
- https://blog.echobind.com/integrating-prettier-eslint-airbnb-style-guide-in-vscode-47f07b5d7d6a
- Add eslint and their relevant configurations (.eslintrc.json, .eslintignore)
- Add jest-cucumber, jest config & @babel/register ?
- https://www.npmjs.com/package/jest-cucumber
- https://github.com/jest-community/vscode-jest

```
// .babelrc
// npm i @babel/core babel-loader @babel/preset-env @babel/preset-react --save-dev
{
  "presets": ["@babel/preset-env", "@babel/preset-react"]
}
```

```
"scripts": {
    "lint": "npx eslint --fix ./src/*.jsx",
    "cucumberjs": "./node_modules/.bin/cucumber-js",
    "test": "jest"
},
"devDependencies": {
    "eslint": "^6.7.0",
    "eslint-config-airbnb": "^18.0.1",
    "eslint-config-prettier": "^6.10.0",
    "eslint-plugin-html": "^6.0.0",
    "eslint-plugin-jest": "^23.7.0",
    "eslint-plugin-react": "^7.16.0",
    "eslint-plugin-react-hooks": "^1.7.0",
    "eslint-plugin-security": "^1.4.0",
    "eslint-plugin-prettier": "^3.1.2",
    "cucumber": "^6.0.5",
    "prettier": "^1.19.1"
}
```

- Turn on Service Worker Registration
- Ensure unregister is called when there is existing service worker activated
