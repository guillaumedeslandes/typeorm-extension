# [3.0.0-alpha.9](https://github.com/tada5hi/typeorm-extension/compare/v3.0.0-alpha.8...v3.0.0-alpha.9) (2023-07-22)


### Bug Fixes

* logging of seed file name on creation ([8bb0ec5](https://github.com/tada5hi/typeorm-extension/commit/8bb0ec55eb838ed595fed4b8a67ea2651b5da8e1))
* resolve seeder/factory file patterns & paths relative to root directory ([622aec9](https://github.com/tada5hi/typeorm-extension/commit/622aec9b77de999c8b22b26a1336bbf47f7076c0))


### Features

* explicit seed execution, comparison by file-name/path ([61de8dd](https://github.com/tada5hi/typeorm-extension/commit/61de8dd4e6a27782191f22a65e1881747f95f353))
* refactor and optimized file path modification ([5bdfd0a](https://github.com/tada5hi/typeorm-extension/commit/5bdfd0a09e216662947f733f4e432ccfaf7047f7))


### BREAKING CHANGES

* public api changed

# [3.0.0-alpha.8](https://github.com/tada5hi/typeorm-extension/compare/v3.0.0-alpha.7...v3.0.0-alpha.8) (2023-07-21)


### Bug Fixes

* align cli options with README ([4f3432c](https://github.com/tada5hi/typeorm-extension/commit/4f3432c2d18197c74de4579e83ac02ba3372e7da))
* **deps:** bump locter from 1.1.2 to 1.1.3 ([#633](https://github.com/tada5hi/typeorm-extension/issues/633)) ([90ce900](https://github.com/tada5hi/typeorm-extension/commit/90ce9006896901c05a140785d0e56b290e24a965))
* rename seeder property oneTimeOnly to track + global seedTracking option ([b8c4b35](https://github.com/tada5hi/typeorm-extension/commit/b8c4b355b4872479e716d24d9eed56527e2d3cb2))


### Features

* implemented seed:craete cli command + adjusted seed run command ([7cc56bc](https://github.com/tada5hi/typeorm-extension/commit/7cc56bcc30179497f451b5069fe3690696d511de))
* refactored cli options + enhanced commands ([637250b](https://github.com/tada5hi/typeorm-extension/commit/637250be1e760fb10cd791ebfa30cc5dcf12d7d6))

# [3.0.0-alpha.7](https://github.com/tada5hi/typeorm-extension/compare/v3.0.0-alpha.6...v3.0.0-alpha.7) (2023-07-20)


### Bug Fixes

* circular dependencies ([23b8d6c](https://github.com/tada5hi/typeorm-extension/commit/23b8d6c2c08ecb00358aae5276ff93ee9911a063))
* cleanup file path adjustment ([01332c5](https://github.com/tada5hi/typeorm-extension/commit/01332c5f3b645c194d71b11639781e8b8d45c650))

# [3.0.0-alpha.6](https://github.com/tada5hi/typeorm-extension/compare/v3.0.0-alpha.5...v3.0.0-alpha.6) (2023-07-16)


### Bug Fixes

* adjust runSeeder(s) method to use seeder executor ([3f55d49](https://github.com/tada5hi/typeorm-extension/commit/3f55d4919d23b75d0f2cb0d62958feafd25db597))
* **deps:** bump rapiq from 0.8.1 to 0.9.0 ([#618](https://github.com/tada5hi/typeorm-extension/issues/618)) ([e2d9d1b](https://github.com/tada5hi/typeorm-extension/commit/e2d9d1bbbc7b018c735039ca2b11ead48acce570))
* only track one time seeder ([8edf6cf](https://github.com/tada5hi/typeorm-extension/commit/8edf6cf082ea0da8deb3ebd0b7e7dd4cf18e9151))
* seeds without timestamp should be considered older ([f511978](https://github.com/tada5hi/typeorm-extension/commit/f511978cf23e5d02eb949710471d282b48d79bab))


### Features

* allow setting (faker) locale for seeder factories ([5387d44](https://github.com/tada5hi/typeorm-extension/commit/5387d4422efe0768e81312091f4f162d2fc6b734))
* option to execute seeds only once ([5f6d98f](https://github.com/tada5hi/typeorm-extension/commit/5f6d98f0e2b6c8935a1b5d1177b6563950009863))

# [3.0.0-alpha.5](https://github.com/tada5hi/typeorm-extension/compare/v3.0.0-alpha.4...v3.0.0-alpha.5) (2023-05-29)


### Bug Fixes

* adjust build action to cache bin and dist dir ([9afa905](https://github.com/tada5hi/typeorm-extension/commit/9afa9053b58de5736299f86aafd5054f7baff5ce))

# [3.0.0-alpha.4](https://github.com/tada5hi/typeorm-extension/compare/v3.0.0-alpha.3...v3.0.0-alpha.4) (2023-05-29)


### Bug Fixes

* preserve bin/cli.{mjs,cjs} for publishing ([7b175e9](https://github.com/tada5hi/typeorm-extension/commit/7b175e92bd8db5b71d07d279d2fbc76dc0c4a03e))

# [3.0.0-alpha.3](https://github.com/tada5hi/typeorm-extension/compare/v3.0.0-alpha.2...v3.0.0-alpha.3) (2023-05-29)


### Bug Fixes

* keepÃ bin directory + updated .gitignore ([58aebad](https://github.com/tada5hi/typeorm-extension/commit/58aebad44982969eb14c905a601537204741baa5))

# [3.0.0-alpha.2](https://github.com/tada5hi/typeorm-extension/compare/v3.0.0-alpha.1...v3.0.0-alpha.2) (2023-05-29)


### Bug Fixes

* include bin directory in package-json file list ([327ce47](https://github.com/tada5hi/typeorm-extension/commit/327ce47416df15f22406a5f69250f80feecf45db))

# [3.0.0-alpha.1](https://github.com/tada5hi/typeorm-extension/compare/v2.8.1...v3.0.0-alpha.1) (2023-05-29)


### Bug Fixes

* circular dependencies between seder and data-source-options ([c5d1d09](https://github.com/tada5hi/typeorm-extension/commit/c5d1d09ec2a0903d1257599b61ba609b76921171))
* yargs import for esm cli entry-point ([3d46dff](https://github.com/tada5hi/typeorm-extension/commit/3d46dffc5a4dbfa95ecb77b84149352299519cfa))


### Features

* generate cli entry point for cjs/esm ([0cc73b6](https://github.com/tada5hi/typeorm-extension/commit/0cc73b608f9782da25db89e1f6786e964a7cbcd3))
* remove legacy data-source options building ([6cb4d77](https://github.com/tada5hi/typeorm-extension/commit/6cb4d775e1684ec395b03be6ab96e46f73e165f6))
* use rollup and swc to create bundles for cjs & esm ([46016e8](https://github.com/tada5hi/typeorm-extension/commit/46016e83afb9bfb7731f113aea298b9d16fad9fe))


### BREAKING CHANGES

* ormconfig no longer supported
* CLI path changed

## [2.8.1](https://github.com/tada5hi/typeorm-extension/compare/v2.8.0...v2.8.1) (2023-05-29)


### Bug Fixes

* **deps:** bump @faker-js/faker from 7.6.0 to 8.0.2 ([#589](https://github.com/tada5hi/typeorm-extension/issues/589)) ([1cc418b](https://github.com/tada5hi/typeorm-extension/commit/1cc418b6f403c11580b93faa96e098f939a16822))
* **deps:** bump rapiq from 0.8.0 to 0.8.1 ([#590](https://github.com/tada5hi/typeorm-extension/issues/590)) ([ae669c8](https://github.com/tada5hi/typeorm-extension/commit/ae669c8b4c9b5666d94b350a49772895e1e41ae8))
* **deps:** bump smob from 1.0.0 to 1.4.0 ([#588](https://github.com/tada5hi/typeorm-extension/issues/588)) ([7b0d094](https://github.com/tada5hi/typeorm-extension/commit/7b0d094f8c6da754397ab7367d4836242b43dda6))

## v2.8.0

[compare changes](https://github.com/tada5hi/typeorm-extension/compare/v2.7.0...v2.8.0)


### 🚀 Enhancements

  - Sort by filename when using seed pattern ([#546](https://github.com/tada5hi/typeorm-extension/pull/546))

### 🩹 Fixes

  - **deps:** Bump yargs from 17.7.1 to 17.7.2 ([#554](https://github.com/tada5hi/typeorm-extension/pull/554))

### 📦 Build

  - **deps-dev:** Bump typeorm from 0.3.12 to 0.3.13 ([#534](https://github.com/tada5hi/typeorm-extension/pull/534))
  - **deps-dev:** Bump @tada5hi/commitlint-config from 1.0.0 to 1.0.1 ([#530](https://github.com/tada5hi/typeorm-extension/pull/530))
  - **deps:** Bump codecov/codecov-action from 3.1.1 to 3.1.3 ([#547](https://github.com/tada5hi/typeorm-extension/pull/547))
  - **deps-dev:** Bump better-sqlite3 from 8.2.0 to 8.3.0 ([#535](https://github.com/tada5hi/typeorm-extension/pull/535))
  - **deps-dev:** Bump eslint from 8.36.0 to 8.38.0 ([#537](https://github.com/tada5hi/typeorm-extension/pull/537))
  - **deps-dev:** Bump vitepress from 1.0.0-alpha.64 to 1.0.0-alpha.73 ([#545](https://github.com/tada5hi/typeorm-extension/pull/545))
  - **deps-dev:** Bump changelogen from 0.5.2 to 0.5.3 ([#549](https://github.com/tada5hi/typeorm-extension/pull/549))
  - **deps-dev:** Bump eslint from 8.38.0 to 8.39.0 ([#550](https://github.com/tada5hi/typeorm-extension/pull/550))
  - **deps-dev:** Bump @types/node from 18.15.11 to 18.16.0 ([#548](https://github.com/tada5hi/typeorm-extension/pull/548))
  - **deps-dev:** Bump vitepress from 1.0.0-alpha.73 to 1.0.0-alpha.74 ([#551](https://github.com/tada5hi/typeorm-extension/pull/551))
  - **deps-dev:** Bump @types/node from 18.16.0 to 18.16.2 ([#553](https://github.com/tada5hi/typeorm-extension/pull/553))
  - **deps-dev:** Bump @types/node from 18.16.2 to 18.16.3 ([#556](https://github.com/tada5hi/typeorm-extension/pull/556))
  - **deps-dev:** Bump typeorm to v0.3.15 ([33c34b1](https://github.com/tada5hi/typeorm-extension/commit/33c34b1))
  - **deps-dev:** Remove semantic release dependency ([5b9047e](https://github.com/tada5hi/typeorm-extension/commit/5b9047e))

### ✅ Tests

  - Fix file-path sort test for windows os ([30971e3](https://github.com/tada5hi/typeorm-extension/commit/30971e3))

### ❤️  Contributors

- Tada5hi <peter.placzek1996@gmail.com>
- LuisK Ruiz

## v2.7.0

[compare changes](https://github.com/tada5hi/typeorm-extension/compare/v2.6.2...v2.7.0)


### 🚀 Enhancements

  - Prepare & extend env reading for env data-source otions reading ([c3a401c](https://github.com/tada5hi/typeorm-extension/commit/c3a401c))
  - Experimental read env data-source options and merge them with file based options ([e5c4e1b](https://github.com/tada5hi/typeorm-extension/commit/e5c4e1b))
  - Add extra utility to merge data-source options ([df5637c](https://github.com/tada5hi/typeorm-extension/commit/df5637c))

### 🩹 Fixes

  - **deps:** Bump locter from 1.0.10 to 1.1.0 ([#523](https://github.com/tada5hi/typeorm-extension/pull/523))
  - Export env sub module ([fc9090d](https://github.com/tada5hi/typeorm-extension/commit/fc9090d))

### 📦 Build

  - Replaced semantic-release with changelogen for release management ([66e3997](https://github.com/tada5hi/typeorm-extension/commit/66e3997))
  - **deps-dev:** Bump vitepress from 1.0.0-alpha.61 to 1.0.0-alpha.64 ([#529](https://github.com/tada5hi/typeorm-extension/pull/529))
  - **deps-dev:** Bump @tada5hi/eslint-config-typescript ([#526](https://github.com/tada5hi/typeorm-extension/pull/526))
  - **deps-dev:** Bump @types/yargs from 17.0.22 to 17.0.24 ([#527](https://github.com/tada5hi/typeorm-extension/pull/527))
  - **deps-dev:** Bump @types/node from 18.15.7 to 18.15.11 ([#528](https://github.com/tada5hi/typeorm-extension/pull/528))

### ❤️  Contributors

- Tada5hi <peter.placzek1996@gmail.com>

## [2.6.2](https://github.com/tada5hi/typeorm-extension/compare/v2.6.1...v2.6.2) (2023-03-25)


### Bug Fixes

* typo in mongo-db connection creation ([f828f26](https://github.com/tada5hi/typeorm-extension/commit/f828f26634616b7110c3ba075262ad18be82a873))

## [2.6.1](https://github.com/tada5hi/typeorm-extension/compare/v2.6.0...v2.6.1) (2023-03-25)


### Bug Fixes

* **deps:** bump locter from 1.0.9 to 1.0.10 ([#512](https://github.com/tada5hi/typeorm-extension/issues/512)) ([a4ef42d](https://github.com/tada5hi/typeorm-extension/commit/a4ef42d5f6651f2c5a3b831af769cc47b69cf961))

# [2.6.0](https://github.com/tada5hi/typeorm-extension/compare/v2.5.4...v2.6.0) (2023-03-25)


### Features

* add generate migraiton helper utility ([c9e3736](https://github.com/tada5hi/typeorm-extension/commit/c9e37362eb9a75b95525c68e5dbf941d8641b8af))
* add mongodb driver support ([5ef4d74](https://github.com/tada5hi/typeorm-extension/commit/5ef4d74e4e35db01a20984f4f36ed4d7f0e387ca))
* better env variable(s) handling ([fea6bf7](https://github.com/tada5hi/typeorm-extension/commit/fea6bf7c015f20a419f3d2354c38c701b10e1cf4))

## [2.5.4](https://github.com/tada5hi/typeorm-extension/compare/v2.5.3...v2.5.4) (2023-03-13)


### Bug Fixes

* use of default export for data-source search ([66eddf0](https://github.com/tada5hi/typeorm-extension/commit/66eddf036a2b2f2ea1b100d2d08de994c37dd6ab))

## [2.5.3](https://github.com/tada5hi/typeorm-extension/compare/v2.5.2...v2.5.3) (2023-03-13)


### Bug Fixes

* **deps:** bump locter to v1.0.9 ([ce0abc0](https://github.com/tada5hi/typeorm-extension/commit/ce0abc077a21b779cc889a18ddd26244c2fd44f2))
* **deps:** bump yargs from 17.6.2 to 17.7.1 ([#492](https://github.com/tada5hi/typeorm-extension/issues/492)) ([0850571](https://github.com/tada5hi/typeorm-extension/commit/085057174260f09a2b72ef3d7da2005bca31f51d))
* safer strategy for replacing windows separator ([8839b57](https://github.com/tada5hi/typeorm-extension/commit/8839b57319efd5966e67b6d4986bf582ddb99ed0))

## [2.5.2](https://github.com/tada5hi/typeorm-extension/compare/v2.5.1...v2.5.2) (2023-02-16)


### Bug Fixes

* more secure path extension replacement ([51f2056](https://github.com/tada5hi/typeorm-extension/commit/51f2056c899ac3023cd15893b9b8642f0ea50c74))

## [2.5.1](https://github.com/tada5hi/typeorm-extension/compare/v2.5.0...v2.5.1) (2023-02-16)


### Bug Fixes

* enhance path replacement for ts -> js ([dd141ab](https://github.com/tada5hi/typeorm-extension/commit/dd141ab216940a3564d947866de2e3968fe2fa4a))
* minor enhancements  for path replacing + enhanced find operation ([17160ea](https://github.com/tada5hi/typeorm-extension/commit/17160ea532d871f60e53355c95e3ddad253a65fe))

# [2.5.0](https://github.com/tada5hi/typeorm-extension/compare/v2.4.2...v2.5.0) (2023-02-15)


### Bug Fixes

* **deps:** bump rapiq, better-sqlite(dev) & typeorm(dev) ([acff4f7](https://github.com/tada5hi/typeorm-extension/commit/acff4f74875bf565ceedb4f34c8b304d8646331c))


### Features

* lazy transpiling of seeder-/data-source-files ([5d092ad](https://github.com/tada5hi/typeorm-extension/commit/5d092ad9ed8e83f2c53a82c67b7b9e907a9a3e0a))
* stricter typescript rules ([64a2868](https://github.com/tada5hi/typeorm-extension/commit/64a286861da49f6d6893c8c19c6ef18f7a02916d))

## [2.4.2](https://github.com/tada5hi/typeorm-extension/compare/v2.4.1...v2.4.2) (2023-01-17)


### Bug Fixes

* **deps:** bump locter from 0.6.1 to 0.7.0 ([bb0d2fa](https://github.com/tada5hi/typeorm-extension/commit/bb0d2fac3a7f6de19fde323f0907b10716741c53))
* **deps:** bump rapiq from 0.6.2 to 0.6.3 ([#438](https://github.com/tada5hi/typeorm-extension/issues/438)) ([d2d4919](https://github.com/tada5hi/typeorm-extension/commit/d2d49195bc16e5b79c133d8740b6e08f94e91138))
* generic type for seeder meta ([f82c655](https://github.com/tada5hi/typeorm-extension/commit/f82c65505fb9e8ee48a81e1d55c9504795116274))

## [2.4.1](https://github.com/tada5hi/typeorm-extension/compare/v2.4.0...v2.4.1) (2022-12-28)


### Bug Fixes

* **deps:** bump locter from 0.6.0 to 0.6.1 ([79f44bf](https://github.com/tada5hi/typeorm-extension/commit/79f44bf46c6013285d0c0c45b281d13425f7047f))
* **deps:** bump rapiq from 0.6.1 to 0.6.2 ([1c941a1](https://github.com/tada5hi/typeorm-extension/commit/1c941a19cf4b11cf449d71d12bb2ebba35ae305b))

# [2.4.0](https://github.com/tada5hi/typeorm-extension/compare/v2.3.1...v2.4.0) (2022-12-16)


### Features

* run migrations with specified transaction mode ([3e7f9a5](https://github.com/tada5hi/typeorm-extension/commit/3e7f9a58424a9ee57d3ba50c2b8beb25ebd045c4))

## [2.3.1](https://github.com/tada5hi/typeorm-extension/compare/v2.3.0...v2.3.1) (2022-12-09)


### Bug Fixes

* **deps:** bump locter from 0.5.1 to 0.6.0 ([8f12f18](https://github.com/tada5hi/typeorm-extension/commit/8f12f1890f6b1e723d7e66379e05caabead37540))
* **deps:** bump rapiq from 0.6.0 to 0.6.1 ([f15a95e](https://github.com/tada5hi/typeorm-extension/commit/f15a95efa17165cd8b6d78f94fc2ff4cb7966881))
* pending migrations check ([532cd2f](https://github.com/tada5hi/typeorm-extension/commit/532cd2f5cd54e47842fa0b1fb88d7f9bd5ac3913))

# [2.3.0](https://github.com/tada5hi/typeorm-extension/compare/v2.2.13...v2.3.0) (2022-11-27)


### Features

* add check-database utility fn ([706e044](https://github.com/tada5hi/typeorm-extension/commit/706e044571b751bdf2c31dc9bace9deec6b4689a))
* allow null value in query filter list ([949124c](https://github.com/tada5hi/typeorm-extension/commit/949124cbfaabe5b81db56883e2106b71b7be0a52))

## [2.2.13](https://github.com/tada5hi/typeorm-extension/compare/v2.2.12...v2.2.13) (2022-11-16)


### Bug Fixes

* typo in apply-query check ([df79051](https://github.com/tada5hi/typeorm-extension/commit/df79051ad6485948d9683916c94f4640fe39e7c4))

## [2.2.12](https://github.com/tada5hi/typeorm-extension/compare/v2.2.11...v2.2.12) (2022-11-06)


### Bug Fixes

* **deps:** bump yargs from 17.6.0 to 17.6.2 ([b76eeac](https://github.com/tada5hi/typeorm-extension/commit/b76eeacbc2907352870f021032c71305bbf6c01c))

## [2.2.11](https://github.com/tada5hi/typeorm-extension/compare/v2.2.10...v2.2.11) (2022-10-28)


### Bug Fixes

* only apply query parameter if options are defined ([49b1d0a](https://github.com/tada5hi/typeorm-extension/commit/49b1d0afb9e290ef86f2a8209f234e514ffebbd5))

## [2.2.10](https://github.com/tada5hi/typeorm-extension/compare/v2.2.9...v2.2.10) (2022-10-27)


### Bug Fixes

* **deps:** bump rapiq from 0.3.1 to 0.3.2 ([dd0fc55](https://github.com/tada5hi/typeorm-extension/commit/dd0fc554f47c815f47fd00ae6d3c64550b26d502))

## [2.2.9](https://github.com/tada5hi/typeorm-extension/compare/v2.2.8...v2.2.9) (2022-10-26)


### Bug Fixes

* **deps:** bump rapiq from 0.0.6 to 0.3.1 ([b78dfe8](https://github.com/tada5hi/typeorm-extension/commit/b78dfe8941cc3e33399ef04a7ce6d76d7b94a96a))

## [2.2.8](https://github.com/tada5hi/typeorm-extension/compare/v2.2.7...v2.2.8) (2022-10-21)


### Bug Fixes

* param order in apply-query-parse-output ([4fff8cd](https://github.com/tada5hi/typeorm-extension/commit/4fff8cdb756272aa3bf2765499595d213ec7f71c))

## [2.2.7](https://github.com/tada5hi/typeorm-extension/compare/v2.2.6...v2.2.7) (2022-10-21)


### Bug Fixes

* add apply-query function + cleaned up query sub-module ([247fa0a](https://github.com/tada5hi/typeorm-extension/commit/247fa0ae5a4a075818239501e4d96f4bcf9eb401))

## [2.2.6](https://github.com/tada5hi/typeorm-extension/compare/v2.2.5...v2.2.6) (2022-10-20)


### Bug Fixes

* apply-sort should rely on apply-query-sort ([dc7f713](https://github.com/tada5hi/typeorm-extension/commit/dc7f713899032eafbda19de9dfeba936c020a1d3))

## [2.2.5](https://github.com/tada5hi/typeorm-extension/compare/v2.2.4...v2.2.5) (2022-10-20)


### Bug Fixes

* updated rapiq to v0.2.6 ([2220d4d](https://github.com/tada5hi/typeorm-extension/commit/2220d4d6c95fe0eefcba3bcec71314889f36f28c))

## [2.2.4](https://github.com/tada5hi/typeorm-extension/compare/v2.2.3...v2.2.4) (2022-10-20)


### Bug Fixes

* use default-path as alternative default-alias ([13594d4](https://github.com/tada5hi/typeorm-extension/commit/13594d4279fa84462607fe8badfaf6c4564100ae))

## [2.2.3](https://github.com/tada5hi/typeorm-extension/compare/v2.2.2...v2.2.3) (2022-10-20)


### Bug Fixes

* updated rapiq to v0.2.5 & updated docs ([09226cb](https://github.com/tada5hi/typeorm-extension/commit/09226cb74001b4e4b5c92b44541d932780f82a5d))

## [2.2.2](https://github.com/tada5hi/typeorm-extension/compare/v2.2.1...v2.2.2) (2022-10-19)


### Bug Fixes

* updated rapiq to v0.2.4 ([0b35d43](https://github.com/tada5hi/typeorm-extension/commit/0b35d43354f72bc7bb818836c74024aae9c89172))

## [2.2.1](https://github.com/tada5hi/typeorm-extension/compare/v2.2.0...v2.2.1) (2022-10-19)


### Bug Fixes

* export parse* methods + updated docs & README.md ([3251135](https://github.com/tada5hi/typeorm-extension/commit/32511352eb62427bc7553424d0467ada29dcbdc4))

# [2.2.0](https://github.com/tada5hi/typeorm-extension/compare/v2.1.15...v2.2.0) (2022-10-19)


### Features

* strongly typed options for query parse functions ([206c653](https://github.com/tada5hi/typeorm-extension/commit/206c6535a69ca50a5c8c4bdb0849b30e7d151eb9))

## [2.1.15](https://github.com/tada5hi/typeorm-extension/compare/v2.1.14...v2.1.15) (2022-10-13)


### Bug Fixes

* **deps:** bump @faker-js/faker from 7.5.0 to 7.6.0 ([9730d27](https://github.com/tada5hi/typeorm-extension/commit/9730d27aca3b4a2ffcf11cff6296ca0549999b72))

## [2.1.14](https://github.com/tada5hi/typeorm-extension/compare/v2.1.13...v2.1.14) (2022-10-11)


### Bug Fixes

* file import ([39825b3](https://github.com/tada5hi/typeorm-extension/commit/39825b3a07ab5dc6845e97cb6e27622d154dfad0))

## [2.1.13](https://github.com/tada5hi/typeorm-extension/compare/v2.1.12...v2.1.13) (2022-10-10)


### Bug Fixes

* **deps:** bump rapiq from 0.0.4 to 0.0.6 ([591848e](https://github.com/tada5hi/typeorm-extension/commit/591848e33d3ec7195cae7a719bf7ef47199f80fe))

## [2.1.12](https://github.com/tada5hi/typeorm-extension/compare/v2.1.11...v2.1.12) (2022-10-04)


### Bug Fixes

* add missing save argument for seeder-factory make method ([3f5f32b](https://github.com/tada5hi/typeorm-extension/commit/3f5f32b1e52dfdcf238800c2d9afb9b63a7d00e9))

## [2.1.11](https://github.com/tada5hi/typeorm-extension/compare/v2.1.10...v2.1.11) (2022-10-03)


### Bug Fixes

* set seeder to synchronous execution by default ([955f2ef](https://github.com/tada5hi/typeorm-extension/commit/955f2ef5dca19b806360315357ea4e043aa634a7))
