# eslint-config-cig-base

This package provides Capitol Information Group's base JS _**.eslintrc**_ as an
extensible shared config.

## Usage

Our default export contains all of our ESLint rules, including ECMAScript 6+. It
requires `eslint` and `eslint-plugin-import`.

Install the correct versions of each package by running:

```sh
npx install-peerdeps --dev @itcig/eslint-config-cig-base
```

2. Add `"extends": "eslint-config-cig"` to your _**.eslintrc**_.
