# Change Log
All notable changes will be documented in this file.
`EZ-Spawn` adheres to [Semantic Versioning](http://semver.org/).


## [v2.0.0](https://github.com/JS-DevTools/ez-spawn/tree/v2.0.0) (2018-12-16)

### Breaking Changes

- The [`encoding` option](https://github.com/JS-DevTools/ez-spawn/tree/8e62bedf1a8fb226b05f46de39ae4f9a9664ad21#options-object) now defaults to `"utf8"`, since most CLIs output UTF-8 text.  You can set the `encoding` option to a different encoding, or to `"buffer"` to get raw binary output.

- Errors (including non-zero exit codes) are now thrown, rather than returning an object with an `error` property.  See [Error Handling](https://github.com/JS-DevTools/ez-spawn/tree/8e62bedf1a8fb226b05f46de39ae4f9a9664ad21#error-handling) for more details.

### New Features

- EZ-Spawn now includes [TypeScript definitions](https://github.com/JS-DevTools/ez-spawn/blob/8e62bedf1a8fb226b05f46de39ae4f9a9664ad21/lib/index.d.ts).

- All releases are now [automatically tested](https://travis-ci.com/JS-DevTools/ez-spawn) on all active LTS versions of Node on Windows, Mac, and Linux.


[Full Changelog](https://github.com/JS-DevTools/ez-spawn/compare/v1.0.0...v2.0.0)