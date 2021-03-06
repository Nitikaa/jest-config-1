# Changelog

All notable changes to this project will be documented in this file. See [standard-version](https://github.com/conventional-changelog/standard-version) for commit guidelines.

### [4.0.1](https://github.com/moxystudio/jest-config/compare/v4.0.0...v4.0.1) (2020-03-23)


### Bug Fixes

* remove unused dependency ([59b7d11](https://github.com/moxystudio/jest-config/commit/59b7d119023234271e9deba8e25d4d7bb945696c))

## [4.0.0](https://github.com/moxystudio/jest-config/compare/v3.0.0...v4.0.0) (2020-03-23)


### ⚠ BREAKING CHANGES

* the base configuration no longer contains transforms nor mappings other than JavaScript files
* baseConfig and enhancers are now factories
* enhancers now validate if the test environment is correctly set
* withEnzyme now has mandatory target argument
* compose now accepts baseConfig as the first argument and enhancers are spread-ed after it

### Features

* add react-native enhancers ([#16](https://github.com/moxystudio/jest-config/issues/16)) ([df9d662](https://github.com/moxystudio/jest-config/commit/df9d662cae3c29aea0c548b82ab31c48c4ad8a4d))


### Bug Fixes

* fix testMatch pattern to not accept jsx ([#13](https://github.com/moxystudio/jest-config/issues/13)) ([55dc8b0](https://github.com/moxystudio/jest-config/commit/55dc8b0f80566fd8f5f7237229221e01d012bbbf))

## [3.0.0](https://github.com/moxystudio/jest-config/compare/v2.1.0...v3.0.0) (2020-03-20)


### ⚠ BREAKING CHANGES

* no longer detect .spec.js files (#12)

### Features

* no longer detect .spec.js files ([#12](https://github.com/moxystudio/jest-config/issues/12)) ([379d462](https://github.com/moxystudio/jest-config/commit/379d4629a757792a64f1b427b7f773b5125bfcf7))

## [2.1.0](https://github.com/moxystudio/jest-config/compare/v2.0.2...v2.1.0) (2020-03-14)


### Features

* add jestConfig to baseConfig ([#10](https://github.com/moxystudio/jest-config/issues/10)) ([b86a4ad](https://github.com/moxystudio/jest-config/commit/b86a4ad65531e473a3b07b6fe25d346781746c15))

### [2.0.2](https://github.com/moxystudio/jest-config/compare/v2.0.1...v2.0.2) (2020-03-10)

### [2.0.1](https://github.com/moxystudio/jest-config/compare/v2.0.0...v2.0.1) (2020-03-10)


### Bug Fixes

* remove peer dependency warning about react ([2aef3a0](https://github.com/moxystudio/jest-config/commit/2aef3a0876fb9a3a5c8abd5f2b2b108d6a53dbb5))

## [2.0.0](https://github.com/moxystudio/jest-config/compare/v1.4.1...v2.0.0) (2020-02-21)


### ⚠ BREAKING CHANGES

* withWeb addon no longer comes with RTL by default

### Features

* add support for enzyme ([#8](https://github.com/moxystudio/jest-config/issues/8)) ([ec260d2](https://github.com/moxystudio/jest-config/commit/ec260d2ba39afebaf8d5ba4d0086081500edbeb4))

### [1.4.1](https://github.com/moxystudio/jest-config/compare/v1.4.0...v1.4.1) (2020-01-23)


### Bug Fixes

* fix previous commit ([c792db4](https://github.com/moxystudio/jest-config/commit/c792db4c66ca3073722a9a5573a9f5b8cfa36e41))

## [1.4.0](https://github.com/moxystudio/jest-config/compare/v1.3.0...v1.4.0) (2020-01-23)


### Features

* ignore docusaurus in the web addon ([008d17f](https://github.com/moxystudio/jest-config/commit/008d17fbdda27dd2d1aa64a2e81024a217ffee0a))

## [1.3.0](https://github.com/moxystudio/jest-config/compare/v1.2.0...v1.3.0) (2020-01-22)


### Features

* support jest@15 ([312e86a](https://github.com/moxystudio/jest-config/commit/312e86a248939cbcabc238ddd2770ff1ebcd1a89))

## [1.2.0](https://github.com/moxystudio/jest-config/compare/v1.1.1...v1.2.0) (2019-12-17)


### Features

* add api to collect coverage from in the web addon ([923150f](https://github.com/moxystudio/jest-config/commit/923150f2395c16bc430886ea23b56c1751b238e6))

### [1.1.1](https://github.com/moxystudio/jest-config/compare/v1.1.0...v1.1.1) (2019-11-21)


### Bug Fixes

* transformers not generating interop code ([#5](https://github.com/moxystudio/jest-config/issues/5)) ([7047b45](https://github.com/moxystudio/jest-config/commit/7047b45847d2a3dd85b3561dcd2ab9070c58e2a3))

## [1.1.0](https://github.com/moxystudio/jest-config/compare/v1.0.2...v1.1.0) (2019-11-07)


### Features

* implement rtl addon ([#3](https://github.com/moxystudio/jest-config/issues/3)) ([3d73965](https://github.com/moxystudio/jest-config/commit/3d739657ec957d5c3e025474aadd70a86ad4d2ee))


### Bug Fixes

* add missing babel-jest dependency ([db1c38e](https://github.com/moxystudio/jest-config/commit/db1c38efb7ae2ec5297182f02b684e29d37dc690))

### [1.0.2](https://github.com/moxystudio/jest-config/compare/v1.0.1...v1.0.2) (2019-11-05)


### Bug Fixes

* add repo to package.json ([7e0d554](https://github.com/moxystudio/jest-config/commit/7e0d5543afd7b24ad3770e5be99896074eef28c8))

### [1.0.1](https://github.com/moxystudio/jest-config/compare/v1.0.0...v1.0.1) (2019-11-05)

## 1.0.0 (2019-11-05)


### Features

* initial implementation ([b07a971](https://github.com/moxystudio/jest-config/commit/b07a97139483872b5267eab2d7bc3363db9f7157))
