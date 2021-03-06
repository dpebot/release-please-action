# Changelog

## [2.0.0](https://www.github.com/GoogleCloudPlatform/release-please-action/compare/v1.6.3...v2.0.0) (2020-09-04)


### ⚠ BREAKING CHANGES

* moves to code-suggester for PR management (#57)

### Features

* moves to code-suggester for PR management ([#57](https://www.github.com/GoogleCloudPlatform/release-please-action/issues/57)) ([1875a0a](https://www.github.com/GoogleCloudPlatform/release-please-action/commit/1875a0accd4910cdeed87ee0d05c376f71b9d155))

### [1.6.3](https://www.github.com/GoogleCloudPlatform/release-please-action/compare/v1.6.2...v1.6.3) (2020-08-02)


### Bug Fixes

* path was sometimes empty string ([37d7741](https://www.github.com/GoogleCloudPlatform/release-please-action/commit/37d774119e97ee91ab924fc3e30902a38a64c6bb))

### [1.6.2](https://www.github.com/GoogleCloudPlatform/release-please-action/compare/v1.6.1...v1.6.2) (2020-08-02)


### Bug Fixes

* falsy path should be passed as undefined ([#54](https://www.github.com/GoogleCloudPlatform/release-please-action/issues/54)) ([21233d3](https://www.github.com/GoogleCloudPlatform/release-please-action/commit/21233d3c9f239105feab8f1df3e5fb013c1bd7f8))

### [1.6.1](https://www.github.com/GoogleCloudPlatform/release-please-action/compare/v1.6.0...v1.6.1) (2020-07-28)


### Bug Fixes

* add missing  path and  monorepo-tags options ([#52](https://www.github.com/GoogleCloudPlatform/release-please-action/issues/52)) ([41fbc62](https://www.github.com/GoogleCloudPlatform/release-please-action/commit/41fbc62bb12a4b0ff33a3ae5f401acc3d1bf3b7f))

## [1.6.0](https://www.github.com/GoogleCloudPlatform/release-please-action/compare/v1.5.0...v1.6.0) (2020-07-27)


### Features

* adds support for releases from alternate paths ([#50](https://www.github.com/GoogleCloudPlatform/release-please-action/issues/50)) ([6fc9b14](https://www.github.com/GoogleCloudPlatform/release-please-action/commit/6fc9b14e82521ecefd65c6b7f6b4f32561ce35f6))


### Bug Fixes

* run tests on release PRs ([#47](https://www.github.com/GoogleCloudPlatform/release-please-action/issues/47)) ([b4c1bd2](https://www.github.com/GoogleCloudPlatform/release-please-action/commit/b4c1bd25c7ff2d17dcdd9a91d018dc7058c654a8))

## [1.5.0](https://www.github.com/GoogleCloudPlatform/release-please-action/compare/v1.4.0...v1.5.0) (2020-07-23)


### Features

* **release-please:** auth gets; stop skipping all ci/cd ([#45](https://www.github.com/GoogleCloudPlatform/release-please-action/issues/45)) ([367f112](https://www.github.com/GoogleCloudPlatform/release-please-action/commit/367f112c21cbef9eef1ec197173f276b42b2fcbf))

## [1.4.0](https://www.github.com/GoogleCloudPlatform/release-please-action/compare/v1.3.2...v1.4.0) (2020-07-23)


### Features

* output tag name and upload url ([#43](https://www.github.com/GoogleCloudPlatform/release-please-action/issues/43)) ([90469b0](https://www.github.com/GoogleCloudPlatform/release-please-action/commit/90469b02b471d8f7cba6c353b4c1ec1bab5bcde4))

### [1.3.2](https://www.github.com/GoogleCloudPlatform/release-please-action/compare/v1.3.1...v1.3.2) (2020-06-17)


### Bug Fixes

* **build:** switch to GITHUB_TOKEN ([#38](https://www.github.com/GoogleCloudPlatform/release-please-action/issues/38)) ([188d363](https://www.github.com/GoogleCloudPlatform/release-please-action/commit/188d36320b0644bc436b701963d78be6386fe2c3))

### [1.3.1](https://www.github.com/GoogleCloudPlatform/release-please-action/compare/v1.3.0...v1.3.1) (2020-06-17)


### Bug Fixes

* **build:** update to match new default branch ([#36](https://www.github.com/GoogleCloudPlatform/release-please-action/issues/36)) ([1188197](https://www.github.com/GoogleCloudPlatform/release-please-action/commit/1188197913717dd90bc1d79e1139269f427411e9))

## [1.3.0](https://www.github.com/GoogleCloudPlatform/release-please-action/compare/v1.2.2...v1.3.0) (2020-06-17)


### Features

* **release-please:** configurable default branch; package-lock.json now updated ([#34](https://www.github.com/GoogleCloudPlatform/release-please-action/issues/34)) ([a4607bd](https://www.github.com/GoogleCloudPlatform/release-please-action/commit/a4607bde22b13d1ff7f153625f6e9c84ddf20a41))


### Bug Fixes

* **docs:** update docs to GoogleCloudPlatform ([#31](https://www.github.com/GoogleCloudPlatform/release-please-action/issues/31)) ([4f72a02](https://www.github.com/GoogleCloudPlatform/release-please-action/commit/4f72a02b61bc06a7607189ce5eea318ac382d242))

### [1.2.2](https://www.github.com/bcoe/release-please-action/compare/v1.2.1...v1.2.2) (2020-06-11)


### Bug Fixes

* **deps:** depend on release-please ^5.2.1 to support merge commits  ([#28](https://www.github.com/bcoe/release-please-action/issues/28)) ([5c2e7c4](https://www.github.com/bcoe/release-please-action/commit/5c2e7c41fc2a838bdd1c4319f18385e4784b020f))

### [1.2.1](https://www.github.com/bcoe/release-please-action/compare/v1.2.0...v1.2.1) (2020-05-21)


### Bug Fixes

* use the static build helper ([6872559](https://www.github.com/bcoe/release-please-action/commit/687255987d0e25878a9d56fd69de09c232bbcea3))

## [1.2.0](https://www.github.com/bcoe/release-please-action/compare/v1.1.0...v1.2.0) (2020-05-21)


### Features

* output whether or not a release was created ([#24](https://www.github.com/bcoe/release-please-action/issues/24)) ([b80ca61](https://www.github.com/bcoe/release-please-action/commit/b80ca61e2612c87bad38d85451c7f696a040bdc8))

## [1.1.0](https://www.github.com/bcoe/release-please-action/compare/v1.0.1...v1.1.0) (2020-05-20)


### Features

* Add `bump-minor-pre-major` option ([#9](https://www.github.com/bcoe/release-please-action/issues/9)) ([788c495](https://www.github.com/bcoe/release-please-action/commit/788c495e2607702ce5ab41e9e246161d07fe8854))

### [1.0.1](https://www.github.com/bcoe/release-please-action/compare/v1.0.0...v1.0.1) (2020-05-09)


### Bug Fixes

* pass token to create release ([3ad91fa](https://www.github.com/bcoe/release-please-action/commit/3ad91fa6cb8cf2c05464672da14cbea65555e5a2))

## 1.0.0 (2020-05-09)


### ⚠ BREAKING CHANGES

* initial implementation of logic for running release please

### Features

* handle creating releases ([#3](https://www.github.com/bcoe/release-please-action/issues/3)) ([e72afe0](https://www.github.com/bcoe/release-please-action/commit/e72afe059a2eae50d319b3a4cee2a31479886fe8))
* initial implementation of logic for running release please ([196390b](https://www.github.com/bcoe/release-please-action/commit/196390b8667a14c2ab16f53ba086c11afee28327))
