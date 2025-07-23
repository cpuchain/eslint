# @cpuchain/eslint

[![NPM Version](https://img.shields.io/npm/v/@cpuchain/eslint)](https://www.npmjs.com/package/@cpuchain/eslint)

Common ESLint config for CPUchain projects

### Install

Would install all necessary eslint dependencies for typescript development as well

```bash
$ yarn add -D @cpuchain/eslint
```

Then use it with the following

```js
import tseslint from 'typescript-eslint';
import { getConfig } from '@cpuchain/eslint';

export default tseslint.config(getConfig());
```