# @matterlabs/hardhat-zksync-verify

## [1.10.0](https://github.com/elijah86j/hardhat-zksync/compare/@matterlabs/hardhat-zksync-verify-v1.9.1...@matterlabs/hardhat-zksync-verify-v1.10.0) (2025-09-25)


### Features

* add etherscan as verification interface ([#1518](https://github.com/elijah86j/hardhat-zksync/issues/1518)) ([0e551d9](https://github.com/elijah86j/hardhat-zksync/commit/0e551d9e2dbecc64e60dfc571f09e86c45a385fd))
* add telemetry ([f27dc7c](https://github.com/elijah86j/hardhat-zksync/commit/f27dc7c1ba87d8340cf93df12897a0c4286ded95))
* allow passing through the query params on verifyURL ([#1207](https://github.com/elijah86j/hardhat-zksync/issues/1207)) ([6e8bb7b](https://github.com/elijah86j/hardhat-zksync/commit/6e8bb7b65a14ac2bde6d3dcf980ef153273e827f))
* bump ethers, zksync-ethers, hardaht and other dependencies to newer versions ([#1111](https://github.com/elijah86j/hardhat-zksync/issues/1111)) ([7541898](https://github.com/elijah86j/hardhat-zksync/commit/754189814188a168a3ed44bcf61d8091451992dd))
* bump hardhat-zksync-deploy and hardhat-zksync-solc dependencies… ([#840](https://github.com/elijah86j/hardhat-zksync/issues/840)) ([7a92782](https://github.com/elijah86j/hardhat-zksync/commit/7a927824a754dfb18b9df59b111c8b3641b62f70))
* support for deploy time library linking ([#1505](https://github.com/elijah86j/hardhat-zksync/issues/1505)) ([19ce534](https://github.com/elijah86j/hardhat-zksync/commit/19ce53492ac4dfffeab6e75bc4c3d5d76733010d))
* support for zkvm solc compiler verification ([#662](https://github.com/elijah86j/hardhat-zksync/issues/662)) ([589c456](https://github.com/elijah86j/hardhat-zksync/commit/589c456e6f988259b179b5ff6ce59897d7c8910d))
* switch to the default codegen with zksolc ([#1062](https://github.com/elijah86j/hardhat-zksync/issues/1062)) ([086afae](https://github.com/elijah86j/hardhat-zksync/commit/086afae0a06d0311194ecd216237e6a31f36fc26))
* throw errors for older versions of the compiler ([#1770](https://github.com/elijah86j/hardhat-zksync/issues/1770)) ([a188c8b](https://github.com/elijah86j/hardhat-zksync/commit/a188c8bfa714df6ce7416af2a7961c16a42da25d))


### Bug Fixes

* add missing setting properties to support isSystem and forceEvml… ([#965](https://github.com/elijah86j/hardhat-zksync/issues/965)) ([2efd255](https://github.com/elijah86j/hardhat-zksync/commit/2efd255a3a64d12e3373eb1f557a273a76f1fcc0))
* call fallback verification with full source codes when BE throws… ([#968](https://github.com/elijah86j/hardhat-zksync/issues/968)) ([501ea1b](https://github.com/elijah86j/hardhat-zksync/commit/501ea1ba21cd1f4ad1285ebe5edbde16a7b66df3))
* compare proper bytecode execution parts ([#1773](https://github.com/elijah86j/hardhat-zksync/issues/1773)) ([21d34bb](https://github.com/elijah86j/hardhat-zksync/commit/21d34bb4e7342df81b364ba0101e57dc21632e1f))
* compiler path issue with compiler breakable changes ([#1212](https://github.com/elijah86j/hardhat-zksync/issues/1212)) ([221ec88](https://github.com/elijah86j/hardhat-zksync/commit/221ec881c4a0ebbefedfc12cd9339e1f0716356f))
* **docs:** update readme files ([#612](https://github.com/elijah86j/hardhat-zksync/issues/612)) ([d1cbbd5](https://github.com/elijah86j/hardhat-zksync/commit/d1cbbd5d3fedc16dba94abdd9f98d752adf7286e))
* get valid minimal context for verification BE request ([#1061](https://github.com/elijah86j/hardhat-zksync/issues/1061)) ([c8fc7e8](https://github.com/elijah86j/hardhat-zksync/commit/c8fc7e80abc5ca7ae6a82bb6eed550210ad86878))
* **hardhat-zksync-verify:** support for non zksync networks and solutions ([#575](https://github.com/elijah86j/hardhat-zksync/issues/575)) ([49c70ea](https://github.com/elijah86j/hardhat-zksync/commit/49c70ea671449ab912b9c9144f6e018e3f3509f0))
* migrate zkSync Etherscan verification to V2 API ([47e3f5a](https://github.com/elijah86j/hardhat-zksync/commit/47e3f5a33dd4eaf39323c40cda4d38e59b082757))
* move hardhat dependency to dev dependencies ([#1188](https://github.com/elijah86j/hardhat-zksync/issues/1188)) ([9a540f2](https://github.com/elijah86j/hardhat-zksync/commit/9a540f2d6b3c9fabf6c342ae66fe482f256e3612))
* remove verify bump from toolbox ([93e7bd6](https://github.com/elijah86j/hardhat-zksync/commit/93e7bd62d4aa9a370f328aa28ccd35974c3a68a4))
* remove zksync-ethers dependency ([#876](https://github.com/elijah86j/hardhat-zksync/issues/876)) ([ac8b687](https://github.com/elijah86j/hardhat-zksync/commit/ac8b687bb01ae1e28319189361ffe80d5888197e))
* removed openzeppelin dependency, fixed dev dependencies, and updated the contributing markdown to be clearer ([#1081](https://github.com/elijah86j/hardhat-zksync/issues/1081)) ([8a5045b](https://github.com/elijah86j/hardhat-zksync/commit/8a5045be84481cc11cc6b8d2262e74c4f219998f))
* restore workspace dependencies in hardhat-zksync-verify ([246ac38](https://github.com/elijah86j/hardhat-zksync/commit/246ac38df6f24d315a515347387637cf9d0863b1))
* send to verify service compiler input settings ([#854](https://github.com/elijah86j/hardhat-zksync/issues/854)) ([e3dc3b5](https://github.com/elijah86j/hardhat-zksync/commit/e3dc3b5e726d4a87660ab988ac80753328bbc972))
* support partial match verification for contracts with keccak metadata ([#1667](https://github.com/elijah86j/hardhat-zksync/issues/1667)) ([8b9194e](https://github.com/elijah86j/hardhat-zksync/commit/8b9194e4297f43dacaffe96025d30e092ab7018e))
* update deploy cache logic with script load path support for windows ([#865](https://github.com/elijah86j/hardhat-zksync/issues/865)) ([f88c3dc](https://github.com/elijah86j/hardhat-zksync/commit/f88c3dcf4705cca71c66a248cf47541e1ae8538c))
* update links to new doc site ([8083a9e](https://github.com/elijah86j/hardhat-zksync/commit/8083a9eea3322f01503d2c261470351032f47657))
* verify contract params format ([#1536](https://github.com/elijah86j/hardhat-zksync/issues/1536)) ([d8db408](https://github.com/elijah86j/hardhat-zksync/commit/d8db408ba88df1c0d0a8bf6b59c57732d90d6558))

## [1.9.1](https://github.com/matter-labs/hardhat-zksync/compare/@matterlabs/hardhat-zksync-verify-v1.9.0...@matterlabs/hardhat-zksync-verify-v1.9.1) (2025-08-11)


### Bug Fixes

* restore workspace dependencies in hardhat-zksync-verify ([6e2b6f8](https://github.com/matter-labs/hardhat-zksync/commit/6e2b6f8f22394e6dfbba76369c08a8205805d26c))

## [1.9.0](https://github.com/matter-labs/hardhat-zksync/compare/@matterlabs/hardhat-zksync-verify-v1.8.1...@matterlabs/hardhat-zksync-verify-v1.9.0) (2025-07-10)


### Features

* support for deploy time library linking ([#1505](https://github.com/matter-labs/hardhat-zksync/issues/1505)) ([5958825](https://github.com/matter-labs/hardhat-zksync/commit/59588255976ba81dfdd245bff6b64d58bd2aa13d))
* throw errors for older versions of the compiler ([#1770](https://github.com/matter-labs/hardhat-zksync/issues/1770)) ([19ddeb2](https://github.com/matter-labs/hardhat-zksync/commit/19ddeb26796da51adf4b0f1d895ef754424b6bf9))

## [1.8.1](https://github.com/matter-labs/hardhat-zksync/compare/@matterlabs/hardhat-zksync-verify-v1.8.0...@matterlabs/hardhat-zksync-verify-v1.8.1) (2025-06-05)


### Bug Fixes

* compare proper bytecode execution parts ([#1773](https://github.com/matter-labs/hardhat-zksync/issues/1773)) ([84267c0](https://github.com/matter-labs/hardhat-zksync/commit/84267c0a67450c06d92c79b84eaa68d254f70316))

## [1.8.0](https://github.com/matter-labs/hardhat-zksync/compare/@matterlabs/hardhat-zksync-verify-v1.7.1...@matterlabs/hardhat-zksync-verify-v1.8.0) (2025-03-25)


### Features

* add telemetry ([a345d09](https://github.com/matter-labs/hardhat-zksync/commit/a345d09e2150ac5b2b96b9e77edbe18dc0f3e7f4))


### Bug Fixes

* support partial match verification for contracts with keccak metadata ([#1667](https://github.com/matter-labs/hardhat-zksync/issues/1667)) ([e0faf3e](https://github.com/matter-labs/hardhat-zksync/commit/e0faf3e3e6686d898f49a22b42d03b0577d5020c))

## [1.7.1](https://github.com/matter-labs/hardhat-zksync/compare/@matterlabs/hardhat-zksync-verify-v1.7.0...@matterlabs/hardhat-zksync-verify-v1.7.1) (2024-11-25)


### Bug Fixes

* verify contract params format ([#1536](https://github.com/matter-labs/hardhat-zksync/issues/1536)) ([02e751e](https://github.com/matter-labs/hardhat-zksync/commit/02e751e0f6150f2a335a278efca3bd4689f3f020))

## [1.7.0](https://github.com/matter-labs/hardhat-zksync/compare/@matterlabs/hardhat-zksync-verify-v1.6.0...@matterlabs/hardhat-zksync-verify-v1.7.0) (2024-10-31)


### Features

* add etherscan as verification interface ([#1518](https://github.com/matter-labs/hardhat-zksync/issues/1518)) ([cb38fa2](https://github.com/matter-labs/hardhat-zksync/commit/cb38fa2f87d524de89106f4727e13a446d1be936))


### Bug Fixes

* update links to new doc site ([276740b](https://github.com/matter-labs/hardhat-zksync/commit/276740ba5abf8b5775e135b5653824d6456a7e4f))

## [1.6.0](https://github.com/matter-labs/hardhat-zksync/compare/@matterlabs/hardhat-zksync-verify-v1.5.0...@matterlabs/hardhat-zksync-verify-v1.6.0) (2024-07-15)


### Features

* allow passing through the query params on verifyURL ([#1207](https://github.com/matter-labs/hardhat-zksync/issues/1207)) ([9869329](https://github.com/matter-labs/hardhat-zksync/commit/9869329770bf1e458f54f3e7ced4fcab8eab84b5))


### Bug Fixes

* compiler path issue with compiler breakable changes ([#1212](https://github.com/matter-labs/hardhat-zksync/issues/1212)) ([c4231d9](https://github.com/matter-labs/hardhat-zksync/commit/c4231d922421887af60e6ebcec755ce6856292e6))
* move hardhat dependency to dev dependencies ([#1188](https://github.com/matter-labs/hardhat-zksync/issues/1188)) ([98ed333](https://github.com/matter-labs/hardhat-zksync/commit/98ed3337c841fdbfed5d356388429ff7a28c1adb))

## [1.5.0](https://github.com/matter-labs/hardhat-zksync/compare/@matterlabs/hardhat-zksync-verify-v1.4.3...@matterlabs/hardhat-zksync-verify-v1.5.0) (2024-06-19)


### Features

* bump ethers, zksync-ethers, hardaht and other dependencies to newer versions ([#1111](https://github.com/matter-labs/hardhat-zksync/issues/1111)) ([a2d503a](https://github.com/matter-labs/hardhat-zksync/commit/a2d503abe3f504859651f22998046576eddf6579))
* switch to the default codegen with zksolc ([#1062](https://github.com/matter-labs/hardhat-zksync/issues/1062)) ([5ec997a](https://github.com/matter-labs/hardhat-zksync/commit/5ec997aaa83ba18d978f10b96f489513f6c4dd9f))


### Bug Fixes

* removed openzeppelin dependency, fixed dev dependencies, and updated the contributing markdown to be clearer ([#1081](https://github.com/matter-labs/hardhat-zksync/issues/1081)) ([944bcac](https://github.com/matter-labs/hardhat-zksync/commit/944bcac1987d76f6fc135b2ddee7fb7091f5cf7f))

## [1.4.3](https://github.com/matter-labs/hardhat-zksync/compare/@matterlabs/hardhat-zksync-verify-v1.4.2...@matterlabs/hardhat-zksync-verify-v1.4.3) (2024-05-14)


### Bug Fixes

* get valid minimal context for verification BE request ([#1061](https://github.com/matter-labs/hardhat-zksync/issues/1061)) ([6d197e8](https://github.com/matter-labs/hardhat-zksync/commit/6d197e81df8cba117969e716c75f9cc72c54b0b0))

## [1.4.2](https://github.com/matter-labs/hardhat-zksync/compare/@matterlabs/hardhat-zksync-verify-v1.4.1...@matterlabs/hardhat-zksync-verify-v1.4.2) (2024-04-03)


### Bug Fixes

* add missing setting properties to support isSystem and forceEvml… ([#965](https://github.com/matter-labs/hardhat-zksync/issues/965)) ([b32243a](https://github.com/matter-labs/hardhat-zksync/commit/b32243a8bf4bf8fe71b81359a99cf9bd06117e4a))
* call fallback verification with full source codes when BE throws… ([#968](https://github.com/matter-labs/hardhat-zksync/issues/968)) ([bfe86f2](https://github.com/matter-labs/hardhat-zksync/commit/bfe86f24a22b6dcd0a2286d33fc450adb0bcc2bc))
* remove zksync-ethers dependency ([#876](https://github.com/matter-labs/hardhat-zksync/issues/876)) ([5964e3f](https://github.com/matter-labs/hardhat-zksync/commit/5964e3f35550bb14ddb50ca019e60d4b24d636d5))
* update deploy cache logic with script load path support for windows ([#865](https://github.com/matter-labs/hardhat-zksync/issues/865)) ([c30e276](https://github.com/matter-labs/hardhat-zksync/commit/c30e276903e97b12283bb742659e513bdb9dafe6))

## [1.4.1](https://github.com/matter-labs/hardhat-zksync/compare/@matterlabs/hardhat-zksync-verify-v1.4.0...@matterlabs/hardhat-zksync-verify-v1.4.1) (2024-02-29)


### Bug Fixes

* send to verify service compiler input settings ([#854](https://github.com/matter-labs/hardhat-zksync/issues/854)) ([1452e2e](https://github.com/matter-labs/hardhat-zksync/commit/1452e2e8db22d399a9142c07ea38ca7ce5fea697))

## [1.4.0](https://github.com/matter-labs/hardhat-zksync/compare/@matterlabs/hardhat-zksync-verify-v1.3.0...@matterlabs/hardhat-zksync-verify-v1.4.0) (2024-02-26)


### Features

* bump hardhat-zksync-deploy and hardhat-zksync-solc dependencies… ([#840](https://github.com/matter-labs/hardhat-zksync/issues/840)) ([b570877](https://github.com/matter-labs/hardhat-zksync/commit/b570877c78c74f3c88c7e62498e5f477d4ada616))

## [1.3.0](https://github.com/matter-labs/hardhat-zksync/compare/@matterlabs/hardhat-zksync-verify-v1.2.2...@matterlabs/hardhat-zksync-verify-v1.3.0) (2024-01-22)


### Features

* support for zkvm solc compiler verification ([#662](https://github.com/matter-labs/hardhat-zksync/issues/662)) ([a1fef16](https://github.com/matter-labs/hardhat-zksync/commit/a1fef1662ae5d9687d48bfa0e076cf3313e222df))

## [1.2.2](https://github.com/matter-labs/hardhat-zksync/compare/@matterlabs/hardhat-zksync-verify@1.2.1...@matterlabs/hardhat-zksync-verify-v1.2.2) (2023-12-22)


### Fixes

* **docs:** update readme files ([#612](https://github.com/matter-labs/hardhat-zksync/issues/612)) ([682338e](https://github.com/matter-labs/hardhat-zksync/commit/682338e60f52021206325ff6eeec2c394a118642))

## 1.2.1

### Patch Changes

- 065f52a: Fixed to work with non zksync networks

## 1.2.0

### Minor Changes

- f216797: Migration from zksync2-js to zksync-ethers

## 1.1.1

### Patch Changes

- 523985a: Added support for Sepolia testnet.

## 1.1.0

### Minor Changes

- 1148d9f: Bumped hardhat-verify version and used latest version zksync solc compiler

## 1.0.0

### Major Changes

- b3b175b: Hardhat version updates

## 0.2.1

### Patch Changes

- 64f5de0: Add noCompile flag to the contract verification script to not recompile the contracts before sending verification request

## 0.2.0

### Minor Changes

- 30d802a: Replaced hardhat-etherscan dependency with hardhat-verify dependency

## 0.1.8

### Patch Changes

- a730d07: Enable passing encoded constructor arguments in 'verify' task and 'verify:verify' subtask
- cd50e0e: Add quiet compiling during the verification process

## 0.1.7

### Patch Changes

- 670534e: Fallback verification support
- d8b7c80: Axios dependency update
- 1146fee: Expand matching solidity compilers with overrides

## 0.1.6

### Patch Changes

- c185b99: 'verify:verify' task now returns verification id
- 892c1de: Updated the usage of cbor's DecoderOptions type
- Updated dependencies [c9c91f7]
  - @matterlabs/hardhat-zksync-solc@0.3.17

## 0.1.5

### Patch Changes

- ebdc1e2: Read zksolc optimization settings and add them in verify request
