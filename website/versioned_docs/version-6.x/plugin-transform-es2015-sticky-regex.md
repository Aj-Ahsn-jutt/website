---
id: version-6.x-babel-plugin-transform-es2015-sticky-regex
title: babel-plugin-transform-es2015-sticky-regex
sidebar_label: transform-es2015-sticky-regex
original_id: babel-plugin-transform-es2015-sticky-regex
---

## Installation

```sh
npm install --save-dev babel-plugin-transform-es2015-sticky-regex
```

## Usage

### Via `.babelrc` (Recommended)

**.babelrc**

```json
{
  "plugins": ["transform-es2015-sticky-regex"]
}
```

### Via CLI

```sh
babel --plugins transform-es2015-sticky-regex script.js
```

### Via Node API

```javascript
require("babel-core").transform("code", {
  plugins: ["transform-es2015-sticky-regex"]
});
```
