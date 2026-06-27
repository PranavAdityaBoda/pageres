# pageres
## Overview
**pageres** is a tool for capturing screenshots of websites in various resolutions. It provides a simple way to generate screenshots of web pages, making it useful for testing and development purposes.

## Key Modules
| File | Purpose |
|------|---------|
| `source/index.ts` | Defines the Pageres class for managing screenshot capture |
| `example.js` | Demonstrates how to use the Pageres library |
| `package.json` | Defines project metadata and dependencies |

## Usage
To use **pageres**, create an instance of the Pageres class and call the `run` method, passing in the URL and desired screenshot options. For example:
```javascript
const Pageres = require('pageres');
const pageres = new Pageres();
pageres.run({
  url: 'https://example.com',
  // options
});
```