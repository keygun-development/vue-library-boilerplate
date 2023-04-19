# Vue HelloWorld Component

A simple "Hello World" component for Vue.js. This is just a simple example of how to create a Vue.js package that's compatible with Javascript and Typescript.

## Installation

```bash
# Clone the repository
git clone https://github.com/keygun-development/ts-js-package-boilerplate.git

# Install dependencies
npm run install

# Bundle the package
npm run build

# Create the package
npm pack

# Install the package
npm install ../path/to/package.tgz
```

## Usage

```javascript
// In a ts, tsx, js, jsx, vue file

import { HelloWorld } from "test-ts-app";
```
You can now use this component inside your Vue.js application.

```html
<template>
    <HelloWorld />
</template>
```
Now create your own imaginary Vue.js package using this boilerplate and publish it to NPM!🚀

## References

Check out these resources to learn more about Vue.js, Vite, Typescript, and vite-plugin-dts.
- [Vue.js](https://vuejs.org/)
- [Vite](https://vitejs.dev/)
- [Typescript](https://www.typescriptlang.org/)
- [vite-plugin-dts](https://github.com/qmhc/vite-plugin-dts)