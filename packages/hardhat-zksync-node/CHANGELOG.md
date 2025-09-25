# @matterlabs/hardhat-zksync-node

## [1.6.0](https://github.com/elijah86j/hardhat-zksync/compare/@matterlabs/hardhat-zksync-node-v1.5.3...@matterlabs/hardhat-zksync-node-v1.6.0) (2025-09-25)


### Features

* add telemetry ([f27dc7c](https://github.com/elijah86j/hardhat-zksync/commit/f27dc7c1ba87d8340cf93df12897a0c4286ded95))
* bump anvil-zksync version and add new parameters ([#1709](https://github.com/elijah86j/hardhat-zksync/issues/1709)) ([d66c1f2](https://github.com/elijah86j/hardhat-zksync/commit/d66c1f2c1250168642f1b44d40faf420adec010a))
* bump ethers, zksync-ethers, hardaht and other dependencies to newer versions ([#1111](https://github.com/elijah86j/hardhat-zksync/issues/1111)) ([7541898](https://github.com/elijah86j/hardhat-zksync/commit/754189814188a168a3ed44bcf61d8091451992dd))
* get release tag from redirect url at node plugin ([#668](https://github.com/elijah86j/hardhat-zksync/issues/668)) ([a390c8c](https://github.com/elijah86j/hardhat-zksync/commit/a390c8c500f5d9ae6334a24be880714a77adb414))
* override run task for zksync hardhat network ([#1462](https://github.com/elijah86j/hardhat-zksync/issues/1462)) ([37afa27](https://github.com/elijah86j/hardhat-zksync/commit/37afa275b2d8618651f70cc48ded774b1d836a0f))
* set default version and handle github repo redirects ([#1577](https://github.com/elijah86j/hardhat-zksync/issues/1577)) ([8458363](https://github.com/elijah86j/hardhat-zksync/commit/8458363fd50f8340b612c757e59b9524f0a596a1))
* show contract logs while running tests and scripts with zksync hadrhat node ([f6a956f](https://github.com/elijah86j/hardhat-zksync/commit/f6a956fe9bca30dfe58712c3569fcaafd6977a7f))
* switch to the default codegen with zksolc ([#1062](https://github.com/elijah86j/hardhat-zksync/issues/1062)) ([086afae](https://github.com/elijah86j/hardhat-zksync/commit/086afae0a06d0311194ecd216237e6a31f36fc26))


### Bug Fixes

* add offline mode to global and rename emulateEVM to corrected name ([884f9df](https://github.com/elijah86j/hardhat-zksync/commit/884f9df7b8f64c710e91aec469b1b01ea65eda70))
* add type extension to the index ([#1651](https://github.com/elijah86j/hardhat-zksync/issues/1651)) ([f84daf5](https://github.com/elijah86j/hardhat-zksync/commit/f84daf5866049042ec446045e3e87e8d78c15c8b))
* anvil-zksync bumped default version ([#1751](https://github.com/elijah86j/hardhat-zksync/issues/1751)) ([8959506](https://github.com/elijah86j/hardhat-zksync/commit/8959506ed477373c3bcf0fb38c78accff766ef77))
* apply anvil cli args with values ([e7c2172](https://github.com/elijah86j/hardhat-zksync/commit/e7c2172ee50da9fcb6be005458e362b9fdac1022))
* create node cache directory with permissions ([#1642](https://github.com/elijah86j/hardhat-zksync/issues/1642)) ([5db0901](https://github.com/elijah86j/hardhat-zksync/commit/5db0901d1cf7145bbf94933e83305a06d84735c9))
* **docs:** update readme files ([#612](https://github.com/elijah86j/hardhat-zksync/issues/612)) ([d1cbbd5](https://github.com/elijah86j/hardhat-zksync/commit/d1cbbd5d3fedc16dba94abdd9f98d752adf7286e))
* **hardhat-zksync-node:** Proper user_agent for getRelease ([d615e79](https://github.com/elijah86j/hardhat-zksync/commit/d615e79c919ea870843e6e23db1b99f1a3326b1f))
* **hardhat-zksync-node:** Proper user_agent for getRelease ([1757952](https://github.com/elijah86j/hardhat-zksync/commit/1757952cf420e1d7c2ca57c990a714cd06b7b2a2))
* noop commit to trigger release ([#1834](https://github.com/elijah86j/hardhat-zksync/issues/1834)) ([5ce0e7d](https://github.com/elijah86j/hardhat-zksync/commit/5ce0e7d96cfe609685f2084dced36cf854a40105))
* properly constructor fork arguments ([#927](https://github.com/elijah86j/hardhat-zksync/issues/927)) ([fd52e18](https://github.com/elijah86j/hardhat-zksync/commit/fd52e18ef4eb0a2edfcba478c58885d624c5b97c))
* remove zksync-ethers dependency  ([#920](https://github.com/elijah86j/hardhat-zksync/issues/920)) ([bdb281e](https://github.com/elijah86j/hardhat-zksync/commit/bdb281e8ec0ee0016ba82a6e2a83afdb61664d4c))
* rename silent param to quiet ([#1759](https://github.com/elijah86j/hardhat-zksync/issues/1759)) ([4bc6993](https://github.com/elijah86j/hardhat-zksync/commit/4bc6993aa010f13e85a264a5844536b877130fbd))
* tests ([00d59fb](https://github.com/elijah86j/hardhat-zksync/commit/00d59fbf9308562ae5b8969a023cd13e5006e432))
* tests ([9760ac1](https://github.com/elijah86j/hardhat-zksync/commit/9760ac10e097564be6f80494a3ba301e1f90aba9))
* tests ([79d83cd](https://github.com/elijah86j/hardhat-zksync/commit/79d83cd45d48fb80de88f770c181d6c0319433a6))
* update links to new doc site ([8083a9e](https://github.com/elijah86j/hardhat-zksync/commit/8083a9eea3322f01503d2c261470351032f47657))
* update naming from era_test_node to anvil-zksync ([613eba1](https://github.com/elijah86j/hardhat-zksync/commit/613eba1ca166ddc481ae8cc84b574f8283a0f1e3))
* update naming from era_test_node to anvil-zksync ([8ea99ac](https://github.com/elijah86j/hardhat-zksync/commit/8ea99acb561cd6b66fef91b63b59492ebd601e79))
* update release url for anvil-zksync and era-test-node releases ([ceb3461](https://github.com/elijah86j/hardhat-zksync/commit/ceb3461ab1e8baef3c6869501f82d992be6590ce))

## [1.5.3](https://github.com/matter-labs/hardhat-zksync/compare/@matterlabs/hardhat-zksync-node-v1.5.2...@matterlabs/hardhat-zksync-node-v1.5.3) (2025-08-11)


### Bug Fixes

* noop commit to trigger release ([#1834](https://github.com/matter-labs/hardhat-zksync/issues/1834)) ([596f736](https://github.com/matter-labs/hardhat-zksync/commit/596f73688f1bf67fe30083e6197ad1bf2abda1c7))

## [1.5.2](https://github.com/matter-labs/hardhat-zksync/compare/@matterlabs/hardhat-zksync-node-v1.5.1...@matterlabs/hardhat-zksync-node-v1.5.2) (2025-06-23)


### Bug Fixes

* add offline mode to global and rename emulateEVM to corrected name ([8ac15f1](https://github.com/matter-labs/hardhat-zksync/commit/8ac15f19f9d7bcce1b76ce8dae6752ab3691fda2))

## [1.5.1](https://github.com/matter-labs/hardhat-zksync/compare/@matterlabs/hardhat-zksync-node-v1.5.0...@matterlabs/hardhat-zksync-node-v1.5.1) (2025-05-16)


### Bug Fixes

* rename silent param to quiet ([#1759](https://github.com/matter-labs/hardhat-zksync/issues/1759)) ([28fc526](https://github.com/matter-labs/hardhat-zksync/commit/28fc5262763158ee3fd350260163323eb5d1d84a))

## [1.5.0](https://github.com/matter-labs/hardhat-zksync/compare/@matterlabs/hardhat-zksync-node-v1.4.1...@matterlabs/hardhat-zksync-node-v1.5.0) (2025-05-12)


### Features

* bump anvil-zksync version and add new parameters ([#1709](https://github.com/matter-labs/hardhat-zksync/issues/1709)) ([99676f5](https://github.com/matter-labs/hardhat-zksync/commit/99676f533af5f0e07147242dfc5e30e19d29a33d))

## [1.4.1](https://github.com/matter-labs/hardhat-zksync/compare/@matterlabs/hardhat-zksync-node-v1.4.0...@matterlabs/hardhat-zksync-node-v1.4.1) (2025-05-09)


### Bug Fixes

* anvil-zksync bumped default version ([#1751](https://github.com/matter-labs/hardhat-zksync/issues/1751)) ([4279487](https://github.com/matter-labs/hardhat-zksync/commit/4279487f409e45ac8767d50cbf9644455d9be5cb))

## [1.4.0](https://github.com/matter-labs/hardhat-zksync/compare/@matterlabs/hardhat-zksync-node-v1.3.1...@matterlabs/hardhat-zksync-node-v1.4.0) (2025-03-25)


### Features

* add telemetry ([a345d09](https://github.com/matter-labs/hardhat-zksync/commit/a345d09e2150ac5b2b96b9e77edbe18dc0f3e7f4))

## [1.3.1](https://github.com/matter-labs/hardhat-zksync/compare/@matterlabs/hardhat-zksync-node-v1.3.0...@matterlabs/hardhat-zksync-node-v1.3.1) (2025-03-03)


### Bug Fixes

* add type extension to the index ([#1651](https://github.com/matter-labs/hardhat-zksync/issues/1651)) ([1304495](https://github.com/matter-labs/hardhat-zksync/commit/130449550c9096dee56015b12c59255d8a3cc390))
* create node cache directory with permissions ([#1642](https://github.com/matter-labs/hardhat-zksync/issues/1642)) ([8711e0e](https://github.com/matter-labs/hardhat-zksync/commit/8711e0e2eb3076abecaeb511f44877b258183e09))

## [1.3.0](https://github.com/matter-labs/hardhat-zksync/compare/@matterlabs/hardhat-zksync-node-v1.2.1...@matterlabs/hardhat-zksync-node-v1.3.0) (2025-02-24)


### Features

* set default version and handle github repo redirects ([#1577](https://github.com/matter-labs/hardhat-zksync/issues/1577)) ([fcf16d2](https://github.com/matter-labs/hardhat-zksync/commit/fcf16d21f67ed5212669ead7ae183adb155a1007))


### Bug Fixes

* apply anvil cli args with values ([291e80a](https://github.com/matter-labs/hardhat-zksync/commit/291e80a4bea49864840bebf602942e5a3a87978b))
* tests ([8a7d79c](https://github.com/matter-labs/hardhat-zksync/commit/8a7d79ce5483c3ed14a66dfc4dcc554d74e8c5f0))

## [1.2.1](https://github.com/matter-labs/hardhat-zksync/compare/@matterlabs/hardhat-zksync-node-v1.2.0...@matterlabs/hardhat-zksync-node-v1.2.1) (2024-12-10)


### Bug Fixes

* tests ([0e07b7e](https://github.com/matter-labs/hardhat-zksync/commit/0e07b7e0c8a26f2152229fc6f0efb4181b7dd3a4))
* update naming from era_test_node to anvil-zksync ([6bfb1c2](https://github.com/matter-labs/hardhat-zksync/commit/6bfb1c26f8f01ecd1a3095d97b7858dfef8bb06a))
* update naming from era_test_node to anvil-zksync ([d484fdd](https://github.com/matter-labs/hardhat-zksync/commit/d484fdda713d9c246c4a4639b6d6af84f63ceb15))
* update release url for anvil-zksync and era-test-node releases ([b57b9cc](https://github.com/matter-labs/hardhat-zksync/commit/b57b9cc3ab1e638901901120b91761666b8761af))

## [1.2.0](https://github.com/matter-labs/hardhat-zksync/compare/@matterlabs/hardhat-zksync-node-v1.1.1...@matterlabs/hardhat-zksync-node-v1.2.0) (2024-10-24)


### Features

* override run task for zksync hardhat network ([#1462](https://github.com/matter-labs/hardhat-zksync/issues/1462)) ([a49c593](https://github.com/matter-labs/hardhat-zksync/commit/a49c5932abcb7e5244314471c9b7f701c1c90a20))


### Bug Fixes

* update links to new doc site ([276740b](https://github.com/matter-labs/hardhat-zksync/commit/276740ba5abf8b5775e135b5653824d6456a7e4f))

## [1.1.1](https://github.com/matter-labs/hardhat-zksync/compare/@matterlabs/hardhat-zksync-node-v1.1.0...@matterlabs/hardhat-zksync-node-v1.1.1) (2024-07-15)


### Bug Fixes

* remove zksync-ethers dependency  ([#920](https://github.com/matter-labs/hardhat-zksync/issues/920)) ([d4a1ac8](https://github.com/matter-labs/hardhat-zksync/commit/d4a1ac80727d9de38460373cd07245ba2b747eea))

## [1.1.0](https://github.com/matter-labs/hardhat-zksync/compare/@matterlabs/hardhat-zksync-node-v1.0.3...@matterlabs/hardhat-zksync-node-v1.1.0) (2024-06-19)


### Features

* bump ethers, zksync-ethers, hardaht and other dependencies to newer versions ([#1111](https://github.com/matter-labs/hardhat-zksync/issues/1111)) ([a2d503a](https://github.com/matter-labs/hardhat-zksync/commit/a2d503abe3f504859651f22998046576eddf6579))
* switch to the default codegen with zksolc ([#1062](https://github.com/matter-labs/hardhat-zksync/issues/1062)) ([5ec997a](https://github.com/matter-labs/hardhat-zksync/commit/5ec997aaa83ba18d978f10b96f489513f6c4dd9f))

## [1.0.3](https://github.com/matter-labs/hardhat-zksync/compare/@matterlabs/hardhat-zksync-node@1.0.2...@matterlabs/hardhat-zksync-node-v1.0.3) (2024-03-21)


### Bug Fixes

* properly constructor fork arguments ([#927](https://github.com/matter-labs/hardhat-zksync/issues/927)) ([bfe8970](https://github.com/matter-labs/hardhat-zksync/commit/bfe897019bae72abd1ae0f3d6f69c2c4bb6038cd))

## [1.0.2](https://github.com/matter-labs/hardhat-zksync/compare/@matterlabs/hardhat-zksync-node-v1.0.1...@matterlabs/hardhat-zksync-node-v1.0.2) (2024-02-01)


### Bug Fixes

* get release tag from redirect url at node plugin ([#668](https://github.com/matter-labs/hardhat-zksync/issues/668)) ([5d53b27](https://github.com/matter-labs/hardhat-zksync/commit/5d53b270428fc3bd7a6338d0bab38a7f52d485d1))

## [1.0.1](https://github.com/matter-labs/hardhat-zksync/compare/@matterlabs/hardhat-zksync-node@1.0.0...@matterlabs/hardhat-zksync-node-v1.0.1) (2023-12-22)


### Fixes

* **docs:** update readme files ([#612](https://github.com/matter-labs/hardhat-zksync/issues/612)) ([682338e](https://github.com/matter-labs/hardhat-zksync/commit/682338e60f52021206325ff6eeec2c394a118642))

## 1.0.0

### Major Changes

- f216797: Migration from zksync2-js to zksync-ethers
