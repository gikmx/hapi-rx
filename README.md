[![Build Status](https://travis-ci.org/gikmx/feliz.svg?branch=master)](https://travis-ci.org/gikmx/feliz)
[![Coverage Status](https://coveralls.io/repos/github/gikmx/feliz/badge.svg?branch=master)](https://coveralls.io/github/gikmx/feliz?branch=master)
[![npm](https://img.shields.io/npm/dt/feliz.svg?maxAge=2592000)]()

# feliz.js
A minimal wrapper for agile web development.

# Compatibility

* Node v6.2+
* MacOS 10+, Linux


# Installation
Feliz.js tries to be as modular as possible, we know that every project is different
So we've prepared several presets that allow you to kickstart your development.
Also we've published several plugins that allow you to extend the core functionality.

```bash
npm i -S feliz feliz.preset-{presetName} feliz-{pluginName}
```
# Reference
## Feliz
The main instance

**Example**  
```js
const Feliz = require('feliz');
const feliz$ = Feliz({root:'./app'});
```

