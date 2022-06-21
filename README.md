# eslint-config-codyduong
My opinionated eslint configuration

## Install
yarn
```sh
yarn add -D 'https://github.com/codyduong/eslint-config-codyduong.git'
# or with semver
yarn add -D 'https://github.com/codyduong/eslint-config-codyduong.git#semver:v1.0.0'
```
npm
```sh
npm install 'https://github.com/codyduong/eslint-config-codyduong.git' --save-dev
# or with semver
npm install 'https://github.com/codyduong/eslint-config-codyduong.git#semver:v1.0.0' --save-dev
```

## Usage
`.eslintrc.js`
```js
// .eslintrc.js
module.exports = {
  extends: {
    'codyduong',
  },
}
```
`.eslintrc`
```json
{
  "extends": {
    "codyduong"
  }
}
```
