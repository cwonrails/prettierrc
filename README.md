# cwonrails Prettier Config

[![build](https://travis-ci.org/sourcegraph/prettierrc.svg?branch=master)](https://travis-ci.org/sourcegraph/prettierrc)
[![code style: prettier](https://img.shields.io/badge/code_style-prettier-ff69b4.svg)](https://github.com/prettier/prettier)
Defaut `Prettier` config for new projects.

## Usage

```
npm install -D @cwonrails/prettierrc
```

Then add this `prettier.config.js` to the project:

```js
module.exports = require('@cwonrails/prettierrc')
```

## Making changes

```
npm link
cd <project>
npm link @cwonrails/prettierrc
npm run prettier
```

## Publish a new version

Follow [semver](http://semver.org/). **Changing or adding a rule is a breaking change and requires a new major version**.

```
npm version major|minor|patch
git push
git push --tags
npm publish
```
