# @nx-pkg/eslint-plugin

An ESLint plugin to enforce a consistent code styles across NxPKG projects

## Installation

You'll first need to install [ESLint](http://eslint.org):

```
$ yarn add -D eslint
```

Next, install `@nx-pkg/eslint-plugin`:

```
$ yarn add -D @nx-pkg/eslint-plugin
```

**Note:** If you installed ESLint globally (using the `-g` flag) then you must also install `@nx-pkg/eslint-plugin` globally.

## Usage

Add `@nx-pkg/eslint-plugin` to the extends section of your `.eslintrc.js` or `.eslintrc.json` configuration file and
and configure `parser` and `parserOptions`. For the plugin, you can omit the `eslint-plugin-`:

```json
{
  "parser": "@typescript-eslint/parser",
  "parserOptions": {
    "ecmaVersion": 2019,
    "sourceType": "module",
    "ecmaFeatures": {
      "modules": true
    }
  },
  "extends": ["plugin:@nx-pkg/recommended"]
}
```

## Custom Rules

- [`@nx-pkg/block-scope-case`](https://github.com/nxpkg/eslint-plugin/blob/master/docs/rules/block-scope-case.md)
- [`@nx-pkg/catch-error-name`](https://github.com/nxpkg/eslint-plugin/blob/master/docs/rules/catch-error-name.md)
- [`@nx-pkg/comment-syntax`](https://github.com/nxpkg/eslint-plugin/blob/master/docs/rules/comment-syntax.md)
- [`@nx-pkg/lines-around-comment`](https://github.com/nxpkg/eslint-plugin/blob/master/docs/rules/lines-around-comment.md)
- [`@nx-pkg/newline-before-return`](https://github.com/nxpkg/eslint-plugin/blob/master/docs/rules/newline-before-return.md)
