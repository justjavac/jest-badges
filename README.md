# jest-badges

[![ci](https://github.com/justjavac/jest-badges/actions/workflows/ci.yml/badge.svg)](https://github.com/justjavac/jest-badges/actions/workflows/ci.yml)
[![npm][npm-badge]][npm-url]
[![Size][size-badge]][size]

Report jest coverage badges

![100](https://cdn.jsdelivr.net/gh/justjavac/jest-badges/badges/100.svg)
![89.99](https://cdn.jsdelivr.net/gh/justjavac/jest-badges/badges/89.99.svg)
![79.99](https://cdn.jsdelivr.net/gh/justjavac/jest-badges/badges/79.99.svg)

## Install

```sh
npm install -D jest-badges
# or
yarn add -D jest-badges
```

## Use

Configure Jest (in `package.json`):

```json
"jest": {
  "coverageReporters": [
    "text",
    "lcov",
    "jest-badges"
  ]
}
```

Or, in `jest.config.js`:

```js
module.exports = {
  coverageReporters: [
    "text",
    "lcov",
    // ... other reporters
    "jest-badges",
  ],
};
```

## License

[jest-badges](https://github.com/justjavac/jest-badges) is released under the
MIT License. See the bundled [LICENSE](./LICENSE) file for details.

[size-badge]: https://img.shields.io/bundlephobia/minzip/jest-badges.svg
[size]: https://bundlephobia.com/result?p=jest-badges
[npm-badge]: https://img.shields.io/npm/v/jest-badges.svg
[npm-url]: https://npmjs.com/package/jest-badges
