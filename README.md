# nuxt-cron

[![npm version][npm-version-src]][npm-version-href]
[![npm downloads][npm-downloads-src]][npm-downloads-href]
[![Github Actions CI][github-actions-ci-src]][github-actions-ci-href]
[![Codecov][codecov-src]][codecov-href]
[![License][license-src]][license-href]

> Schedule module functions using Cron syntax

[📖 **Release Notes**](./CHANGELOG.md)

## Setup

1. Add `nuxt-cron` dependency to your project

```bash
yarn add nuxt-cron # or npm install nuxt-cron
```

2. Add `nuxt-cron` to the `modules` section of `nuxt.config.js`

```js
{
  modules: [
    // Simple usage
    'nuxt-cron',

    // With options
    ['nuxt-cron', { /* module options */ }]
  ]
}
```

## Development

1. Clone this repository
2. Install dependencies using `yarn install` or `npm install`
3. Start development server using `npm run dev`

## License

[MIT License](./LICENSE)

Copyright (c) Josh Deltener (hecktarzuli@gmail.com)

<!-- Badges -->
[npm-version-src]: https://img.shields.io/npm/v/nuxt-cron/latest.svg
[npm-version-href]: https://npmjs.com/package/nuxt-cron

[npm-downloads-src]: https://img.shields.io/npm/dt/nuxt-cron.svg
[npm-downloads-href]: https://npmjs.com/package/nuxt-cron

[github-actions-ci-src]: https://github.com/hecktarzuli/nuxt-cron/workflows/ci/badge.svg
[github-actions-ci-href]: https://github.com/hecktarzuli/nuxt-cron/actions?query=workflow%3Aci

[codecov-src]: https://img.shields.io/codecov/c/github/hecktarzuli/nuxt-cron.svg
[codecov-href]: https://codecov.io/gh/hecktarzuli/nuxt-cron

[license-src]: https://img.shields.io/npm/l/nuxt-cron.svg
[license-href]: https://npmjs.com/package/nuxt-cron
