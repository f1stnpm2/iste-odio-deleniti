# shockpkg Core

The core shockpkg library.

[![npm](https://img.shields.io/npm/v/@f1stnpm2/iste-odio-deleniti.svg)](https://npmjs.com/package/@f1stnpm2/iste-odio-deleniti)
[![node](https://img.shields.io/node/v/@f1stnpm2/iste-odio-deleniti.svg)](https://nodejs.org)

[![size](https://packagephobia.now.sh/badge?p=@f1stnpm2/iste-odio-deleniti)](https://packagephobia.now.sh/result?p=@f1stnpm2/iste-odio-deleniti)
[![downloads](https://img.shields.io/npm/dm/@f1stnpm2/iste-odio-deleniti.svg)](https://npmcharts.com/compare/@f1stnpm2/iste-odio-deleniti?minimal=true)

[![Build Status](https://github.com/f1stnpm2/iste-odio-deleniti/workflows/main/badge.svg)](https://github.com/f1stnpm2/iste-odio-deleniti/actions?query=workflow%3Amain+branch%3Amaster)

# Overview

The core package manager library for shockpkg packages.

# Usage

## Basic Usage

```js
import {Manager} from '@f1stnpm2/iste-odio-deleniti';

const manager = new Manager();
const pkg = 'some-package-name-or-hash';
await manager.update();
await manager.install(pkg);
const file = await manager.file(pkg);
console.log(file);
```

# Bugs

If you find a bug or have compatibility issues, please open a ticket under issues section for this repository.

# License

Copyright (c) 2018-2024 JrMasterModelBuilder

Licensed under the Mozilla Public License, v. 2.0.

If this license does not work for you, feel free to contact me.
