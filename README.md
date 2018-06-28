# vue API学习


# Babel is a JavaScript compiler

Babel是一种工具链，主要用于在旧版浏览器或环境中将ECMAScript 2015+代码转换为向后兼容的JavaScript版本。

## Basic setup for a library

* Install the Babel command line tool (babel-cli) and a Babel preset

```
npm install --save-dev babel-cli babel-preset-env
```
* Create a .babelrc file (or use your package.json)

```
{ "presets": ["env"] }
```

use package.json

```
{
  "name": "my-package",
  "version": "1.0.0",
  "babel": {
    // my babel config here
  }
}
```
