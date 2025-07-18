# Changelog

## [2.1.3](https://github.com/rkoshy/openapi-generator-go/compare/v2.1.2...v2.1.3) (2024-09-10)


### Miscellaneous Chores

* release 2.1.3 ([00cae34](https://github.com/rkoshy/openapi-generator-go/commit/00cae345069915e43502eb39109440adfe361082))

## [2.1.2](https://github.com/rkoshy/openapi-generator-go/compare/v2.1.1...v2.1.2) (2024-09-06)


### Bug Fixes

* filter missing schema when request bodies are defined ([aadda1a](https://github.com/rkoshy/openapi-generator-go/commit/aadda1a94a190075404223ead615b1aa57980e69))

## [2.1.1](https://github.com/rkoshy/openapi-generator-go/compare/v2.1.0...v2.1.1) (2024-02-16)


### Bug Fixes

* ozzo validation ([#134](https://github.com/rkoshy/openapi-generator-go/issues/134)) ([d48b64b](https://github.com/rkoshy/openapi-generator-go/commit/d48b64b302b17440651847ec90c3d1df81f6ad49))

## [2.1.0](https://github.com/rkoshy/openapi-generator-go/compare/v2.0.4...v2.1.0) (2023-11-25)

### Features

* upgrade to chi v5 [#112](https://github.com/rkoshy/openapi-generator-go/pull/112) ([5821062](https://github.com/rkoshy/openapi-generator-go/commit/5821062579767c17b569693e254b8bbf6b4b1e2e))
* add validation to Values and ensure nested validation is applied correctly, resolves [#111](https://github.com/rkoshy/openapi-generator-go/issues/111) ([ae80075](https://github.com/rkoshy/openapi-generator-go/commit/5821062579767c17b569693e254b8bbf6b4b1e2e))

### Miscellaneous Chores

* release 2.1.0 ([644bb3b](https://github.com/rkoshy/openapi-generator-go/commit/644bb3b8fd2128f22ccec8c1fb510606ed3a1064))

### [2.0.4](https://www.github.com/rkoshy/openapi-generator-go/compare/v2.0.3...v2.0.4) (2023-09-04)


### Miscellaneous Chores

* release 2.0.4 ([86304fe](https://www.github.com/rkoshy/openapi-generator-go/commit/86304fe6635243c035497f2ff81cf33a7890cc0a))

### [2.0.3](https://www.github.com/rkoshy/openapi-generator-go/compare/v2.0.2...v2.0.3) (2023-06-19)


### Bug Fixes

* + and - as a first character in names usually has a special meaning ([42fc660](https://www.github.com/rkoshy/openapi-generator-go/commit/42fc66080ba0e2a1ca3b4eedfdbb990bc4c8e778))
* generated multiline comments need proper formatting ([7e37ab8](https://www.github.com/rkoshy/openapi-generator-go/commit/7e37ab85658181415026538cbd45374e6a6aade7))
* Not all schema references are properly formatted GoTypes ([bb07fee](https://www.github.com/rkoshy/openapi-generator-go/commit/bb07feed0f5e20cfe45243b992609d65ef35bab9))

### [2.0.2](https://www.github.com/rkoshy/openapi-generator-go/compare/v2.0.1...v2.0.2) (2023-05-12)


### Bug Fixes

* support numberic enum types ([#98](https://www.github.com/rkoshy/openapi-generator-go/issues/98)) ([db0b095](https://www.github.com/rkoshy/openapi-generator-go/commit/db0b09555467ad5dd9267f15b9bc00ff474b170b))

### [2.0.1](https://www.github.com/rkoshy/openapi-generator-go/compare/v2.0.0...v2.0.1) (2023-04-08)


### Bug Fixes

* ensure nestd allOfs are correctly resolved ([#95](https://www.github.com/rkoshy/openapi-generator-go/issues/95)) ([d6605c6](https://www.github.com/rkoshy/openapi-generator-go/commit/d6605c6a59c72979cd1c850e444610fcb4f5c8f2))

## [2.0.0](https://www.github.com/rkoshy/openapi-generator-go/compare/v0.19.0...v2.0.0) (2023-03-10)


### Miscellaneous Chores

* bump go module to v2 ([#92](https://www.github.com/rkoshy/openapi-generator-go/issues/92)) ([7bbf28f](https://www.github.com/rkoshy/openapi-generator-go/commit/7bbf28fc24d28c3674ea2255631464e80329735e))

## [0.19.0](https://www.github.com/rkoshy/openapi-generator-go/compare/v0.18.0...v0.19.0) (2023-01-17)


### Features

* add mapstructure tags ([#88](https://www.github.com/rkoshy/openapi-generator-go/issues/88)) ([481788c](https://www.github.com/rkoshy/openapi-generator-go/commit/481788c3e6412dd710b66858bd3612bdeea1dfe9))

## [0.18.0](https://www.github.com/rkoshy/openapi-generator-go/compare/v0.17.0...v0.18.0) (2022-12-06)


### Features

* combined properties, additional properties in named objects ([#85](https://www.github.com/rkoshy/openapi-generator-go/issues/85)) ([27c3f61](https://www.github.com/rkoshy/openapi-generator-go/commit/27c3f61a449e0d720f72959e45fc8687fb8f4fb4))


### Bug Fixes

* move main to the project root ([#81](https://www.github.com/rkoshy/openapi-generator-go/issues/81)) ([0d60d72](https://www.github.com/rkoshy/openapi-generator-go/commit/0d60d72ef9e3105413fba06669773b9858bd9025))
* panic on oneof validation ([#86](https://www.github.com/rkoshy/openapi-generator-go/issues/86)) ([317299d](https://www.github.com/rkoshy/openapi-generator-go/commit/317299d3b2d7adb387c052224070fbe17be0ad84))
* Update the test comments ([#84](https://www.github.com/rkoshy/openapi-generator-go/issues/84)) ([3ef0880](https://www.github.com/rkoshy/openapi-generator-go/commit/3ef08804f9b356eaec81b2168d160ea50c3e1d7b))

## [0.17.0](https://www.github.com/rkoshy/openapi-generator-go/compare/v0.16.0...v0.17.0) (2022-04-19)


### Features

* add HTTP HEAD operation ([#76](https://www.github.com/rkoshy/openapi-generator-go/issues/76)) ([4d4b429](https://www.github.com/rkoshy/openapi-generator-go/commit/4d4b429a8ca1682c024c91252b0a06231610da57))

## [0.16.0](https://www.github.com/rkoshy/openapi-generator-go/compare/v0.15.0...v0.16.0) (2022-02-14)


### Features

* upgrade kin-openapi to 0.89.0 to support oidc security schemas ([#74](https://www.github.com/rkoshy/openapi-generator-go/issues/74)) ([9d119c2](https://www.github.com/rkoshy/openapi-generator-go/commit/9d119c2ebb1d8deefa2932d37f0bab314e77f5ef))

## [0.15.0](https://www.github.com/rkoshy/openapi-generator-go/compare/v0.14.2...v0.15.0) (2022-02-11)


### Features

* create prebuilt binaries for releases ([#72](https://www.github.com/rkoshy/openapi-generator-go/issues/72)) ([351c158](https://www.github.com/rkoshy/openapi-generator-go/commit/351c15816630d09b966511939c69b050303b52fe))

### [0.14.2](https://www.github.com/rkoshy/openapi-generator-go/compare/v0.14.1...v0.14.2) (2021-10-18)


### Bug Fixes

* sort model names prior to generation to improve stability ([#69](https://www.github.com/rkoshy/openapi-generator-go/issues/69)) ([f2ba6a9](https://www.github.com/rkoshy/openapi-generator-go/commit/f2ba6a93a56e213ea1354805972ad1231bee5708))

### [0.14.1](https://www.github.com/rkoshy/openapi-generator-go/compare/v0.14.0...v0.14.1) (2021-10-18)


### Bug Fixes

* update cobra to get rid of old jwt lib ([#67](https://www.github.com/rkoshy/openapi-generator-go/issues/67)) ([e86c3b5](https://www.github.com/rkoshy/openapi-generator-go/commit/e86c3b522d4d01df948c6f8beb6a32e55184df7c))

## [0.14.0](https://www.github.com/rkoshy/openapi-generator-go/compare/v0.13.0...v0.14.0) (2021-08-30)


### Features

* ignore non-yaml files in the merge command ([#65](https://www.github.com/rkoshy/openapi-generator-go/issues/65)) ([1e2b8c9](https://www.github.com/rkoshy/openapi-generator-go/commit/1e2b8c9456e79efbd92da5d581406c78f312014f))

## [0.13.0](https://www.github.com/rkoshy/openapi-generator-go/compare/v0.12.1...v0.13.0) (2021-08-26)


### Features

* add support for pattern based validation ([#62](https://www.github.com/rkoshy/openapi-generator-go/issues/62)) ([2f02ad4](https://www.github.com/rkoshy/openapi-generator-go/commit/2f02ad457e539abb3e9bf15489cf2914bf6afe2e))
* use enum for discriminators ([#64](https://www.github.com/rkoshy/openapi-generator-go/issues/64)) ([637f11a](https://www.github.com/rkoshy/openapi-generator-go/commit/637f11a435c9286396ce857903eb21b8768af34f))

### [0.12.1](https://www.github.com/rkoshy/openapi-generator-go/compare/v0.12.0...v0.12.1) (2021-08-20)


### Bug Fixes

* prevent validation loop in discriminated oneOf ([#59](https://www.github.com/rkoshy/openapi-generator-go/issues/59)) ([5d47c8e](https://www.github.com/rkoshy/openapi-generator-go/commit/5d47c8e9779797aa2357546bd7c87ba476b9216f))

## [0.12.0](https://www.github.com/rkoshy/openapi-generator-go/compare/v0.11.0...v0.12.0) (2021-08-18)


### Features

* Add discriminator support for oneOfs ([#57](https://www.github.com/rkoshy/openapi-generator-go/issues/57)) ([78080f0](https://www.github.com/rkoshy/openapi-generator-go/commit/78080f097ffdaba8ecd8207f8d2e13e236493f2f))

## [0.11.0](https://www.github.com/rkoshy/openapi-generator-go/compare/v0.10.1...v0.11.0) (2021-08-12)


### Features

* expose the merge package as command ([#52](https://www.github.com/rkoshy/openapi-generator-go/issues/52)) ([cd2fcf9](https://www.github.com/rkoshy/openapi-generator-go/commit/cd2fcf98ddb8ee39d659741f9866732e4c32ff69))
* improve description handling in allOfs ([#55](https://www.github.com/rkoshy/openapi-generator-go/issues/55)) ([f6feffe](https://www.github.com/rkoshy/openapi-generator-go/commit/f6feffe7cd47d292ab52ed14ef75331f67655aa6))


### Bug Fixes

* MarshalJSON should not have pointer reciever ([#50](https://www.github.com/rkoshy/openapi-generator-go/issues/50)) ([4946b37](https://www.github.com/rkoshy/openapi-generator-go/commit/4946b3735971663689344c77432e6aef18880b34))

### [0.10.1](https://www.github.com/rkoshy/openapi-generator-go/compare/v0.10.0...v0.10.1) (2021-07-30)


### Bug Fixes

* improve allOf type generation ([#48](https://www.github.com/rkoshy/openapi-generator-go/issues/48)) ([c31f173](https://www.github.com/rkoshy/openapi-generator-go/commit/c31f1733f4dddcea02c1c6ca6a0ecdf74312b72e))

## [0.10.0](https://www.github.com/rkoshy/openapi-generator-go/compare/v0.9.0...v0.10.0) (2021-06-29)


### Features

* Add From* methods to set oneOf data models ([#45](https://www.github.com/rkoshy/openapi-generator-go/issues/45)) ([4bc1140](https://www.github.com/rkoshy/openapi-generator-go/commit/4bc11402f23e615422f23e3f224779d0e250dad1))

## [0.9.0](https://www.github.com/rkoshy/openapi-generator-go/compare/v0.8.1...v0.9.0) (2021-06-23)


### ⚠ BREAKING CHANGES

* add convert functions for toplevel oneofs. (#41)

### Features

* add convert functions for toplevel oneofs. ([#41](https://www.github.com/rkoshy/openapi-generator-go/issues/41)) ([93d7cc8](https://www.github.com/rkoshy/openapi-generator-go/commit/93d7cc8e4c66226352317be5ec33ee50f7580f6b))

### [0.8.1](https://www.github.com/rkoshy/openapi-generator-go/compare/v0.8.0...v0.8.1) (2021-06-17)


### Bug Fixes

* Allow responses section in components to be omitted ([#39](https://www.github.com/rkoshy/openapi-generator-go/issues/39)) ([30398af](https://www.github.com/rkoshy/openapi-generator-go/commit/30398affd55074b774627deccb42b5db396a88aa))
* use interface for oneOf ([#36](https://www.github.com/rkoshy/openapi-generator-go/issues/36)) ([6bda6b3](https://www.github.com/rkoshy/openapi-generator-go/commit/6bda6b3930d42dece3ac1f29054950267dabba76))
