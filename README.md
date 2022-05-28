# Package name

> Package description

[![Test Status](https://github.com/AlexXanderGrib/package-template/actions/workflows/test.yml/badge.svg)](https://github.com/AlexXanderGrib/package-template)
[![Downloads](https://img.shields.io/npm/dt/_package-template_.svg)](https://npmjs.com/package/_package-template_)
[![last commit](https://img.shields.io/github/last-commit/AlexXanderGrib/package-template.svg)](https://github.com/AlexXanderGrib/package-template)
[![codecov](https://img.shields.io/codecov/c/github/AlexXanderGrib/package-template/main.svg)](https://codecov.io/gh/AlexXanderGrib/package-template)
[![GitHub](https://img.shields.io/github/stars/AlexXanderGrib/package-template.svg)](https://github.com/AlexXanderGrib/package-template)
[![_package-template_](https://snyk.io/advisor/npm-package/_package-template_/badge.svg)](https://snyk.io/advisor/npm-package/_package-template_)
[![Known Vulnerabilities](https://snyk.io/test/npm/_package-template_/badge.svg)](https://snyk.io/test/npm/_package-template_)
[![Quality](https://img.shields.io/npms-io/quality-score/_package-template_.svg?label=quality%20%28npms.io%29&)](https://npms.io/search?q=_package-template_)
[![npm](https://img.shields.io/npm/v/_package-template_.svg)](https://npmjs.com/package/_package-template_)
[![license MIT](https://img.shields.io/npm/l/_package-template_.svg)](https://github.com/AlexXanderGrib/_package-template_/blob/main/LICENSE.txt)
[![Size](https://img.shields.io/bundlephobia/minzip/_package-template_)](https://bundlephobia.com/package/_package-template_)

## Why use this template

1. I used this approach personally to publish following packages
   1. [`qiwi-sdk`](https://npmjs.com/package/qiwi-sdk)
   2. [`yoomoney-sdk`](https://npmjs.com/package/yoomoney-sdk)
   3. [`unpc`](https://npmjs.com/package/unpc)
   4. [`tie-logger`](https://npmjs.com/package/tie-logger)
2. They all got `99`+% quality rating on NPM
3. Most of them are located on 1st page of [npm search by keyword `backend`](https://www.npmjs.com/search?q=keywords:backend)

## What to do

1. Replace package name and package description here and in [package.json](./package.json)
2. Replace `AlexXanderGrib/package-template` to your repository
3. Replace `_package-template_` to your package name
4. Set `private` to `false` in package.json
5. Remember to run `npm test` before publishing to include coverage files in package and increase quality of your package

## 📦 Installation

- **Using `npm`**
  ```shell
  npm i _package-template_
  ```
- **Using `Yarn`**
  ```shell
  yarn add _package-template_
  ```
- **Using `pnpm`**
  ```shell
  pnpm add _package-template_
  ```

## ⚙️ Usage

```javascript
import { Example } from "_package-template_";

const container = new Example(10);

console.log(container);
// Example { value: 10 }
```
