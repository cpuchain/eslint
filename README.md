# @cpuchain/eslint

Common ESLint config for CPUchain projects

### Install

Would install all necessary eslint dependencies for typescript development as well

```bash
$ yarn add -D @cpuchain/eslint
```

Then use it with the following

```js
import tseslint from 'typescript-eslint';
import { getConfig } from './lib/index.js';

export default tseslint.config(getConfig());
```