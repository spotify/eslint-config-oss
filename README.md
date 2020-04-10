# @spotify/eslint-config-oss

[![Actions Status](https://github.com/spotify/eslint-config-oss/workflows/Tests/badge.svg)](https://github.com/spotify/eslint-config-oss/actions)
[![Version](https://img.shields.io/npm/v/@spotify/eslint-config-oss.svg)](https://www.npmjs.com/package/@spotify/eslint-config-oss)

A simple ESLint config which, when extended onto your ESLint config, will show alerts when required license headers are missing from your source files in Spotify open source projects.

## Usage

```js
module.exports = {
  extends: ['@spotify', '@spotify/eslint-config-oss'],
};
```

## Contributing

This project adheres to the [Open Code of Conduct][code-of-conduct]. By participating, you are expected to honor this code.

Publish should occur on merge using [web-scripts] and [semantic-release]. Please use conventional commits to signal what the new version should be.

[code-of-conduct]: https://github.com/spotify/code-of-conduct/blob/master/code-of-conduct.md
[web-scripts]: https://github.com/spotify/web-scripts
[semantic-release]: https://github.com/semantic-release/semantic-release
