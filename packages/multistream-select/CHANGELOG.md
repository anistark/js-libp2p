## [3.1.9](https://github.com/libp2p/js-libp2p-multistream-select/compare/v3.1.8...v3.1.9) (2023-06-15)


### Trivial Changes

* Update .github/workflows/semantic-pull-request.yml [skip ci] ([c03b6cd](https://github.com/libp2p/js-libp2p-multistream-select/commit/c03b6cd8013a82605f414a5ddbde7c66c84e4db1))
* Update .github/workflows/stale.yml [skip ci] ([e8d5014](https://github.com/libp2p/js-libp2p-multistream-select/commit/e8d5014b6da7bf4db1cc542c5d923760a6067903))


### Dependencies

* **dev:** bump aegir from 38.1.8 to 39.0.10 ([#70](https://github.com/libp2p/js-libp2p-multistream-select/issues/70)) ([f87b1c3](https://github.com/libp2p/js-libp2p-multistream-select/commit/f87b1c3505934ebeed6eff018af8d3042e7e6e06))

## [5.0.1](https://github.com/libp2p/js-libp2p/compare/multistream-select-v5.0.0...multistream-select-v5.0.1) (2023-12-02)


### Bug Fixes

* do not wait for stream reads and writes at the same time ([#2290](https://github.com/libp2p/js-libp2p/issues/2290)) ([10ea197](https://github.com/libp2p/js-libp2p/commit/10ea19700ae0c464734c88eb5922e2faeb27446a))

## [5.0.0](https://github.com/libp2p/js-libp2p/compare/multistream-select-v4.0.9...multistream-select-v5.0.0) (2023-12-01)


### ⚠ BREAKING CHANGES

* requires libp2p v1

### Bug Fixes

* release majors of modules that had patches during v1.0 ([#2286](https://github.com/libp2p/js-libp2p/issues/2286)) ([738dd40](https://github.com/libp2p/js-libp2p/commit/738dd40f1e1b8ed1b83693763cc91c218ec2b41b))

## [4.0.9](https://github.com/libp2p/js-libp2p/compare/multistream-select-v4.0.8...multistream-select-v4.0.9) (2023-12-01)


### Bug Fixes

* make mss check logger before use ([#2261](https://github.com/libp2p/js-libp2p/issues/2261)) ([#2274](https://github.com/libp2p/js-libp2p/issues/2274)) ([cf96369](https://github.com/libp2p/js-libp2p/commit/cf963694f0253cc32ef805980c5be3397a41fae2))

## [4.0.8](https://github.com/libp2p/js-libp2p/compare/multistream-select-v4.0.7...multistream-select-v4.0.8) (2023-11-30)


### Bug Fixes

* restore lost commits ([#2268](https://github.com/libp2p/js-libp2p/issues/2268)) ([5775f1d](https://github.com/libp2p/js-libp2p/commit/5775f1df4f5561500e622dc0788fdacbc74e2755))


### Dependencies

* The following workspace dependencies were updated
  * dependencies
    * @libp2p/interface bumped from ^1.0.0 to ^1.0.1
  * devDependencies
    * @libp2p/logger bumped from ^4.0.0 to ^4.0.1

### [4.0.7](https://www.github.com/libp2p/js-libp2p/compare/multistream-select-v4.0.6...multistream-select-v4.0.7) (2023-11-28)


### Bug Fixes

* allow mss lazy select on read ([#2246](https://www.github.com/libp2p/js-libp2p/issues/2246)) ([d8f5bc2](https://www.github.com/libp2p/js-libp2p/commit/d8f5bc211185a963c2a5182d58d73629457bc78d))
* use logging component everywhere ([#2228](https://www.github.com/libp2p/js-libp2p/issues/2228)) ([e5dfde0](https://www.github.com/libp2p/js-libp2p/commit/e5dfde0883191c93903ca552433f177d48adf0b3))
* use optimistic protocol negotation ([#2253](https://www.github.com/libp2p/js-libp2p/issues/2253)) ([0b4a2ee](https://www.github.com/libp2p/js-libp2p/commit/0b4a2ee7983b4dc9dc0a7b705a202a4c550e7017))


### Dependencies

* The following workspace dependencies were updated
  * dependencies
    * @libp2p/interface bumped from ^0.1.6 to ^1.0.0
  * devDependencies
    * @libp2p/logger bumped from ^3.1.0 to ^4.0.0

### [4.0.6](https://www.github.com/libp2p/js-libp2p/compare/multistream-select-v4.0.5...multistream-select-v4.0.6) (2023-11-07)


### Dependencies

* The following workspace dependencies were updated
  * dependencies
    * @libp2p/interface bumped from ^0.1.5 to ^0.1.6
    * @libp2p/logger bumped from ^3.0.5 to ^3.1.0

### [4.0.5](https://www.github.com/libp2p/js-libp2p/compare/multistream-select-v4.0.4...multistream-select-v4.0.5) (2023-11-03)


### Dependencies

* The following workspace dependencies were updated
  * dependencies
    * @libp2p/interface bumped from ^0.1.4 to ^0.1.5
    * @libp2p/logger bumped from ^3.0.4 to ^3.0.5

### [4.0.4](https://www.github.com/libp2p/js-libp2p/compare/multistream-select-v4.0.3...multistream-select-v4.0.4) (2023-10-25)


### Dependencies

* The following workspace dependencies were updated
  * dependencies
    * @libp2p/interface bumped from ^0.1.3 to ^0.1.4
    * @libp2p/logger bumped from ^3.0.3 to ^3.0.4

### [4.0.3](https://www.github.com/libp2p/js-libp2p/compare/multistream-select-v4.0.2...multistream-select-v4.0.3) (2023-10-06)


### Dependencies

* The following workspace dependencies were updated
  * dependencies
    * @libp2p/interface bumped from ^0.1.2 to ^0.1.3
    * @libp2p/logger bumped from ^3.0.2 to ^3.0.3

### [4.0.2](https://www.github.com/libp2p/js-libp2p/compare/multistream-select-v4.0.1...multistream-select-v4.0.2) (2023-08-14)


### Bug Fixes

* update project config ([9c0353c](https://www.github.com/libp2p/js-libp2p/commit/9c0353cf5a1e13196ca0e7764f87e36478518f69))


### Dependencies

* The following workspace dependencies were updated
  * dependencies
    * @libp2p/interface bumped from ^0.1.1 to ^0.1.2
    * @libp2p/logger bumped from ^3.0.1 to ^3.0.2

### [4.0.1](https://www.github.com/libp2p/js-libp2p/compare/multistream-select-v4.0.0...multistream-select-v4.0.1) (2023-08-05)


### Dependencies

* The following workspace dependencies were updated
  * dependencies
    * @libp2p/interface bumped from ^0.1.0 to ^0.1.1
    * @libp2p/logger bumped from ^3.0.0 to ^3.0.1

## [4.0.0](https://www.github.com/libp2p/js-libp2p/compare/multistream-select-v3.1.9...multistream-select-v4.0.0) (2023-07-31)


### ⚠ BREAKING CHANGES

* the `.close`, `closeRead` and `closeWrite` methods on the `Stream` interface are now asynchronous
* `stream.stat.*` and `conn.stat.*` properties are now accessed via `stream.*` and `conn.*`
* consolidate interface modules (#1833)

### Features

* merge stat properties into stream/connection objects ([#1856](https://www.github.com/libp2p/js-libp2p/issues/1856)) ([e9cafd3](https://www.github.com/libp2p/js-libp2p/commit/e9cafd3d8ab0f8e0655ff44e04aa41fccc912b51)), closes [#1849](https://www.github.com/libp2p/js-libp2p/issues/1849)


### Bug Fixes

* close streams gracefully ([#1864](https://www.github.com/libp2p/js-libp2p/issues/1864)) ([b36ec7f](https://www.github.com/libp2p/js-libp2p/commit/b36ec7f24e477af21cec31effc086a6c611bf271)), closes [#1793](https://www.github.com/libp2p/js-libp2p/issues/1793) [#656](https://www.github.com/libp2p/js-libp2p/issues/656)
* consolidate interface modules ([#1833](https://www.github.com/libp2p/js-libp2p/issues/1833)) ([4255b1e](https://www.github.com/libp2p/js-libp2p/commit/4255b1e2485d31e00c33efa029b6426246ea23e3))


### Dependencies

* The following workspace dependencies were updated
  * dependencies
    * @libp2p/interface bumped from ~0.0.1 to ^0.1.0
    * @libp2p/logger bumped from ^2.0.0 to ^3.0.0

## [3.1.8](https://github.com/libp2p/js-libp2p-multistream-select/compare/v3.1.7...v3.1.8) (2023-04-19)


### Dependencies

* update abortable iterator to 5.x.x ([#61](https://github.com/libp2p/js-libp2p-multistream-select/issues/61)) ([5bc4293](https://github.com/libp2p/js-libp2p-multistream-select/commit/5bc42936e25e14791d19fdd790d3c3987c56e784))

## [3.1.7](https://github.com/libp2p/js-libp2p-multistream-select/compare/v3.1.6...v3.1.7) (2023-04-18)


### Bug Fixes

* specify protocol stream sink return type ([#60](https://github.com/libp2p/js-libp2p-multistream-select/issues/60)) ([12d6b9c](https://github.com/libp2p/js-libp2p-multistream-select/commit/12d6b9c4ea26b26d0428df2d05c3078464068392))

## [3.1.6](https://github.com/libp2p/js-libp2p-multistream-select/compare/v3.1.5...v3.1.6) (2023-04-18)


### Dependencies

* bump it-stream-types from 1.0.5 to 2.0.1 ([#58](https://github.com/libp2p/js-libp2p-multistream-select/issues/58)) ([0b0ebca](https://github.com/libp2p/js-libp2p-multistream-select/commit/0b0ebcadd0ccbbfd373ebbf8e9fb5a8b793fc924))

## [3.1.5](https://github.com/libp2p/js-libp2p-multistream-select/compare/v3.1.4...v3.1.5) (2023-04-17)


### Bug Fixes

* use trace logging for happy paths ([#59](https://github.com/libp2p/js-libp2p-multistream-select/issues/59)) ([184ef21](https://github.com/libp2p/js-libp2p-multistream-select/commit/184ef21c930c1557d657ce0891471d86f76fb271))

## [3.1.4](https://github.com/libp2p/js-libp2p-multistream-select/compare/v3.1.3...v3.1.4) (2023-04-03)


### Dependencies

* update all it-* deps to the latest versions ([#57](https://github.com/libp2p/js-libp2p-multistream-select/issues/57)) ([cf9133a](https://github.com/libp2p/js-libp2p-multistream-select/commit/cf9133a00b73c9e6d7576b57d2dccd9e87ccd01e))

## [3.1.3](https://github.com/libp2p/js-libp2p-multistream-select/compare/v3.1.2...v3.1.3) (2023-03-31)


### Trivial Changes

* replace err-code with CodeError ([#36](https://github.com/libp2p/js-libp2p-multistream-select/issues/36)) ([fc2aefd](https://github.com/libp2p/js-libp2p-multistream-select/commit/fc2aefdec0db9a2b39fe8259881cf3a2693027cb)), closes [js-libp2p#1269](https://github.com/libp2p/js-libp2p/issues/1269)
* Update .github/workflows/semantic-pull-request.yml [skip ci] ([1861a94](https://github.com/libp2p/js-libp2p-multistream-select/commit/1861a945fd8fef3d407591632d92f080d07e0bed))
* Update .github/workflows/semantic-pull-request.yml [skip ci] ([0f312c0](https://github.com/libp2p/js-libp2p-multistream-select/commit/0f312c08f3760f188304074088060f3d701e5815))
* Update .github/workflows/semantic-pull-request.yml [skip ci] ([6a277a6](https://github.com/libp2p/js-libp2p-multistream-select/commit/6a277a6efdcbd3afef72335699d3a61e4bbea609))


### Dependencies

* bump it-merge from 2.0.1 to 3.0.0 ([#51](https://github.com/libp2p/js-libp2p-multistream-select/issues/51)) ([129166b](https://github.com/libp2p/js-libp2p-multistream-select/commit/129166ba5366d29d20e2629ce1f542c57cc864ba))
* **dev:** bump it-all from 2.0.1 to 3.0.1 ([#50](https://github.com/libp2p/js-libp2p-multistream-select/issues/50)) ([d8420a0](https://github.com/libp2p/js-libp2p-multistream-select/commit/d8420a03207be7ee3472c4bb7a4f3cc0912758a1))

## [3.1.2](https://github.com/libp2p/js-libp2p-multistream-select/compare/v3.1.1...v3.1.2) (2022-12-16)


### Trivial Changes

* log invalid buffer ([#30](https://github.com/libp2p/js-libp2p-multistream-select/issues/30)) ([1fce957](https://github.com/libp2p/js-libp2p-multistream-select/commit/1fce9579eefe32a81b9805edc6a348f37605ac7f))
* update it-* deps ([#31](https://github.com/libp2p/js-libp2p-multistream-select/issues/31)) ([3caf904](https://github.com/libp2p/js-libp2p-multistream-select/commit/3caf904c20aab7dc4ca61f40420b18e84bbd2c49))


### Documentation

* publish api docs ([#35](https://github.com/libp2p/js-libp2p-multistream-select/issues/35)) ([c4c978a](https://github.com/libp2p/js-libp2p-multistream-select/commit/c4c978ac1eb84667d5568c5f68a6678cf460380f))

## [3.1.1](https://github.com/libp2p/js-libp2p-multistream-select/compare/v3.1.0...v3.1.1) (2022-10-31)


### Bug Fixes

* set min and max protocol length ([#21](https://github.com/libp2p/js-libp2p-multistream-select/issues/21)) ([ae42f76](https://github.com/libp2p/js-libp2p-multistream-select/commit/ae42f7623b557d33208c12c69d7f01e49f478fdb))


### Trivial Changes

* update to handshake 4.1.2 ([#28](https://github.com/libp2p/js-libp2p-multistream-select/issues/28)) ([53883b1](https://github.com/libp2p/js-libp2p-multistream-select/commit/53883b1c6215584043f4dd6e97e2d10adb890af6))

## [3.1.0](https://github.com/libp2p/js-libp2p-multistream-select/compare/v3.0.0...v3.1.0) (2022-10-12)


### Features

* add lazy select ([#18](https://github.com/libp2p/js-libp2p-multistream-select/issues/18)) ([d3bff7c](https://github.com/libp2p/js-libp2p-multistream-select/commit/d3bff7cc3cd5afe6ebc1355241030868ec0aa572))


### Trivial Changes

* Update .github/workflows/stale.yml [skip ci] ([ba9ea12](https://github.com/libp2p/js-libp2p-multistream-select/commit/ba9ea12b2b55602bbeb6c9227976419851496783))


### Dependencies

* bump uint8arrays from 3.x.x to 4.x.x ([#22](https://github.com/libp2p/js-libp2p-multistream-select/issues/22)) ([cfb887b](https://github.com/libp2p/js-libp2p-multistream-select/commit/cfb887b9bc01f8234838049c59866064db97bdf5))

## [3.0.0](https://github.com/libp2p/js-libp2p-multistream-select/compare/v2.0.2...v3.0.0) (2022-08-06)


### ⚠ BREAKING CHANGES

* the single-method Listener and Dialer classes have been removed and their methods exported instead

### Bug Fixes

* support Duplex<Uint8Array> and Duplex<Uint8ArrayList> ([#17](https://github.com/libp2p/js-libp2p-multistream-select/issues/17)) ([6e96c89](https://github.com/libp2p/js-libp2p-multistream-select/commit/6e96c89b68a77ea5192e91cab5547e78f5b078fd))

## [2.0.2](https://github.com/libp2p/js-libp2p-multistream-select/compare/v2.0.1...v2.0.2) (2022-07-31)


### Trivial Changes

* update project config ([#14](https://github.com/libp2p/js-libp2p-multistream-select/issues/14)) ([4d4ef28](https://github.com/libp2p/js-libp2p-multistream-select/commit/4d4ef28af8cb8d0f57e06d9ae161ba31e2c5e814))


### Dependencies

* update it-length-prefixed deps to support no-copy ops ([#16](https://github.com/libp2p/js-libp2p-multistream-select/issues/16)) ([2946064](https://github.com/libp2p/js-libp2p-multistream-select/commit/2946064a8993b4ec70ebfd3e5a34d86db1ee7fe6))

## [2.0.1](https://github.com/libp2p/js-libp2p-multistream-select/compare/v2.0.0...v2.0.1) (2022-06-17)


### Trivial Changes

* update deps ([#9](https://github.com/libp2p/js-libp2p-multistream-select/issues/9)) ([dc5ddc1](https://github.com/libp2p/js-libp2p-multistream-select/commit/dc5ddc1b93da82a98e5acddc25a8e41c6eb67044))

## [2.0.0](https://github.com/libp2p/js-libp2p-multistream-select/compare/v1.0.6...v2.0.0) (2022-06-15)


### ⚠ BREAKING CHANGES

* updates to single-issue libp2p interfaces and ls has been removed

### Features

* update interfaces, remove ls ([#3](https://github.com/libp2p/js-libp2p-multistream-select/issues/3)) ([1e6f3cd](https://github.com/libp2p/js-libp2p-multistream-select/commit/1e6f3cdffee6683786349142349a50872fa8fd17)), closes [#2](https://github.com/libp2p/js-libp2p-multistream-select/issues/2)

## [@libp2p/multistream-select-v1.0.6](https://github.com/libp2p/js-libp2p-interfaces/compare/@libp2p/multistream-select-v1.0.5...@libp2p/multistream-select-v1.0.6) (2022-05-24)


### Bug Fixes

* chunk data in mock muxer ([#218](https://github.com/libp2p/js-libp2p-interfaces/issues/218)) ([14604f6](https://github.com/libp2p/js-libp2p-interfaces/commit/14604f69a858bf8c16ce118420c5e49f3f5331ea))

## [@libp2p/multistream-select-v1.0.5](https://github.com/libp2p/js-libp2p-interfaces/compare/@libp2p/multistream-select-v1.0.4...@libp2p/multistream-select-v1.0.5) (2022-05-20)


### Bug Fixes

* update interfaces ([#215](https://github.com/libp2p/js-libp2p-interfaces/issues/215)) ([72e6890](https://github.com/libp2p/js-libp2p-interfaces/commit/72e6890826dadbd6e7cbba5536bde350ca4286e6))

## [@libp2p/multistream-select-v1.0.4](https://github.com/libp2p/js-libp2p-interfaces/compare/@libp2p/multistream-select-v1.0.3...@libp2p/multistream-select-v1.0.4) (2022-04-08)


### Bug Fixes

* swap protobufjs for protons ([#191](https://github.com/libp2p/js-libp2p-interfaces/issues/191)) ([d72b30c](https://github.com/libp2p/js-libp2p-interfaces/commit/d72b30cfca4b9145e0b31db28e8fa3329a180e83))


### Trivial Changes

* update aegir ([#192](https://github.com/libp2p/js-libp2p-interfaces/issues/192)) ([41c1494](https://github.com/libp2p/js-libp2p-interfaces/commit/41c14941e8b67d6601a90b4d48a2776573d55e60))

## [@libp2p/multistream-select-v1.0.3](https://github.com/libp2p/js-libp2p-interfaces/compare/@libp2p/multistream-select-v1.0.2...@libp2p/multistream-select-v1.0.3) (2022-03-15)


### Bug Fixes

* simplify transport interface, update interfaces for use with libp2p ([#180](https://github.com/libp2p/js-libp2p-interfaces/issues/180)) ([ec81622](https://github.com/libp2p/js-libp2p-interfaces/commit/ec81622e5b7c6d256e0f8aed6d3695642473293b))

## [@libp2p/multistream-select-v1.0.2](https://github.com/libp2p/js-libp2p-interfaces/compare/@libp2p/multistream-select-v1.0.1...@libp2p/multistream-select-v1.0.2) (2022-02-27)


### Bug Fixes

* rename crypto to connection-encrypter ([#179](https://github.com/libp2p/js-libp2p-interfaces/issues/179)) ([d197f55](https://github.com/libp2p/js-libp2p-interfaces/commit/d197f554d7cdadb3b05ed2d6c69fda2c4362b1eb))

## [@libp2p/multistream-select-v1.0.1](https://github.com/libp2p/js-libp2p-interfaces/compare/@libp2p/multistream-select-v1.0.0...@libp2p/multistream-select-v1.0.1) (2022-02-27)


### Bug Fixes

* update package config and add connection gater interface ([#178](https://github.com/libp2p/js-libp2p-interfaces/issues/178)) ([c6079a6](https://github.com/libp2p/js-libp2p-interfaces/commit/c6079a6367f004788062df3e30ad2e26330d947b))

## @libp2p/multistream-select-v1.0.0 (2022-02-17)


### Bug Fixes

* add multistream-select and update pubsub types ([#170](https://github.com/libp2p/js-libp2p-interfaces/issues/170)) ([b9ecb2b](https://github.com/libp2p/js-libp2p-interfaces/commit/b9ecb2bee8f2abc0c41bfcf7bf2025894e37ddc2))
