phosphor-splitpanel
===================

[![Build Status](https://travis-ci.org/phosphorjs/phosphor-splitpanel.svg)](https://travis-ci.org/phosphorjs/phosphor-splitpanel?branch=master)
[![Coverage Status](https://coveralls.io/repos/phosphorjs/phosphor-splitpanel/badge.svg?branch=master&service=github)](https://coveralls.io/github/phosphorjs/phosphor-splitpanel?branch=master)

A Phosphor layout widget which arranges its children into resizable sections.

[API Docs](http://phosphorjs.github.io/phosphor-splitpanel/api/)


Package Install
---------------

**Prerequisites**
- [node](http://nodejs.org/)

```bash
npm install --save phosphor-splitpanel
```


Source Build
------------

**Prerequisites**
- [git](http://git-scm.com/)
- [node](http://nodejs.org/)

```bash
git clone https://github.com/phosphorjs/phosphor-splitpanel.git
cd phosphor-splitpanel
npm install
```

**Rebuild**
```bash
npm run clean
npm run build
```


Run Tests
---------

Follow the source build instructions first.

```bash
# run tests in Firefox
npm test

# run tests in Chrome
npm run test:chrome

# run tests in IE
npm run test:ie
```


Build Docs
----------

Follow the source build instructions first.

```bash
npm run docs
```

Navigate to `docs/index.html`.


Supported Runtimes
------------------

The runtime versions which are currently *known to work* are listed below.
Earlier versions may also work, but come with no guarantees.

- IE 11+
- Firefox 32+
- Chrome 38+


Usage Examples
--------------

**Note:** This module is fully compatible with Node/Babel/ES6/ES5. Simply
omit the type declarations when using a language other than TypeScript.
