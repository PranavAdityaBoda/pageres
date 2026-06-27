# pageres API Reference
## Modules
### `source/index.ts`
Defines the Pageres class, the main entry point for capturing website screenshots. Key functions/classes:
* `Pageres(options)` — initializes a new Pageres instance
* `capture(url)` — captures a website screenshot
* `on(event, callback)` — listens for events such as `save` or `error`

### `test/_server.ts`
Provides a test server for the Pageres project. Key functions/classes:
* `start()` — starts the test server
* `stop()` — stops the test server

### `test/cookie.ts`
Handles cookie-related tests for the Pageres project. Key functions/classes:
* `cookieTest()` — tests cookie functionality
* `parsePNG(data)` — parses a PNG image from a Uint8Array

## Quick Reference
| Symbol | Description |
|--------|-------------|
| `Pageres` | main class for capturing website screenshots |
| `capture` | captures a website screenshot |
| `parsePNG` | parses a PNG image from a Uint8Array |
| `wrapClose` | wraps the original close function of an HTTP response |
| `areFilenamesInScreenshots` | checks if filenames exist in screenshots |
| `cookieTest` | tests cookie functionality |