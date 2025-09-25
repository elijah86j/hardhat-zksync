# @matterlabs/hardhat-zksync-solc

## [1.6.0](https://github.com/elijah86j/hardhat-zksync/compare/@matterlabs/hardhat-zksync-solc-v1.5.1...@matterlabs/hardhat-zksync-solc-v1.6.0) (2025-09-25)


### Features

* add telemetry ([f27dc7c](https://github.com/elijah86j/hardhat-zksync/commit/f27dc7c1ba87d8340cf93df12897a0c4286ded95))
* bump ethers, zksync-ethers, hardaht and other dependencies to newer versions ([#1111](https://github.com/elijah86j/hardhat-zksync/issues/1111)) ([7541898](https://github.com/elijah86j/hardhat-zksync/commit/754189814188a168a3ed44bcf61d8091451992dd))
* support an option to fallback to optimizing for size solc ([#660](https://github.com/elijah86j/hardhat-zksync/issues/660)) ([ae850ac](https://github.com/elijah86j/hardhat-zksync/commit/ae850ac94cfda7e7fc184e00e37d63b2c0f7d9a8))
* support for deploy time library linking ([#1505](https://github.com/elijah86j/hardhat-zksync/issues/1505)) ([19ce534](https://github.com/elijah86j/hardhat-zksync/commit/19ce53492ac4dfffeab6e75bc4c3d5d76733010d))
* support for zkvm solc compiler ([#599](https://github.com/elijah86j/hardhat-zksync/issues/599)) ([6c45642](https://github.com/elijah86j/hardhat-zksync/commit/6c45642c37089aca8bb3e1849aeab7551f7e2270))
* switch to the default codegen with zksolc ([#1062](https://github.com/elijah86j/hardhat-zksync/issues/1062)) ([086afae](https://github.com/elijah86j/hardhat-zksync/commit/086afae0a06d0311194ecd216237e6a31f36fc26))
* throw errors for older versions of the compiler ([#1770](https://github.com/elijah86j/hardhat-zksync/issues/1770)) ([a188c8b](https://github.com/elijah86j/hardhat-zksync/commit/a188c8bfa714df6ce7416af2a7961c16a42da25d))


### Bug Fixes

* add check for local binary compiler ([098bfd4](https://github.com/elijah86j/hardhat-zksync/commit/098bfd4b36f41cd37b26ffd0c4cce3002f34c63e))
* add gnu toolchain for linux as default from compiler version 1.5.3 ([#1354](https://github.com/elijah86j/hardhat-zksync/issues/1354)) ([30d46c4](https://github.com/elijah86j/hardhat-zksync/commit/30d46c4c881611117a21bdefd67c4e65e0665b85))
* add mock extension for compiler path remote origins ([#824](https://github.com/elijah86j/hardhat-zksync/issues/824)) ([511ef40](https://github.com/elijah86j/hardhat-zksync/commit/511ef4044ffb4116fded884fb1f2a2cab680e4c7))
* add new compiler properties in the zksolc hardhat config object ([#1652](https://github.com/elijah86j/hardhat-zksync/issues/1652)) ([7bc07c6](https://github.com/elijah86j/hardhat-zksync/commit/7bc07c60f34100dde07db1d74f1b671f3bf92050))
* add suppressed errors and warnings ([#1375](https://github.com/elijah86j/hardhat-zksync/issues/1375)) ([c369d7c](https://github.com/elijah86j/hardhat-zksync/commit/c369d7c4643c2cd9b239024e8f7eeca5fd96415e))
* add warnings for depricated versions ([2f1a25f](https://github.com/elijah86j/hardhat-zksync/commit/2f1a25f39c2225cb5677c4c443bd787559a11c35))
* adjust solc message for missing libraries ([#783](https://github.com/elijah86j/hardhat-zksync/issues/783)) ([6031eee](https://github.com/elijah86j/hardhat-zksync/commit/6031eee319e8b189bf9ca56ddd22b1dbec823595))
* bump fallback zksolc version ([#1710](https://github.com/elijah86j/hardhat-zksync/issues/1710)) ([a0ff854](https://github.com/elijah86j/hardhat-zksync/commit/a0ff854d8b0f22d17539c45c296da7411882c83a))
* compiler path issue with compiler breakable changes ([#1212](https://github.com/elijah86j/hardhat-zksync/issues/1212)) ([221ec88](https://github.com/elijah86j/hardhat-zksync/commit/221ec881c4a0ebbefedfc12cd9339e1f0716356f))
* **docs:** update readme files ([#612](https://github.com/elijah86j/hardhat-zksync/issues/612)) ([d1cbbd5](https://github.com/elijah86j/hardhat-zksync/commit/d1cbbd5d3fedc16dba94abdd9f98d752adf7286e))
* **hardat-zksync-solc:** ensure that dir exist ([5b2cf42](https://github.com/elijah86j/hardhat-zksync/commit/5b2cf425bac888d649383b85ef9e80be67eb6050))
* **hardhat-zksync-solc:** bump solidity pragma versions ([a9617fd](https://github.com/elijah86j/hardhat-zksync/commit/a9617fdbaffd7f4e6c286317e311b01d5d7beabd))
* **hardhat-zksync-solc:** revert to older version used in other contracts ([39f9a89](https://github.com/elijah86j/hardhat-zksync/commit/39f9a89b46dd86d62d8471f4ca0b84fd82184e05))
* introduce forceContrectsToCompile to ensure that contracts not present in the source path are compiled ([#1290](https://github.com/elijah86j/hardhat-zksync/issues/1290)) ([8dc2c6a](https://github.com/elijah86j/hardhat-zksync/commit/8dc2c6a6b3239d83ca9a70856c97ec82299756e3))
* make compilationJobs argument optional at TASK_COMPILE_SOLIDITY_GET_SOLC_BUILD subtask ([#1322](https://github.com/elijah86j/hardhat-zksync/issues/1322)) ([b2b6271](https://github.com/elijah86j/hardhat-zksync/commit/b2b62711b0bb0cc396ac7efd6093dded1605c78b))
* move fallback optimizing for size to optimizer section ([#687](https://github.com/elijah86j/hardhat-zksync/issues/687)) ([37dbe9b](https://github.com/elijah86j/hardhat-zksync/commit/37dbe9b54c3d22d3b2c8dbe2150954feb98647da))
* noop commit to trigger release ([#1834](https://github.com/elijah86j/hardhat-zksync/issues/1834)) ([5ce0e7d](https://github.com/elijah86j/hardhat-zksync/commit/5ce0e7d96cfe609685f2084dced36cf854a40105))
* remove latest version leftovers ([ca1250a](https://github.com/elijah86j/hardhat-zksync/commit/ca1250a90d893a29027388d001fbd75a89dc8093))
* removes the old zksolc/zkvyper URL format ([#1813](https://github.com/elijah86j/hardhat-zksync/issues/1813)) ([cfd2b41](https://github.com/elijah86j/hardhat-zksync/commit/cfd2b416c81efc0dde6d8b5e4a07f4d32cec7a72))
* return default zksolc version of fetching fails ([#1438](https://github.com/elijah86j/hardhat-zksync/issues/1438)) ([fd3f872](https://github.com/elijah86j/hardhat-zksync/commit/fd3f87262462c66321fa716f76c71f4ae1a6452b))
* set zksolc compiler version for specified compiler path ([#804](https://github.com/elijah86j/hardhat-zksync/issues/804)) ([625e4b1](https://github.com/elijah86j/hardhat-zksync/commit/625e4b115385dce8531c0cc053b654abd40c0713))
* update fallback era compiler version to proper format ([#1446](https://github.com/elijah86j/hardhat-zksync/issues/1446)) ([2e66b9d](https://github.com/elijah86j/hardhat-zksync/commit/2e66b9d3cd3ba467b30be8b5d4ca9969ee372d0d))
* update links to new doc site ([8083a9e](https://github.com/elijah86j/hardhat-zksync/commit/8083a9eea3322f01503d2c261470351032f47657))

## [1.5.1](https://github.com/matter-labs/hardhat-zksync/compare/@matterlabs/hardhat-zksync-solc-v1.5.0...@matterlabs/hardhat-zksync-solc-v1.5.1) (2025-08-11)


### Bug Fixes

* noop commit to trigger release ([#1834](https://github.com/matter-labs/hardhat-zksync/issues/1834)) ([596f736](https://github.com/matter-labs/hardhat-zksync/commit/596f73688f1bf67fe30083e6197ad1bf2abda1c7))

## [1.5.0](https://github.com/matter-labs/hardhat-zksync/compare/@matterlabs/hardhat-zksync-solc-v1.4.0...@matterlabs/hardhat-zksync-solc-v1.5.0) (2025-07-11)


### Features

* support for deploy time library linking ([#1505](https://github.com/matter-labs/hardhat-zksync/issues/1505)) ([5958825](https://github.com/matter-labs/hardhat-zksync/commit/59588255976ba81dfdd245bff6b64d58bd2aa13d))


### Bug Fixes

* remove latest version leftovers ([a5ef140](https://github.com/matter-labs/hardhat-zksync/commit/a5ef140599af15305169ed1a5efed3be84c52990))
* removes the old zksolc/zkvyper URL format ([#1813](https://github.com/matter-labs/hardhat-zksync/issues/1813)) ([1a33687](https://github.com/matter-labs/hardhat-zksync/commit/1a336879d27638d6a2aa775b2e98abbfde71b1d2))

## [1.4.0](https://github.com/matter-labs/hardhat-zksync/compare/@matterlabs/hardhat-zksync-solc-v1.3.2...@matterlabs/hardhat-zksync-solc-v1.4.0) (2025-06-06)


### Features

* throw errors for older versions of the compiler ([#1770](https://github.com/matter-labs/hardhat-zksync/issues/1770)) ([19ddeb2](https://github.com/matter-labs/hardhat-zksync/commit/19ddeb26796da51adf4b0f1d895ef754424b6bf9))

## [1.3.2](https://github.com/matter-labs/hardhat-zksync/compare/@matterlabs/hardhat-zksync-solc-v1.3.1...@matterlabs/hardhat-zksync-solc-v1.3.2) (2025-05-09)


### Bug Fixes

* add check for local binary compiler ([318cce4](https://github.com/matter-labs/hardhat-zksync/commit/318cce4f585e5fc8741e7405e072dd1b9146a874))
* add warnings for depricated versions ([1db166c](https://github.com/matter-labs/hardhat-zksync/commit/1db166c7eea0563e3aba242e6261d854d2c793fc))

## [1.3.1](https://github.com/matter-labs/hardhat-zksync/compare/@matterlabs/hardhat-zksync-solc-v1.3.0...@matterlabs/hardhat-zksync-solc-v1.3.1) (2025-04-07)


### Bug Fixes

* bump fallback zksolc version ([#1710](https://github.com/matter-labs/hardhat-zksync/issues/1710)) ([c1f8ec2](https://github.com/matter-labs/hardhat-zksync/commit/c1f8ec2e40b862fe8dc61f80b5a196a64fd000fd))

## [1.3.0](https://github.com/matter-labs/hardhat-zksync/compare/@matterlabs/hardhat-zksync-solc-v1.2.6...@matterlabs/hardhat-zksync-solc-v1.3.0) (2025-03-25)


### Features

* add telemetry ([a345d09](https://github.com/matter-labs/hardhat-zksync/commit/a345d09e2150ac5b2b96b9e77edbe18dc0f3e7f4))

## [1.2.6](https://github.com/matter-labs/hardhat-zksync/compare/@matterlabs/hardhat-zksync-solc-v1.2.5...@matterlabs/hardhat-zksync-solc-v1.2.6) (2025-03-03)


### Bug Fixes

* add new compiler properties in the zksolc hardhat config object ([#1652](https://github.com/matter-labs/hardhat-zksync/issues/1652)) ([f5ec774](https://github.com/matter-labs/hardhat-zksync/commit/f5ec7748fd81b570b76146747358e5214559c00f))

## [1.2.5](https://github.com/matter-labs/hardhat-zksync/compare/@matterlabs/hardhat-zksync-solc-v1.2.4...@matterlabs/hardhat-zksync-solc-v1.2.5) (2024-09-25)


### Bug Fixes

* add suppressed errors and warnings ([#1375](https://github.com/matter-labs/hardhat-zksync/issues/1375)) ([a0bf6e5](https://github.com/matter-labs/hardhat-zksync/commit/a0bf6e57c17b063b292e26acfa8bf8f8d1974644))
* return default zksolc version of fetching fails ([#1438](https://github.com/matter-labs/hardhat-zksync/issues/1438)) ([b5e4582](https://github.com/matter-labs/hardhat-zksync/commit/b5e4582c36ad79a809778bfaf29e83549668c1d6))
* update fallback era compiler version to proper format ([#1446](https://github.com/matter-labs/hardhat-zksync/issues/1446)) ([c41dbcd](https://github.com/matter-labs/hardhat-zksync/commit/c41dbcd193f97296420061756c73160f078fb7b9))

## [1.2.4](https://github.com/matter-labs/hardhat-zksync/compare/@matterlabs/hardhat-zksync-solc-v1.2.3...@matterlabs/hardhat-zksync-solc-v1.2.4) (2024-09-05)


### Bug Fixes

* add gnu toolchain for linux as default from compiler version 1.5.3 ([#1354](https://github.com/matter-labs/hardhat-zksync/issues/1354)) ([448a2ce](https://github.com/matter-labs/hardhat-zksync/commit/448a2ceb6141e519e4d00a41edbf3381b282e128))

## [1.2.3](https://github.com/matter-labs/hardhat-zksync/compare/@matterlabs/hardhat-zksync-solc-v1.2.2...@matterlabs/hardhat-zksync-solc-v1.2.3) (2024-08-26)


### Bug Fixes

* make compilationJobs argument optional at TASK_COMPILE_SOLIDITY_GET_SOLC_BUILD subtask ([#1322](https://github.com/matter-labs/hardhat-zksync/issues/1322)) ([6877903](https://github.com/matter-labs/hardhat-zksync/commit/68779035a5f611593331f6063a9d7f8b8f07a899))

## [1.2.2](https://github.com/matter-labs/hardhat-zksync/compare/@matterlabs/hardhat-zksync-solc-v1.2.1...@matterlabs/hardhat-zksync-solc-v1.2.2) (2024-08-15)


### Bug Fixes

* introduce forceContrectsToCompile to ensure that contracts not present in the source path are compiled ([#1290](https://github.com/matter-labs/hardhat-zksync/issues/1290)) ([fcbcd1f](https://github.com/matter-labs/hardhat-zksync/commit/fcbcd1f56fd66be02af8fd60358656327521093e))

## [1.2.1](https://github.com/matter-labs/hardhat-zksync/compare/@matterlabs/hardhat-zksync-solc-v1.2.0...@matterlabs/hardhat-zksync-solc-v1.2.1) (2024-07-09)


### Bug Fixes

* compiler path issue with compiler breakable changes ([#1212](https://github.com/matter-labs/hardhat-zksync/issues/1212)) ([c4231d9](https://github.com/matter-labs/hardhat-zksync/commit/c4231d922421887af60e6ebcec755ce6856292e6))

## [1.2.0](https://github.com/matter-labs/hardhat-zksync/compare/@matterlabs/hardhat-zksync-solc-v1.1.4...@matterlabs/hardhat-zksync-solc-v1.2.0) (2024-06-19)


### Features

* bump ethers, zksync-ethers, hardaht and other dependencies to newer versions ([#1111](https://github.com/matter-labs/hardhat-zksync/issues/1111)) ([a2d503a](https://github.com/matter-labs/hardhat-zksync/commit/a2d503abe3f504859651f22998046576eddf6579))
* switch to the default codegen with zksolc ([#1062](https://github.com/matter-labs/hardhat-zksync/issues/1062)) ([5ec997a](https://github.com/matter-labs/hardhat-zksync/commit/5ec997aaa83ba18d978f10b96f489513f6c4dd9f))

## [1.1.4](https://github.com/matter-labs/hardhat-zksync/compare/@matterlabs/hardhat-zksync-solc-v1.1.3...@matterlabs/hardhat-zksync-solc-v1.1.4) (2024-02-26)


### Bug Fixes

* add mock extension for compiler path remote origins ([#824](https://github.com/matter-labs/hardhat-zksync/issues/824)) ([14e3e80](https://github.com/matter-labs/hardhat-zksync/commit/14e3e80df60cc74ae2c26f6bfa487b17bd212f73))
* adjust solc message for missing libraries ([#783](https://github.com/matter-labs/hardhat-zksync/issues/783)) ([aa2b48b](https://github.com/matter-labs/hardhat-zksync/commit/aa2b48b98d5fc11570161a6b7cdfa1944ef5e8a4))

## [1.1.3](https://github.com/matter-labs/hardhat-zksync/compare/@matterlabs/hardhat-zksync-solc-v1.1.2...@matterlabs/hardhat-zksync-solc-v1.1.3) (2024-02-21)


### Bug Fixes

* set zksolc compiler version for specified compiler path ([#804](https://github.com/matter-labs/hardhat-zksync/issues/804)) ([7d2aa6c](https://github.com/matter-labs/hardhat-zksync/commit/7d2aa6cd180d601161af0399bd8fad884f598683))

## [1.1.2](https://github.com/matter-labs/hardhat-zksync/compare/@matterlabs/hardhat-zksync-solc-v1.1.1...@matterlabs/hardhat-zksync-solc-v1.1.2) (2024-01-25)


### Bug Fixes

* move fallback optimizing for size to optimizer section ([#687](https://github.com/matter-labs/hardhat-zksync/issues/687)) ([a1ab511](https://github.com/matter-labs/hardhat-zksync/commit/a1ab51196ec0066a37df46e1a1be0970b8152cba))

## [1.1.1](https://github.com/matter-labs/hardhat-zksync/compare/@matterlabs/hardhat-zksync-solc-v1.1.0...@matterlabs/hardhat-zksync-solc-v1.1.1) (2024-01-25)


### Fixes

* support an option to fallback to optimizing for size solc ([#660](https://github.com/matter-labs/hardhat-zksync/issues/660)) ([eaf4413](https://github.com/matter-labs/hardhat-zksync/commit/eaf44134b588ec869593b2799f9603698d7cfca2))

## [1.1.0](https://github.com/matter-labs/hardhat-zksync/compare/@matterlabs/hardhat-zksync-solc-v1.0.6...@matterlabs/hardhat-zksync-solc-v1.1.0) (2024-01-22)


### Features

* support for zkvm solc compiler ([#599](https://github.com/matter-labs/hardhat-zksync/issues/599)) ([241a6e1](https://github.com/matter-labs/hardhat-zksync/commit/241a6e11899b5d893159f71cf388417d46082351))

## [1.0.6](https://github.com/matter-labs/hardhat-zksync/compare/@matterlabs/hardhat-zksync-solc@1.0.5...@matterlabs/hardhat-zksync-solc-v1.0.6) (2023-12-22)


### Fixes

* **docs:** update readme files ([#612](https://github.com/matter-labs/hardhat-zksync/issues/612)) ([682338e](https://github.com/matter-labs/hardhat-zksync/commit/682338e60f52021206325ff6eeec2c394a118642))

## 1.0.5

### Patch Changes

- f4677a0: Get latest release from redirect URL

## 1.0.4

### Patch Changes

- 12fad5f:
  - Proper User-Agent for getRelease function
  - Contract source names can now match contract names without full overlap.

## 1.0.3

### Patch Changes

- fc5d370: Fetch compiler version info from the latest release

## 1.0.2

### Patch Changes

- 13419e9: Localized compiler version info data

## 1.0.1

### Patch Changes

- efbc6d8: Added CDN for compiler file version info download.

## 1.0.0

### Major Changes

- dfa0ac2: Hardhat version updates

## 0.4.2

### Patch Changes

- a079196: - Added detect-missing-library mode
  - Added release URL as primary download source for zkvyper compiler

## 0.4.1

### Patch Changes

- a1a8f8e: Enable library caching

## 0.4.0

### Minor Changes

- 224cc6c:
  - Enhanced zksolc compiler version checking mechanism.
  - Improved error handling for incorrect zksolc compiler versions.
  - Optimized validation process for zksolc compiler configuration.
  - Added informative messages for recommended and deprecated zksolc compiler versions.
  - General code optimizations and enhancements.

## 0.3.17

### Patch Changes

- 48e2699: Update solidity overrides config in the same way as compilers solidity config
- c9c91f7: Add metadata settings to zksolc config
