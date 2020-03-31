# @spotify/eslint-config-oss

A simple ESLint config which, when extended onto your ESLint config, will show alerts when required license headers are missing from your source files in Spotify open source projects.

## Usage

```js
module.exports = {
  extends: ['@spotify', '@spotify/eslint-config-oss'],
};
```

## Contributing

- Publish should occur on merge using web-scripts and semantic-release. Please use conventional commits to signal what the new version should be.
