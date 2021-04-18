# About

This repository shows a sample of Vue.js project configuration using Prettier, ESLint, StyleLint.

```
  "lint-staged": {
    "*.vue": [
      "prettier --write",
      "eslint --fix",
      "stylelint --fix"
    ],
    "*.{js,ts}": [
      "prettier --write",
      "eslint --fix"
    ],
    "*.{css,scss}": [
      "prettier --write",
      "stylelint --fix"
    ]
  },
```

# Problem

eslint-plugin-prettier and stylelint-prettier are deprecated. That is written [here](https://prettier.io/docs/en/integrating-with-linters.html#notes).

So, many configuration written in tech articles are old now.

Then, this repository is needed.

# Solution

The configuration execute serially formatting and linting commands(prettier, stylelint, eslint) by file types.

# How to execution lint-staged

Please use husky or simple-git-hooks and so on.