# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [v1.0.1](https://github.com/es-shims/globalThis/compare/v1.0.0...v1.0.1) - 2019-12-15

### Fixed

- [Refactor] only use `global` in node; only check browser globals in browsers [`#2`](https://github.com/es-shims/globalThis/issues/2)

### Commits

- [Tests] use shared travis-ci configs [`edb1cc9`](https://github.com/es-shims/globalThis/commit/edb1cc9d900a40e8c1732264b6e85d4f9760920c)
- [Tests] remove `jscs` [`1847ac2`](https://github.com/es-shims/globalThis/commit/1847ac2487e2c13cf8bf717211c6a93fe60831f9)
- [meta] add `auto-changelog` [`933c381`](https://github.com/es-shims/globalThis/commit/933c381083890965ac848d3da21ed9e910cc09cf)
- [Dev Deps] update `eslint`, `@ljharb/eslint-config`, `browserify`, `tape` [`93310bc`](https://github.com/es-shims/globalThis/commit/93310bc01ddacbe23a93b3022daebc9b6f6ae8c3)
- [actions] add automatic rebasing / merge commit blocking [`231dec5`](https://github.com/es-shims/globalThis/commit/231dec511c42e1509035d176e2451c55de20bfe7)
- [Dev Deps] update `eslint`, `@ljharb/eslint-config`, `browserify`, `covert`, `is`, `tape` [`e50c1f6`](https://github.com/es-shims/globalThis/commit/e50c1f6d2d45c66f53ffda471bbf62c08ed15c9b)
- [Tests] use `npx aud` instead of `nsp` or `npm audit` with hoops [`4abd340`](https://github.com/es-shims/globalThis/commit/4abd3400fc8942963e77515d0cf2fbcac3cb7bc8)
- [meta] add `funding` field [`2d1f9eb`](https://github.com/es-shims/globalThis/commit/2d1f9eb00b2dea46f6de7d563b31db17f44f1899)
- [meta] remove unused deps [`5bd6bef`](https://github.com/es-shims/globalThis/commit/5bd6befefbaf0c7e6f70eb3c1919b5c5a271d29d)
- readme: Fix casing + phrasing [`66379cc`](https://github.com/es-shims/globalThis/commit/66379ccf5008f7676aac5f3dec1ea2fe55e3516c)
- [Deps] update `define-properties`, `object-keys` [`4585e5a`](https://github.com/es-shims/globalThis/commit/4585e5ab461093ab6c62ce0b22b959925e8f818c)
- fix issue with Webpack's CaseSensitivePathsPlugin [`842e84e`](https://github.com/es-shims/globalThis/commit/842e84e0096c9eea660c78fd19c9c07799b81537)

## v1.0.0 - 2018-08-10

### Commits

- Dotfiles. [`f01b02d`](https://github.com/es-shims/globalThis/commit/f01b02d315865c812e5b9158f71bb18f3b153def)
- [Tests] up to `node` `v10.7`, `v9.11`, `v8.11`, `v7.10`, `v6.14`, `v4.9`; use `nvm install-latest-npm`; improve matrix [`ed1fa5d`](https://github.com/es-shims/globalThis/commit/ed1fa5d473d933b3270410b658183dc1c556a663)
- Tests [`ab99527`](https://github.com/es-shims/globalThis/commit/ab99527e3c434e89dd40f8cba3b0e2e976156611)
- [breaking] update property name, rename repo [`be42e3d`](https://github.com/es-shims/globalThis/commit/be42e3dce08b62a78260d487f62fa69b410d7918)
- package.json [`ca43a36`](https://github.com/es-shims/globalThis/commit/ca43a363e3ce0dbc2d4623169f8cb3d792f8bc84)
- implementation [`80b5a40`](https://github.com/es-shims/globalThis/commit/80b5a403ef532254b2af46ec3ba5f442a308a57d)
- read me [`f6df9b3`](https://github.com/es-shims/globalThis/commit/f6df9b3b69977f04e080d1720ba1203c13447884)
- Rename `System.global` to `global` [`fa8503c`](https://github.com/es-shims/globalThis/commit/fa8503cf94afe84b3729dd5b0e9f73f481fb1fee)
- Initial commit [`99f1dc3`](https://github.com/es-shims/globalThis/commit/99f1dc328d0b4c52a550037de0139d5452ac01de)
- [Tests] up to `node` `v6.7`, `v5.12`, `v4.6`; improve test matrix [`712ec0e`](https://github.com/es-shims/globalThis/commit/712ec0e545d1603c4e23f4ff1acb066cc4a3c9ee)
- [Dev Deps] update `browserify`, `tape`, `jscs`, `nsp`, `eslint`, `@ljharb/eslint-config` [`73278bd`](https://github.com/es-shims/globalThis/commit/73278bd638d1e762eb7415350a738f5d345896f5)
- [Dev Deps] update `@es-shims/api`, `@ljharb/eslint-config`, `browserify`, `eslint`, `for-each`, `is`, `nsp`, `tape` [`75fa992`](https://github.com/es-shims/globalThis/commit/75fa9929be81afec43895c02e33d0b8a78f11d1f)
- [Dev Deps] update `browserify`, `is`, `tape`, `nsp`, `eslint` [`b223e86`](https://github.com/es-shims/globalThis/commit/b223e86d0868efb1f0c966370ff2f822516d6956)
- [Tests] fix linting; remove parallelshell [`271b329`](https://github.com/es-shims/globalThis/commit/271b329d174b94c08913060752a2e9f9116fe5b8)
- [Deps] update `function-bind`, `object-keys` [`002d0c5`](https://github.com/es-shims/globalThis/commit/002d0c5685a83f97e014a8a07134eb621794c649)
- Only apps should have lockfiles [`960f1d0`](https://github.com/es-shims/globalThis/commit/960f1d00598cbba5427849c863eb10b8de82fb1b)
- [Tests] on `node` `v10.8` [`37fad9d`](https://github.com/es-shims/globalThis/commit/37fad9db9860c654efe0a32ec187f21730d5fed8)
- [Dev Deps] update `eslint`, `@ljharb/eslint-config` [`df28dfe`](https://github.com/es-shims/globalThis/commit/df28dfe7f0daf3db95a536a6ce64062bd706185d)
- [New] add `auto` entry point [`86eb2ab`](https://github.com/es-shims/globalThis/commit/86eb2ab4c4dc2babff20ac436cf7fb7f8da7d2f2)
- [Dev Deps] update `eslint` [`1bdc1aa`](https://github.com/es-shims/globalThis/commit/1bdc1aacfb94dcdc7bb61688c7634c435012e35d)
- [Deps] update `object-keys` [`72cdbf5`](https://github.com/es-shims/globalThis/commit/72cdbf596b16103ee711d52b2b645b42efc08c51)
- Update most common usage to invoke the function upon being required [`5026296`](https://github.com/es-shims/globalThis/commit/502629660da2c21cfb0f8ca233e2b9d427c052fe)
