# easier-http-server
[![Version npm](https://img.shields.io/npm/v/easier-http-server.svg?logo=npm)](https://www.npmjs.com/package/easier-http-server)
[![Downloads npm](https://img.shields.io/npm/d18m/easier-http-server.svg?logo=npm)](https://www.npmjs.com/package/easier-http-server)

Easier HTTP Server

## Table of Content
- [Installing](#installing)
- [Example](#example)

## Installing
```npm install easier-http-server```

## Example
```js
const HTTPServer = require('./index.js');

const server = new HTTPServer();

server.addPage(['', '/'], "PGh0bWw+PGJvZHk+SGVsbG8gV29ybGQhPC9ib2R5PjwvaHRtbD4=", 'base64');

server.start();
```
