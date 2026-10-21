:robot: I have created a release *beep* *boop*
---


<details><summary>cargo-enshwick: 0.10.0</summary>

## [0.10.0](https://github.com/themaiby/enshwick/compare/cargo-enshwick-v0.9.1...cargo-enshwick-v0.10.0) (2026-10-21)


###   BREAKING CHANGES

* **api:** name mod content mod:name and derive its GUIDs
* **api:** name, describe and credit mods, with recommends and breaks ([#126](https://github.com/themaiby/enshwick/issues/126))
* **api:** config stages, ranges, choices, schema and /config ([#130](https://github.com/themaiby/enshwick/issues/130))
* consolidate into Enshwick Loader, one API crate and one tool ([#85](https://github.com/themaiby/enshwick/issues/85))

### Features

* **api:** config stages, ranges, choices, schema and /config ([#130](https://github.com/themaiby/enshwick/issues/130)) ([8a19e89](https://github.com/themaiby/enshwick/commit/8a19e89afe6ac74d09d9a32c66b1fc133e81bc68))
* **api:** name mod content mod:name and derive its GUIDs ([38f46ce](https://github.com/themaiby/enshwick/commit/38f46ce596e9fa6c25c0d673558ee56887160bfb))
* **api:** name vanilla content in packs by debug name ([#193](https://github.com/themaiby/enshwick/issues/193)) ([033fda9](https://github.com/themaiby/enshwick/commit/033fda9c6fa7f616c780d690e1b5758550a086de))
* **api:** name, describe and credit mods, with recommends and breaks ([#126](https://github.com/themaiby/enshwick/issues/126)) ([edfb07c](https://github.com/themaiby/enshwick/commit/edfb07c59676c441f1e8b06ddc2791a80594ae6c))
* **api:** skill, comfort and experience hooks in the platform ([#100](https://github.com/themaiby/enshwick/issues/100)) ([c810a02](https://github.com/themaiby/enshwick/commit/c810a02a60d5d05b8872bf8628afc27123868aa1))
* author keys: updates must be signed by the installed version's key ([#81](https://github.com/themaiby/enshwick/issues/81)) ([d9d46f3](https://github.com/themaiby/enshwick/commit/d9d46f38231234e958a8762e6c0fff5b6ddcb5d8))
* cargo enshwick, to start a mod and install it into the game ([#38](https://github.com/themaiby/enshwick/issues/38)) ([58ea01c](https://github.com/themaiby/enshwick/commit/58ea01cca185612ab188783dc7035a580e41f031))
* **cargo-enshwick:** report what works on a game build with compat ([#162](https://github.com/themaiby/enshwick/issues/162)) ([4bc3978](https://github.com/themaiby/enshwick/commit/4bc3978461c7f72bb07421bd2c96ad9fe6213e28))
* **loader:** add content packs of TOML files, signed and reloadable ([#158](https://github.com/themaiby/enshwick/issues/158)) ([7598b97](https://github.com/themaiby/enshwick/commit/7598b977434dfb207cd5c0d30c6cdd936c0cb0cc))
* **loader:** never start a mod that a renamed mod replaces ([#166](https://github.com/themaiby/enshwick/issues/166)) ([650993c](https://github.com/themaiby/enshwick/commit/650993c7b392be07fc16c4ca47925952c64f1487))
* **loader:** ship build tables as signed data with a pattern fallback ([#155](https://github.com/themaiby/enshwick/issues/155)) ([1df2e3f](https://github.com/themaiby/enshwick/commit/1df2e3fdcaeaeac3ca082a18976e6a3f1d3a46c9))
* name mod versions everywhere, checked at release ([#42](https://github.com/themaiby/enshwick/issues/42)) ([5dc88e3](https://github.com/themaiby/enshwick/commit/5dc88e3a296565b1691d3d54be726540a2255fc8))


### Bug Fixes

* **api:** audit the modder API for soundness, ABI and reuse ([#95](https://github.com/themaiby/enshwick/issues/95)) ([d800142](https://github.com/themaiby/enshwick/commit/d800142991a2d93aaf943af9f6e5cc629fa54d68))


### Other

* consolidate into Enshwick Loader, one API crate and one tool ([#85](https://github.com/themaiby/enshwick/issues/85)) ([5ddfde4](https://github.com/themaiby/enshwick/commit/5ddfde457d24f8e000d2dee1c74508f89582d526))


### Dependencies

* The following workspace dependencies were updated
  * dependencies
    * enshwick-loader bumped from 0.9.1 to 0.10.0
</details>

<details><summary>enshwick-admin-tools: 0.5.0</summary>

## [0.5.0](https://github.com/themaiby/enshwick/compare/enshwick-admin-tools-v0.4.7...enshwick-admin-tools-v0.5.0) (2026-10-21)


###   BREAKING CHANGES

* **api:** name, describe and credit mods, with recommends and breaks ([#126](https://github.com/themaiby/enshwick/issues/126))
* **api:** config stages, ranges, choices, schema and /config ([#130](https://github.com/themaiby/enshwick/issues/130))
* **api:** one naming scheme, run-time errors and named abi values ([#110](https://github.com/themaiby/enshwick/issues/110))
* consolidate into Enshwick Loader, one API crate and one tool ([#85](https://github.com/themaiby/enshwick/issues/85))

### Features

* **api:** config stages, ranges, choices, schema and /config ([#130](https://github.com/themaiby/enshwick/issues/130)) ([8a19e89](https://github.com/themaiby/enshwick/commit/8a19e89afe6ac74d09d9a32c66b1fc133e81bc68))
* **api:** name, describe and credit mods, with recommends and breaks ([#126](https://github.com/themaiby/enshwick/issues/126)) ([edfb07c](https://github.com/themaiby/enshwick/commit/edfb07c59676c441f1e8b06ddc2791a80594ae6c))
* **loader:** never start a mod that a renamed mod replaces ([#166](https://github.com/themaiby/enshwick/issues/166)) ([650993c](https://github.com/themaiby/enshwick/commit/650993c7b392be07fc16c4ca47925952c64f1487))


### Bug Fixes

* **admin-tools:** run no file line twice and forget a game's pieces ([#219](https://github.com/themaiby/enshwick/issues/219)) ([bbcd15e](https://github.com/themaiby/enshwick/commit/bbcd15ef95bbd79a587f2f01d48133a63df6b86b))
* **api:** audit the modder API for soundness, ABI and reuse ([#95](https://github.com/themaiby/enshwick/issues/95)) ([d800142](https://github.com/themaiby/enshwick/commit/d800142991a2d93aaf943af9f6e5cc629fa54d68))
* **mods:** audit fixes across every mod ([#94](https://github.com/themaiby/enshwick/issues/94)) ([e83b2d6](https://github.com/themaiby/enshwick/commit/e83b2d6d9f788f3cf9cc60d32fdcdb95196b76d4))


### Other

* **api:** one naming scheme, run-time errors and named abi values ([#110](https://github.com/themaiby/enshwick/issues/110)) ([cbe72c5](https://github.com/themaiby/enshwick/commit/cbe72c5e92104d374272a5b192272e6e276dd37b))
* consolidate into Enshwick Loader, one API crate and one tool ([#85](https://github.com/themaiby/enshwick/issues/85)) ([5ddfde4](https://github.com/themaiby/enshwick/commit/5ddfde457d24f8e000d2dee1c74508f89582d526))
</details>

<details><summary>enshwick-area-loot: 0.5.0</summary>

## [0.5.0](https://github.com/themaiby/enshwick/compare/enshwick-area-loot-v0.4.7...enshwick-area-loot-v0.5.0) (2026-10-21)


###   BREAKING CHANGES

* **api:** name, describe and credit mods, with recommends and breaks ([#126](https://github.com/themaiby/enshwick/issues/126))
* **api:** config stages, ranges, choices, schema and /config ([#130](https://github.com/themaiby/enshwick/issues/130))
* **api:** one naming scheme, run-time errors and named abi values ([#110](https://github.com/themaiby/enshwick/issues/110))
* consolidate into Enshwick Loader, one API crate and one tool ([#85](https://github.com/themaiby/enshwick/issues/85))

### Features

* **api:** a safe loot pass over each container check ([#102](https://github.com/themaiby/enshwick/issues/102)) ([150d611](https://github.com/themaiby/enshwick/commit/150d6116326741ab0855759251f3ee25b053858b))
* **api:** config stages, ranges, choices, schema and /config ([#130](https://github.com/themaiby/enshwick/issues/130)) ([8a19e89](https://github.com/themaiby/enshwick/commit/8a19e89afe6ac74d09d9a32c66b1fc133e81bc68))
* **api:** name, describe and credit mods, with recommends and breaks ([#126](https://github.com/themaiby/enshwick/issues/126)) ([edfb07c](https://github.com/themaiby/enshwick/commit/edfb07c59676c441f1e8b06ddc2791a80594ae6c))
* **area-loot:** take the enemy loot around an emptied corpse ([#70](https://github.com/themaiby/enshwick/issues/70)) ([859ae89](https://github.com/themaiby/enshwick/commit/859ae89edeafe6e4d85bba180dea6b8709669af4))
* author keys: updates must be signed by the installed version's key ([#81](https://github.com/themaiby/enshwick/issues/81)) ([d9d46f3](https://github.com/themaiby/enshwick/commit/d9d46f38231234e958a8762e6c0fff5b6ddcb5d8))


### Bug Fixes

* **mods:** audit fixes across every mod ([#94](https://github.com/themaiby/enshwick/issues/94)) ([e83b2d6](https://github.com/themaiby/enshwick/commit/e83b2d6d9f788f3cf9cc60d32fdcdb95196b76d4))


### Other

* **api:** one naming scheme, run-time errors and named abi values ([#110](https://github.com/themaiby/enshwick/issues/110)) ([cbe72c5](https://github.com/themaiby/enshwick/commit/cbe72c5e92104d374272a5b192272e6e276dd37b))
* consolidate into Enshwick Loader, one API crate and one tool ([#85](https://github.com/themaiby/enshwick/issues/85)) ([5ddfde4](https://github.com/themaiby/enshwick/commit/5ddfde457d24f8e000d2dee1c74508f89582d526))
</details>

<details><summary>enshwick-build-camera: 0.5.0</summary>

## [0.5.0](https://github.com/themaiby/enshwick/compare/enshwick-build-camera-v0.4.7...enshwick-build-camera-v0.5.0) (2026-10-21)


###   BREAKING CHANGES

* **api:** name, describe and credit mods, with recommends and breaks ([#126](https://github.com/themaiby/enshwick/issues/126))
* **api:** one naming scheme, run-time errors and named abi values ([#110](https://github.com/themaiby/enshwick/issues/110))
* consolidate into Enshwick Loader, one API crate and one tool ([#85](https://github.com/themaiby/enshwick/issues/85))

### Features

* **api:** name, describe and credit mods, with recommends and breaks ([#126](https://github.com/themaiby/enshwick/issues/126)) ([edfb07c](https://github.com/themaiby/enshwick/commit/edfb07c59676c441f1e8b06ddc2791a80594ae6c))
* **api:** skill, comfort and experience hooks in the platform ([#100](https://github.com/themaiby/enshwick/issues/100)) ([c810a02](https://github.com/themaiby/enshwick/commit/c810a02a60d5d05b8872bf8628afc27123868aa1))
* author keys: updates must be signed by the installed version's key ([#81](https://github.com/themaiby/enshwick/issues/81)) ([d9d46f3](https://github.com/themaiby/enshwick/commit/d9d46f38231234e958a8762e6c0fff5b6ddcb5d8))
* build-camera mod opens the building fly mode to every player ([#66](https://github.com/themaiby/enshwick/issues/66)) ([29b1ef9](https://github.com/themaiby/enshwick/commit/29b1ef9275480af172f683f0b241ddf2874b28c5))


### Bug Fixes

* **mods:** audit fixes across every mod ([#94](https://github.com/themaiby/enshwick/issues/94)) ([e83b2d6](https://github.com/themaiby/enshwick/commit/e83b2d6d9f788f3cf9cc60d32fdcdb95196b76d4))


### Other

* **api:** one naming scheme, run-time errors and named abi values ([#110](https://github.com/themaiby/enshwick/issues/110)) ([cbe72c5](https://github.com/themaiby/enshwick/commit/cbe72c5e92104d374272a5b192272e6e276dd37b))
* consolidate into Enshwick Loader, one API crate and one tool ([#85](https://github.com/themaiby/enshwick/issues/85)) ([5ddfde4](https://github.com/themaiby/enshwick/commit/5ddfde457d24f8e000d2dee1c74508f89582d526))
</details>

<details><summary>enshwick-building-materials: 0.5.0</summary>

## [0.5.0](https://github.com/themaiby/enshwick/compare/enshwick-building-materials-v0.4.7...enshwick-building-materials-v0.5.0) (2026-10-21)


###   BREAKING CHANGES

* **api:** name, describe and credit mods, with recommends and breaks ([#126](https://github.com/themaiby/enshwick/issues/126))
* **api:** config stages, ranges, choices, schema and /config ([#130](https://github.com/themaiby/enshwick/issues/130))
* consolidate into Enshwick Loader, one API crate and one tool ([#85](https://github.com/themaiby/enshwick/issues/85))
* building materials x2 doubles vanilla building recipe outputs ([#82](https://github.com/themaiby/enshwick/issues/82))

### Features

* **api:** config stages, ranges, choices, schema and /config ([#130](https://github.com/themaiby/enshwick/issues/130)) ([8a19e89](https://github.com/themaiby/enshwick/commit/8a19e89afe6ac74d09d9a32c66b1fc133e81bc68))
* **api:** name, describe and credit mods, with recommends and breaks ([#126](https://github.com/themaiby/enshwick/issues/126)) ([edfb07c](https://github.com/themaiby/enshwick/commit/edfb07c59676c441f1e8b06ddc2791a80594ae6c))
* building materials x2 doubles vanilla building recipe outputs ([#82](https://github.com/themaiby/enshwick/issues/82)) ([5f6ee1f](https://github.com/themaiby/enshwick/commit/5f6ee1ff583a7bbddaf580e6f0c764e47558ba85))
* **loader:** never start a mod that a renamed mod replaces ([#166](https://github.com/themaiby/enshwick/issues/166)) ([650993c](https://github.com/themaiby/enshwick/commit/650993c7b392be07fc16c4ca47925952c64f1487))


### Bug Fixes

* **mods:** audit fixes across every mod ([#94](https://github.com/themaiby/enshwick/issues/94)) ([e83b2d6](https://github.com/themaiby/enshwick/commit/e83b2d6d9f788f3cf9cc60d32fdcdb95196b76d4))


### Other

* consolidate into Enshwick Loader, one API crate and one tool ([#85](https://github.com/themaiby/enshwick/issues/85)) ([5ddfde4](https://github.com/themaiby/enshwick/commit/5ddfde457d24f8e000d2dee1c74508f89582d526))
</details>

<details><summary>enshwick-example-hot-reload: 0.1.6</summary>

### Dependencies


</details>

<details><summary>enshwick-example-market-stalls: 0.1.8</summary>

### Dependencies

* The following workspace dependencies were updated
  * dependencies
    * enshwick-example-trading-post-api bumped from 0.1.7 to 0.1.8
</details>

<details><summary>enshwick-example-trading-post: 0.1.8</summary>

### Dependencies

* The following workspace dependencies were updated
  * dependencies
    * enshwick-example-trading-post-api bumped from 0.1.7 to 0.1.8
</details>

<details><summary>enshwick-example-trading-post-api: 0.1.8</summary>

### Dependencies


</details>

<details><summary>enshwick-flame-altar-count: 0.5.0</summary>

## [0.5.0](https://github.com/themaiby/enshwick/compare/enshwick-flame-altar-count-v0.4.7...enshwick-flame-altar-count-v0.5.0) (2026-10-21)


###   BREAKING CHANGES

* **api:** name, describe and credit mods, with recommends and breaks ([#126](https://github.com/themaiby/enshwick/issues/126))
* **api:** config stages, ranges, choices, schema and /config ([#130](https://github.com/themaiby/enshwick/issues/130))
* **api:** one naming scheme, run-time errors and named abi values ([#110](https://github.com/themaiby/enshwick/issues/110))
* consolidate into Enshwick Loader, one API crate and one tool ([#85](https://github.com/themaiby/enshwick/issues/85))

### Features

* **api:** altar limit and bases past 16 zones in the platform ([#101](https://github.com/themaiby/enshwick/issues/101)) ([a8e5ca9](https://github.com/themaiby/enshwick/commit/a8e5ca9bafc6321d70c81f2bc1458e34a1ec8175))
* **api:** config stages, ranges, choices, schema and /config ([#130](https://github.com/themaiby/enshwick/issues/130)) ([8a19e89](https://github.com/themaiby/enshwick/commit/8a19e89afe6ac74d09d9a32c66b1fc133e81bc68))
* **api:** name, describe and credit mods, with recommends and breaks ([#126](https://github.com/themaiby/enshwick/issues/126)) ([edfb07c](https://github.com/themaiby/enshwick/commit/edfb07c59676c441f1e8b06ddc2791a80594ae6c))
* author keys: updates must be signed by the installed version's key ([#81](https://github.com/themaiby/enshwick/issues/81)) ([d9d46f3](https://github.com/themaiby/enshwick/commit/d9d46f38231234e958a8762e6c0fff5b6ddcb5d8))
* **flame-altar-count:** 32 altars in at most 16 bases ([#72](https://github.com/themaiby/enshwick/issues/72)) ([ecb0804](https://github.com/themaiby/enshwick/commit/ecb0804fe1d2ac636a56b739f6e9c971fca75b7d))
* join values: #[config(sync)] settings follow the server ([#59](https://github.com/themaiby/enshwick/issues/59)) ([7ff7bfe](https://github.com/themaiby/enshwick/commit/7ff7bfee8ab685d76ead9d211e5c57048d44e160))
* update sources in manifests and staged updates in the stub ([#57](https://github.com/themaiby/enshwick/issues/57)) ([20e72b1](https://github.com/themaiby/enshwick/commit/20e72b1025765d83f3da861ec46ccbb4a163443c))


### Bug Fixes

* **api:** audit the modder API for soundness, ABI and reuse ([#95](https://github.com/themaiby/enshwick/issues/95)) ([d800142](https://github.com/themaiby/enshwick/commit/d800142991a2d93aaf943af9f6e5cc629fa54d68))
* build the docs without rustdoc link errors ([#87](https://github.com/themaiby/enshwick/issues/87)) ([57b02cf](https://github.com/themaiby/enshwick/commit/57b02cf899cf0a0bfc97633ea47339e630f0c0e5))
* **mods:** audit fixes across every mod ([#94](https://github.com/themaiby/enshwick/issues/94)) ([e83b2d6](https://github.com/themaiby/enshwick/commit/e83b2d6d9f788f3cf9cc60d32fdcdb95196b76d4))


### Other

* **api:** one naming scheme, run-time errors and named abi values ([#110](https://github.com/themaiby/enshwick/issues/110)) ([cbe72c5](https://github.com/themaiby/enshwick/commit/cbe72c5e92104d374272a5b192272e6e276dd37b))
* consolidate into Enshwick Loader, one API crate and one tool ([#85](https://github.com/themaiby/enshwick/issues/85)) ([5ddfde4](https://github.com/themaiby/enshwick/commit/5ddfde457d24f8e000d2dee1c74508f89582d526))
</details>

<details><summary>enshwick-flame-altar-zones: 0.5.0</summary>

## [0.5.0](https://github.com/themaiby/enshwick/compare/enshwick-flame-altar-zones-v0.4.7...enshwick-flame-altar-zones-v0.5.0) (2026-10-21)


###   BREAKING CHANGES

* **api:** name, describe and credit mods, with recommends and breaks ([#126](https://github.com/themaiby/enshwick/issues/126))
* **api:** config stages, ranges, choices, schema and /config ([#130](https://github.com/themaiby/enshwick/issues/130))
* **api:** one naming scheme, run-time errors and named abi values ([#110](https://github.com/themaiby/enshwick/issues/110))
* consolidate into Enshwick Loader, one API crate and one tool ([#85](https://github.com/themaiby/enshwick/issues/85))

### Features

* **api:** altar zones and bases in the platform ([#97](https://github.com/themaiby/enshwick/issues/97)) ([e45cc7b](https://github.com/themaiby/enshwick/commit/e45cc7b58c6d82db2affa56b4fbfa89bd4fc3824))
* **api:** config stages, ranges, choices, schema and /config ([#130](https://github.com/themaiby/enshwick/issues/130)) ([8a19e89](https://github.com/themaiby/enshwick/commit/8a19e89afe6ac74d09d9a32c66b1fc133e81bc68))
* **api:** name, describe and credit mods, with recommends and breaks ([#126](https://github.com/themaiby/enshwick/issues/126)) ([edfb07c](https://github.com/themaiby/enshwick/commit/edfb07c59676c441f1e8b06ddc2791a80594ae6c))
* author keys: updates must be signed by the installed version's key ([#81](https://github.com/themaiby/enshwick/issues/81)) ([d9d46f3](https://github.com/themaiby/enshwick/commit/d9d46f38231234e958a8762e6c0fff5b6ddcb5d8))
* **enshwick-flame-altar-zones:** clusters, growth and seams ([#10](https://github.com/themaiby/enshwick/issues/10)) ([d3f907a](https://github.com/themaiby/enshwick/commit/d3f907a997901702c33dcb29d11491391f89ad17))
* run server mods in games the client hosts ([#61](https://github.com/themaiby/enshwick/issues/61)) ([4c6fe26](https://github.com/themaiby/enshwick/commit/4c6fe269e6137bba6e7190907929fa1b11033744))
* update sources in manifests and staged updates in the stub ([#57](https://github.com/themaiby/enshwick/issues/57)) ([20e72b1](https://github.com/themaiby/enshwick/commit/20e72b1025765d83f3da861ec46ccbb4a163443c))


### Bug Fixes

* **api:** audit the modder API for soundness, ABI and reuse ([#95](https://github.com/themaiby/enshwick/issues/95)) ([d800142](https://github.com/themaiby/enshwick/commit/d800142991a2d93aaf943af9f6e5cc629fa54d68))
* **flame-altar-zones:** sync building_across_seams ([#177](https://github.com/themaiby/enshwick/issues/177)) ([ab85310](https://github.com/themaiby/enshwick/commit/ab85310d8ef64b04d061aed80a87f2e3ad38b174))
* **mods:** audit fixes across every mod ([#94](https://github.com/themaiby/enshwick/issues/94)) ([e83b2d6](https://github.com/themaiby/enshwick/commit/e83b2d6d9f788f3cf9cc60d32fdcdb95196b76d4))


### Other

* **api:** one naming scheme, run-time errors and named abi values ([#110](https://github.com/themaiby/enshwick/issues/110)) ([cbe72c5](https://github.com/themaiby/enshwick/commit/cbe72c5e92104d374272a5b192272e6e276dd37b))
* consolidate into Enshwick Loader, one API crate and one tool ([#85](https://github.com/themaiby/enshwick/issues/85)) ([5ddfde4](https://github.com/themaiby/enshwick/commit/5ddfde457d24f8e000d2dee1c74508f89582d526))
</details>

<details><summary>enshwick-furniture-comfort: 0.4.0</summary>

## [0.4.0](https://github.com/themaiby/enshwick/compare/enshwick-furniture-comfort-v0.3.7...enshwick-furniture-comfort-v0.4.0) (2026-10-21)


###   BREAKING CHANGES

* **api:** name, describe and credit mods, with recommends and breaks ([#126](https://github.com/themaiby/enshwick/issues/126))
* **api:** config stages, ranges, choices, schema and /config ([#130](https://github.com/themaiby/enshwick/issues/130))
* consolidate into Enshwick Loader, one API crate and one tool ([#85](https://github.com/themaiby/enshwick/issues/85))

### Features

* **api:** config stages, ranges, choices, schema and /config ([#130](https://github.com/themaiby/enshwick/issues/130)) ([8a19e89](https://github.com/themaiby/enshwick/commit/8a19e89afe6ac74d09d9a32c66b1fc133e81bc68))
* **api:** name, describe and credit mods, with recommends and breaks ([#126](https://github.com/themaiby/enshwick/issues/126)) ([edfb07c](https://github.com/themaiby/enshwick/commit/edfb07c59676c441f1e8b06ddc2791a80594ae6c))
* **api:** skill, comfort and experience hooks in the platform ([#100](https://github.com/themaiby/enshwick/issues/100)) ([c810a02](https://github.com/themaiby/enshwick/commit/c810a02a60d5d05b8872bf8628afc27123868aa1))
* author keys: updates must be signed by the installed version's key ([#81](https://github.com/themaiby/enshwick/issues/81)) ([d9d46f3](https://github.com/themaiby/enshwick/commit/d9d46f38231234e958a8762e6c0fff5b6ddcb5d8))
* **enshwick-furniture-comfort:** more comfort from furniture ([#22](https://github.com/themaiby/enshwick/issues/22)) ([d58094e](https://github.com/themaiby/enshwick/commit/d58094edce5df6851edb30b8cdfd84eb5b0ca3b9))
* events, with settings applied while the game runs ([#41](https://github.com/themaiby/enshwick/issues/41)) ([5eb9204](https://github.com/themaiby/enshwick/commit/5eb9204263da3410dcaeacb295dff33f14b87e80))
* run server mods in games the client hosts ([#61](https://github.com/themaiby/enshwick/issues/61)) ([4c6fe26](https://github.com/themaiby/enshwick/commit/4c6fe269e6137bba6e7190907929fa1b11033744))
* update sources in manifests and staged updates in the stub ([#57](https://github.com/themaiby/enshwick/issues/57)) ([20e72b1](https://github.com/themaiby/enshwick/commit/20e72b1025765d83f3da861ec46ccbb4a163443c))


### Bug Fixes

* **mods:** audit fixes across every mod ([#94](https://github.com/themaiby/enshwick/issues/94)) ([e83b2d6](https://github.com/themaiby/enshwick/commit/e83b2d6d9f788f3cf9cc60d32fdcdb95196b76d4))


### Other

* consolidate into Enshwick Loader, one API crate and one tool ([#85](https://github.com/themaiby/enshwick/issues/85)) ([5ddfde4](https://github.com/themaiby/enshwick/commit/5ddfde457d24f8e000d2dee1c74508f89582d526))
</details>

<details><summary>enshwick-loader: 0.10.0</summary>

## [0.10.0](https://github.com/themaiby/enshwick/compare/enshwick-loader-v0.9.1...enshwick-loader-v0.10.0) (2026-10-21)


###   BREAKING CHANGES

* **loader:** show only updates of installed mods on the Mods screen ([#196](https://github.com/themaiby/enshwick/issues/196))
* **optimizer:** rename and tune per platform for Windows and Proton ([#165](https://github.com/themaiby/enshwick/issues/165))
* **api:** name mod content mod:name and derive its GUIDs
* **api:** check service layouts and add typed mod events ([#146](https://github.com/themaiby/enshwick/issues/146))
* **loader:** mod settings per world ([#145](https://github.com/themaiby/enshwick/issues/145))
* **api:** name, describe and credit mods, with recommends and breaks ([#126](https://github.com/themaiby/enshwick/issues/126))
* **api:** config stages, ranges, choices, schema and /config ([#130](https://github.com/themaiby/enshwick/issues/130))
* **api:** one naming scheme, run-time errors and named abi values ([#110](https://github.com/themaiby/enshwick/issues/110))
* consolidate into Enshwick Loader, one API crate and one tool ([#85](https://github.com/themaiby/enshwick/issues/85))

### Features

* **api:** add stat kinds, modifiers and built-in stats ([#143](https://github.com/themaiby/enshwick/issues/143)) ([dabec8b](https://github.com/themaiby/enshwick/commit/dabec8b85843c33fd3b7a3d07b17271451e7b344))
* **api:** add, dig and flatten terrain, and list its materials ([#125](https://github.com/themaiby/enshwick/issues/125)) ([032b1c9](https://github.com/themaiby/enshwick/commit/032b1c99513dad768d2e380ee339c42ece53ec90))
* **api:** altar limit and bases past 16 zones in the platform ([#101](https://github.com/themaiby/enshwick/issues/101)) ([a8e5ca9](https://github.com/themaiby/enshwick/commit/a8e5ca9bafc6321d70c81f2bc1458e34a1ec8175))
* **api:** altar zones and bases in the platform ([#97](https://github.com/themaiby/enshwick/issues/97)) ([e45cc7b](https://github.com/themaiby/enshwick/commit/e45cc7b58c6d82db2affa56b4fbfa89bd4fc3824))
* **api:** attach typed data to single items ([#133](https://github.com/themaiby/enshwick/issues/133)) ([4d938a9](https://github.com/themaiby/enshwick/commit/4d938a9c457857c7da77066b6fe8c2ecbe6d5ea3))
* **api:** attach typed mod data to any entity, per world ([#161](https://github.com/themaiby/enshwick/issues/161)) ([b0fee70](https://github.com/themaiby/enshwick/commit/b0fee7049cf8c82f791a45716d3ff14d01267dd0))
* **api:** check service layouts and add typed mod events ([#146](https://github.com/themaiby/enshwick/issues/146)) ([aa701ce](https://github.com/themaiby/enshwick/commit/aa701cef773075939cb480dc1c01e91474883196))
* **api:** config stages, ranges, choices, schema and /config ([#130](https://github.com/themaiby/enshwick/issues/130)) ([8a19e89](https://github.com/themaiby/enshwick/commit/8a19e89afe6ac74d09d9a32c66b1fc133e81bc68))
* **api:** draw lines and bars on the HUD and markers on the map ([#134](https://github.com/themaiby/enshwick/issues/134)) ([11d05b3](https://github.com/themaiby/enshwick/commit/11d05b3701942738d3fa49d73726af363af9133b))
* **api:** draw with the game's own widgets and show its dialogs ([#129](https://github.com/themaiby/enshwick/issues/129)) ([8601c70](https://github.com/themaiby/enshwick/commit/8601c70f8a0678a50f41301467d713bf41fab855))
* **api:** engine events from the server's ECS event streams ([#104](https://github.com/themaiby/enshwick/issues/104)) ([73cdaaf](https://github.com/themaiby/enshwick/commit/73cdaafb179d62d9891cb614a3b03f3e3fc783fa))
* **api:** entity queries, destroy, saves and per-world stores ([#105](https://github.com/themaiby/enshwick/issues/105)) ([ffd6090](https://github.com/themaiby/enshwick/commit/ffd6090628a40bd416e19767fcdc89ef7faba853))
* **api:** filter damage by cause and type before it is applied ([#121](https://github.com/themaiby/enshwick/issues/121)) ([a349c50](https://github.com/themaiby/enshwick/commit/a349c50d002eaedafdf9d10873c740d76bdd7140))
* **api:** give items a meter, tooltip lines and fill on give ([#128](https://github.com/themaiby/enshwick/issues/128)) ([11beb9b](https://github.com/themaiby/enshwick/commit/11beb9b762be4d3d6b80cc81b2c3baffb2ab3131))
* **api:** give items icons of their own ([#142](https://github.com/themaiby/enshwick/issues/142)) ([a0c0228](https://github.com/themaiby/enshwick/commit/a0c02288e4c586fc21e01e8497e1fe2da2d7ce76))
* **api:** interaction filters for chests and placed pieces ([#99](https://github.com/themaiby/enshwick/issues/99)) ([7a47400](https://github.com/themaiby/enshwick/commit/7a47400e8c74afee1e1fcfde60bc32aae24ba6d7))
* **api:** list, give and remove buffs and debuffs ([#122](https://github.com/themaiby/enshwick/issues/122)) ([78a7b89](https://github.com/themaiby/enshwick/commit/78a7b89b2fbc3722600529f32f718f1d073bfee8))
* **api:** messages between a mod's server and client parts ([#116](https://github.com/themaiby/enshwick/issues/116)) ([671de20](https://github.com/themaiby/enshwick/commit/671de2003d7a7016131b39db81b59efda4bd732a))
* **api:** name mod content mod:name and derive its GUIDs ([38f46ce](https://github.com/themaiby/enshwick/commit/38f46ce596e9fa6c25c0d673558ee56887160bfb))
* **api:** name vanilla content in packs by debug name ([#193](https://github.com/themaiby/enshwick/issues/193)) ([033fda9](https://github.com/themaiby/enshwick/commit/033fda9c6fa7f616c780d690e1b5758550a086de))
* **api:** name, describe and credit mods, with recommends and breaks ([#126](https://github.com/themaiby/enshwick/issues/126)) ([edfb07c](https://github.com/themaiby/enshwick/commit/edfb07c59676c441f1e8b06ddc2791a80594ae6c))
* **api:** raise allowed game events and teleport entities ([#113](https://github.com/themaiby/enshwick/issues/113)) ([5a42ea6](https://github.com/themaiby/enshwick/commit/5a42ea670417aba93ad18fba57d36db1190de2d2))
* **api:** read and change the server's game settings ([#120](https://github.com/themaiby/enshwick/issues/120)) ([159227a](https://github.com/themaiby/enshwick/commit/159227a6d666999d4d1985b1920c590729055288))
* **api:** read and grant knowledge, quests and their events ([#123](https://github.com/themaiby/enshwick/issues/123)) ([0a656e5](https://github.com/themaiby/enshwick/commit/0a656e585e8c6575c1ff10089d413b2aea672d7b))
* **api:** read and set the time of day, its speed and day turns ([#119](https://github.com/themaiby/enshwick/issues/119)) ([b7505e6](https://github.com/themaiby/enshwick/commit/b7505e697beccf7fda0dfdb4db0b8220cf4e7f42))
* **api:** read and start weather, and report chunk loads ([#124](https://github.com/themaiby/enshwick/issues/124)) ([a36528f](https://github.com/themaiby/enshwick/commit/a36528f1d683b8446c175be2de7635a50f9033db))
* **api:** read the game's own texts and resources from its archive ([#191](https://github.com/themaiby/enshwick/issues/191)) ([ebaf029](https://github.com/themaiby/enshwick/commit/ebaf029db0cf95f6cb63602d6b0f617e8dc451e0))
* **api:** roll affixes onto items from loot, crafting or a mod ([#147](https://github.com/themaiby/enshwick/issues/147)) ([c40ab9b](https://github.com/themaiby/enshwick/commit/c40ab9be39b5e6fee00652aeb5c03117067ec340))
* **api:** run mod migrations once per world and record them ([#150](https://github.com/themaiby/enshwick/issues/150)) ([0bf89e9](https://github.com/themaiby/enshwick/commit/0bf89e9887a6518f26ab87caefba43149438b88c))
* **api:** show notices on a player's screen ([#117](https://github.com/themaiby/enshwick/issues/117)) ([b174549](https://github.com/themaiby/enshwick/commit/b174549819df1e5285b2b74b626732bf3599ee58))
* **api:** skill, comfort and experience hooks in the platform ([#100](https://github.com/themaiby/enshwick/issues/100)) ([c810a02](https://github.com/themaiby/enshwick/commit/c810a02a60d5d05b8872bf8628afc27123868aa1))
* **api:** spawn entities from templates ([#114](https://github.com/themaiby/enshwick/issues/114)) ([63b6e3f](https://github.com/themaiby/enshwick/commit/63b6e3f2da5d44ad05d0ccc0bcad34582469a64c))
* **api:** survivor lookups, beds, staffs and menu in the platform ([#103](https://github.com/themaiby/enshwick/issues/103)) ([166e1ba](https://github.com/themaiby/enshwick/commit/166e1ba837d789bbd9a36f9bab41e8530666d4ef))
* **api:** typed engine events, kill credit and character stats ([#106](https://github.com/themaiby/enshwick/issues/106)) ([99e1d93](https://github.com/themaiby/enshwick/commit/99e1d93ce64e899a9db5c5c872f199ac92bac6f4))
* **api:** veto crafting and building ([#115](https://github.com/themaiby/enshwick/issues/115)) ([7009d56](https://github.com/themaiby/enshwick/commit/7009d568e78eee315a6f8631df6463342e7b1fd2))
* **api:** write components marked changed, set health stamina mana ([#112](https://github.com/themaiby/enshwick/issues/112)) ([98a104f](https://github.com/themaiby/enshwick/commit/98a104fdc9eb06c525eabbcd73c286a039a5e211))
* **cargo-enshwick:** report what works on a game build with compat ([#162](https://github.com/themaiby/enshwick/issues/162)) ([4bc3978](https://github.com/themaiby/enshwick/commit/4bc3978461c7f72bb07421bd2c96ad9fe6213e28))
* **loader:** a Mods screen beside Settings with each mod's settings ([#137](https://github.com/themaiby/enshwick/issues/137)) ([45c2400](https://github.com/themaiby/enshwick/commit/45c240061c0d00578d7c9e28afe26755802316a6))
* **loader:** add content packs of TOML files, signed and reloadable ([#158](https://github.com/themaiby/enshwick/issues/158)) ([7598b97](https://github.com/themaiby/enshwick/commit/7598b977434dfb207cd5c0d30c6cdd936c0cb0cc))
* **loader:** blame crashes on mods only when they end the game ([#153](https://github.com/themaiby/enshwick/issues/153)) ([6b60e1b](https://github.com/themaiby/enshwick/commit/6b60e1bbf49a144eb28a106587a913c4272d051e))
* **loader:** filter drowning, freezing and admin kills ([#181](https://github.com/themaiby/enshwick/issues/181)) ([215297f](https://github.com/themaiby/enshwick/commit/215297f9059d2a21c0d741f34b014988bc5e0993))
* **loader:** keep game settings with the world ([#179](https://github.com/themaiby/enshwick/issues/179)) ([3a1d819](https://github.com/themaiby/enshwick/commit/3a1d819f5f4e34570ce1547b6b8e55368d74f664))
* **loader:** keep items of removed mods as stand-ins until they return ([#184](https://github.com/themaiby/enshwick/issues/184)) ([6c5c09d](https://github.com/themaiby/enshwick/commit/6c5c09d3c624f07b61fdcb76b5f1b0c301aff348))
* **loader:** label mods' settings in the player's language ([#141](https://github.com/themaiby/enshwick/issues/141)) ([0cbc46f](https://github.com/themaiby/enshwick/commit/0cbc46fd311d1bc187b9c89236e10d83a429b27a))
* **loader:** mod settings per world ([#145](https://github.com/themaiby/enshwick/issues/145)) ([c06612b](https://github.com/themaiby/enshwick/commit/c06612bf26b00d4cd6175fd4dac343bb637a5ccc))
* **loader:** mods' settings in the world settings for hosts ([#139](https://github.com/themaiby/enshwick/issues/139)) ([b4c4137](https://github.com/themaiby/enshwick/commit/b4c4137f41c0a3371f5e7698b2084c7dd2b5d47d))
* **loader:** name the killer entity of a player killed by a hit ([#202](https://github.com/themaiby/enshwick/issues/202)) ([c81f863](https://github.com/themaiby/enshwick/commit/c81f8630e192ec6dceba4c395c4639aafea27e7b))
* **loader:** never start a mod that a renamed mod replaces ([#166](https://github.com/themaiby/enshwick/issues/166)) ([650993c](https://github.com/themaiby/enshwick/commit/650993c7b392be07fc16c4ca47925952c64f1487))
* **loader:** open every interface widget with /enshwick ui-demo ([#132](https://github.com/themaiby/enshwick/issues/132)) ([324aa82](https://github.com/themaiby/enshwick/commit/324aa825336c0f422b0625a3ebdc48af98483b64))
* **loader:** profile each mod's costs and report where mods meet ([#152](https://github.com/themaiby/enshwick/issues/152)) ([9c2c39a](https://github.com/themaiby/enshwick/commit/9c2c39a238d0d632e64b4c7ec1cd794588826bdb))
* **loader:** push changed join values and edit server settings remotely ([#138](https://github.com/themaiby/enshwick/issues/138)) ([58bba7c](https://github.com/themaiby/enshwick/commit/58bba7c378f92d5bf832d1f82aa09626591a2899))
* **loader:** read recent log lines in chat with /enshwick log ([#167](https://github.com/themaiby/enshwick/issues/167)) ([24e1aa0](https://github.com/themaiby/enshwick/commit/24e1aa01b41cf813a646a5998df61735de299b68))
* **loader:** refuse knowledge a client grants itself ([#173](https://github.com/themaiby/enshwick/issues/173)) ([a6c2ee7](https://github.com/themaiby/enshwick/commit/a6c2ee7376ec8166b0aa7de9b5cda90b7c28fafa))
* **loader:** reload changed mods on a development client ([#194](https://github.com/themaiby/enshwick/issues/194)) ([0b7618e](https://github.com/themaiby/enshwick/commit/0b7618e741b7a23405a1444dba6a6009f1f76531))
* **loader:** reload mods while a development server runs ([#164](https://github.com/themaiby/enshwick/issues/164)) ([16494a1](https://github.com/themaiby/enshwick/commit/16494a1f52b8c473876b6af9ce014f93a71afbc0))
* **loader:** report player deaths and read the shroud timer ([#185](https://github.com/themaiby/enshwick/issues/185)) ([9bcd23c](https://github.com/themaiby/enshwick/commit/9bcd23c64665aeb814bf0bc08109ce48ec62eeed))
* **loader:** ship build tables as signed data with a pattern fallback ([#155](https://github.com/themaiby/enshwick/issues/155)) ([1df2e3f](https://github.com/themaiby/enshwick/commit/1df2e3fdcaeaeac3ca082a18976e6a3f1d3a46c9))
* **loader:** show mod catalogs with updates and mods on the Mods screen ([#180](https://github.com/themaiby/enshwick/issues/180)) ([2e93fb7](https://github.com/themaiby/enshwick/commit/2e93fb7ec219b7c4b4fcab0ff45dcd4c409340d6))
* **loader:** show only updates of installed mods on the Mods screen ([#196](https://github.com/themaiby/enshwick/issues/196)) ([aee82ac](https://github.com/themaiby/enshwick/commit/aee82acb3a6a0f9d8aa2ebbe414a7a31961c1cd7))
* **loader:** take knowledge back and change it for absent players ([#183](https://github.com/themaiby/enshwick/issues/183)) ([13e4883](https://github.com/themaiby/enshwick/commit/13e4883e75df99ecd6101754608161c87c39633d))
* **loader:** translate chat replies and settings refusals ([#205](https://github.com/themaiby/enshwick/issues/205)) ([c041636](https://github.com/themaiby/enshwick/commit/c04163673fadcf012b3573f1e5d342b2b0947aef))
* **loader:** turn mods off in mods.toml and record the set in a lock ([#127](https://github.com/themaiby/enshwick/issues/127)) ([f2e7dad](https://github.com/themaiby/enshwick/commit/f2e7dadffcb3877524ed86dc380cef1b6cfe7a59))
* **loader:** watch knowledge requests by default before refusing them ([#190](https://github.com/themaiby/enshwick/issues/190)) ([ba2efcd](https://github.com/themaiby/enshwick/commit/ba2efcd87974e62d758b6c9a85fef53f46d2f026))
* **loader:** word the Mods screen in the game language ([#189](https://github.com/themaiby/enshwick/issues/189)) ([b23066b](https://github.com/themaiby/enshwick/commit/b23066b6937c963cbc8ae0a235976b651764b554))
* **survivors-per-altar:** copies come only from copy staffs ([#140](https://github.com/themaiby/enshwick/issues/140)) ([ab540fb](https://github.com/themaiby/enshwick/commit/ab540fb687900e7350f452f3403d4bebabd9f919))
* **updater:** page through releases, word dialogs in the game language ([#170](https://github.com/themaiby/enshwick/issues/170)) ([c6bd27a](https://github.com/themaiby/enshwick/commit/c6bd27a947073a2e4a40dc822f2e3f64606c20a4))


### Bug Fixes

* **loader:** audit fixes for arming, events and logging ([#91](https://github.com/themaiby/enshwick/issues/91)) ([8dbb83e](https://github.com/themaiby/enshwick/commit/8dbb83e9d5ba67f5806302b19ac794926fa02a16))
* **loader:** close crash paths found in the loader audit ([#182](https://github.com/themaiby/enshwick/issues/182)) ([7e4fab8](https://github.com/themaiby/enshwick/commit/7e4fab8a0b70efe438d43b6d9649af97c112e9cb))
* **loader:** forget altars by steps and time, the last one too ([#172](https://github.com/themaiby/enshwick/issues/172)) ([77e90d5](https://github.com/themaiby/enshwick/commit/77e90d5383af513c04a54076c8a8844597ce8b5e))
* **loader:** harden hook writes, chain wiring and the zmm check ([#216](https://github.com/themaiby/enshwick/issues/216)) ([2169e1d](https://github.com/themaiby/enshwick/commit/2169e1d1d5b3d0bb73e55545c18415bb4dae4587))
* **loader:** keep a peer's rate when its client says hello again ([#211](https://github.com/themaiby/enshwick/issues/211)) ([16c9b44](https://github.com/themaiby/enshwick/commit/16c9b445bf2d4182e28dd2d967cab8a6b2e24199))
* **loader:** keep mods on when a join is refused, read big rules ([#209](https://github.com/themaiby/enshwick/issues/209)) ([a8458b6](https://github.com/themaiby/enshwick/commit/a8458b626417ff1e36ca7d40b460bbc365a45c8d))
* **loader:** keep settings texts for the life of the process ([#175](https://github.com/themaiby/enshwick/issues/175)) ([1d56467](https://github.com/themaiby/enshwick/commit/1d5646749a7a9f9f60ebdb966352393d2ab3f499))
* **loader:** keep settings, mod data and migrations on bad reads ([#218](https://github.com/themaiby/enshwick/issues/218)) ([3f06595](https://github.com/themaiby/enshwick/commit/3f06595091114074a89e7072778080c20181bd61))
* **loader:** keep the full vector state across mid-function hooks ([#174](https://github.com/themaiby/enshwick/issues/174)) ([97c6716](https://github.com/themaiby/enshwick/commit/97c6716ffb8ed02af5e4c27e3af359560f6920e0))
* **loader:** look up the survivors' component types by hash ([#201](https://github.com/themaiby/enshwick/issues/201)) ([b1d6e57](https://github.com/themaiby/enshwick/commit/b1d6e57aa68fce15f2a6637cd5117dc94e49e3fb))
* **loader:** move return addresses out of the bytes a hook replaces ([#178](https://github.com/themaiby/enshwick/issues/178)) ([09be0dc](https://github.com/themaiby/enshwick/commit/09be0dca985e1b55f49c95252e8519ae6bdd5501))
* **loader:** refuse world changes inside a step ([#199](https://github.com/themaiby/enshwick/issues/199)) ([56f7b79](https://github.com/themaiby/enshwick/commit/56f7b799d8ba90cce10fcd5f1385f5410e995555))
* **loader:** safety and robustness pass from the conventions review ([#111](https://github.com/themaiby/enshwick/issues/111)) ([52ed976](https://github.com/themaiby/enshwick/commit/52ed976a30d65d7007a56202ed855fbb55e69740))
* **loader:** take back stat maxima, check durations, walk the menu ([#220](https://github.com/themaiby/enshwick/issues/220)) ([8142824](https://github.com/themaiby/enshwick/commit/8142824d9d788fca1715a403fed064de149e84fe))


### Performance

* **loader:** pick the cheapest vector save per processor at mid hooks ([#187](https://github.com/themaiby/enshwick/issues/187)) ([856f9b2](https://github.com/themaiby/enshwick/commit/856f9b27674e3cbc1cf2b64d37fdbf5b34902900))
* **optimizer:** rename and tune per platform for Windows and Proton ([#165](https://github.com/themaiby/enshwick/issues/165)) ([71cf9b5](https://github.com/themaiby/enshwick/commit/71cf9b51b0d35b09d12dd4974e2dc91d174e2c0b))


### Other

* **api:** one naming scheme, run-time errors and named abi values ([#110](https://github.com/themaiby/enshwick/issues/110)) ([cbe72c5](https://github.com/themaiby/enshwick/commit/cbe72c5e92104d374272a5b192272e6e276dd37b))
* consolidate into Enshwick Loader, one API crate and one tool ([#85](https://github.com/themaiby/enshwick/issues/85)) ([5ddfde4](https://github.com/themaiby/enshwick/commit/5ddfde457d24f8e000d2dee1c74508f89582d526))
</details>

<details><summary>enshwick-loader-api: 0.10.0</summary>

## [0.10.0](https://github.com/themaiby/enshwick/compare/enshwick-loader-api-v0.9.1...enshwick-loader-api-v0.10.0) (2026-10-21)


###   BREAKING CHANGES

* **updater:** accept common GitHub release forms and unsigned updates ([#198](https://github.com/themaiby/enshwick/issues/198))
* **loader:** show only updates of installed mods on the Mods screen ([#196](https://github.com/themaiby/enshwick/issues/196))
* **optimizer:** rename and tune per platform for Windows and Proton ([#165](https://github.com/themaiby/enshwick/issues/165))
* **api:** name mod content mod:name and derive its GUIDs
* **api:** check service layouts and add typed mod events ([#146](https://github.com/themaiby/enshwick/issues/146))
* **loader:** mod settings per world ([#145](https://github.com/themaiby/enshwick/issues/145))
* **api:** name, describe and credit mods, with recommends and breaks ([#126](https://github.com/themaiby/enshwick/issues/126))
* **api:** config stages, ranges, choices, schema and /config ([#130](https://github.com/themaiby/enshwick/issues/130))
* **api:** one naming scheme, run-time errors and named abi values ([#110](https://github.com/themaiby/enshwick/issues/110))
* consolidate into Enshwick Loader, one API crate and one tool ([#85](https://github.com/themaiby/enshwick/issues/85))

### Features

* **api:** a safe loot pass over each container check ([#102](https://github.com/themaiby/enshwick/issues/102)) ([150d611](https://github.com/themaiby/enshwick/commit/150d6116326741ab0855759251f3ee25b053858b))
* **api:** add stat kinds, modifiers and built-in stats ([#143](https://github.com/themaiby/enshwick/issues/143)) ([dabec8b](https://github.com/themaiby/enshwick/commit/dabec8b85843c33fd3b7a3d07b17271451e7b344))
* **api:** add, dig and flatten terrain, and list its materials ([#125](https://github.com/themaiby/enshwick/issues/125)) ([032b1c9](https://github.com/themaiby/enshwick/commit/032b1c99513dad768d2e380ee339c42ece53ec90))
* **api:** altar limit and bases past 16 zones in the platform ([#101](https://github.com/themaiby/enshwick/issues/101)) ([a8e5ca9](https://github.com/themaiby/enshwick/commit/a8e5ca9bafc6321d70c81f2bc1458e34a1ec8175))
* **api:** altar zones and bases in the platform ([#97](https://github.com/themaiby/enshwick/issues/97)) ([e45cc7b](https://github.com/themaiby/enshwick/commit/e45cc7b58c6d82db2affa56b4fbfa89bd4fc3824))
* **api:** attach typed data to single items ([#133](https://github.com/themaiby/enshwick/issues/133)) ([4d938a9](https://github.com/themaiby/enshwick/commit/4d938a9c457857c7da77066b6fe8c2ecbe6d5ea3))
* **api:** attach typed mod data to any entity, per world ([#161](https://github.com/themaiby/enshwick/issues/161)) ([b0fee70](https://github.com/themaiby/enshwick/commit/b0fee7049cf8c82f791a45716d3ff14d01267dd0))
* **api:** check service layouts and add typed mod events ([#146](https://github.com/themaiby/enshwick/issues/146)) ([aa701ce](https://github.com/themaiby/enshwick/commit/aa701cef773075939cb480dc1c01e91474883196))
* **api:** config stages, ranges, choices, schema and /config ([#130](https://github.com/themaiby/enshwick/issues/130)) ([8a19e89](https://github.com/themaiby/enshwick/commit/8a19e89afe6ac74d09d9a32c66b1fc133e81bc68))
* **api:** draw lines and bars on the HUD and markers on the map ([#134](https://github.com/themaiby/enshwick/issues/134)) ([11d05b3](https://github.com/themaiby/enshwick/commit/11d05b3701942738d3fa49d73726af363af9133b))
* **api:** draw with the game's own widgets and show its dialogs ([#129](https://github.com/themaiby/enshwick/issues/129)) ([8601c70](https://github.com/themaiby/enshwick/commit/8601c70f8a0678a50f41301467d713bf41fab855))
* **api:** engine events from the server's ECS event streams ([#104](https://github.com/themaiby/enshwick/issues/104)) ([73cdaaf](https://github.com/themaiby/enshwick/commit/73cdaafb179d62d9891cb614a3b03f3e3fc783fa))
* **api:** entity queries, destroy, saves and per-world stores ([#105](https://github.com/themaiby/enshwick/issues/105)) ([ffd6090](https://github.com/themaiby/enshwick/commit/ffd6090628a40bd416e19767fcdc89ef7faba853))
* **api:** filter damage by cause and type before it is applied ([#121](https://github.com/themaiby/enshwick/issues/121)) ([a349c50](https://github.com/themaiby/enshwick/commit/a349c50d002eaedafdf9d10873c740d76bdd7140))
* **api:** give items a meter, tooltip lines and fill on give ([#128](https://github.com/themaiby/enshwick/issues/128)) ([11beb9b](https://github.com/themaiby/enshwick/commit/11beb9b762be4d3d6b80cc81b2c3baffb2ab3131))
* **api:** give items icons of their own ([#142](https://github.com/themaiby/enshwick/issues/142)) ([a0c0228](https://github.com/themaiby/enshwick/commit/a0c02288e4c586fc21e01e8497e1fe2da2d7ce76))
* **api:** interaction filters for chests and placed pieces ([#99](https://github.com/themaiby/enshwick/issues/99)) ([7a47400](https://github.com/themaiby/enshwick/commit/7a47400e8c74afee1e1fcfde60bc32aae24ba6d7))
* **api:** list, give and remove buffs and debuffs ([#122](https://github.com/themaiby/enshwick/issues/122)) ([78a7b89](https://github.com/themaiby/enshwick/commit/78a7b89b2fbc3722600529f32f718f1d073bfee8))
* **api:** messages between a mod's server and client parts ([#116](https://github.com/themaiby/enshwick/issues/116)) ([671de20](https://github.com/themaiby/enshwick/commit/671de2003d7a7016131b39db81b59efda4bd732a))
* **api:** name mod content mod:name and derive its GUIDs ([38f46ce](https://github.com/themaiby/enshwick/commit/38f46ce596e9fa6c25c0d673558ee56887160bfb))
* **api:** name vanilla content in packs by debug name ([#193](https://github.com/themaiby/enshwick/issues/193)) ([033fda9](https://github.com/themaiby/enshwick/commit/033fda9c6fa7f616c780d690e1b5758550a086de))
* **api:** name, describe and credit mods, with recommends and breaks ([#126](https://github.com/themaiby/enshwick/issues/126)) ([edfb07c](https://github.com/themaiby/enshwick/commit/edfb07c59676c441f1e8b06ddc2791a80594ae6c))
* **api:** raise allowed game events and teleport entities ([#113](https://github.com/themaiby/enshwick/issues/113)) ([5a42ea6](https://github.com/themaiby/enshwick/commit/5a42ea670417aba93ad18fba57d36db1190de2d2))
* **api:** read and change the server's game settings ([#120](https://github.com/themaiby/enshwick/issues/120)) ([159227a](https://github.com/themaiby/enshwick/commit/159227a6d666999d4d1985b1920c590729055288))
* **api:** read and grant knowledge, quests and their events ([#123](https://github.com/themaiby/enshwick/issues/123)) ([0a656e5](https://github.com/themaiby/enshwick/commit/0a656e585e8c6575c1ff10089d413b2aea672d7b))
* **api:** read and set the time of day, its speed and day turns ([#119](https://github.com/themaiby/enshwick/issues/119)) ([b7505e6](https://github.com/themaiby/enshwick/commit/b7505e697beccf7fda0dfdb4db0b8220cf4e7f42))
* **api:** read and start weather, and report chunk loads ([#124](https://github.com/themaiby/enshwick/issues/124)) ([a36528f](https://github.com/themaiby/enshwick/commit/a36528f1d683b8446c175be2de7635a50f9033db))
* **api:** read the game's own texts and resources from its archive ([#191](https://github.com/themaiby/enshwick/issues/191)) ([ebaf029](https://github.com/themaiby/enshwick/commit/ebaf029db0cf95f6cb63602d6b0f617e8dc451e0))
* **api:** read the skill nodes a character unlocked ([#186](https://github.com/themaiby/enshwick/issues/186)) ([1a56dde](https://github.com/themaiby/enshwick/commit/1a56dde397e0ef4fad18a0ab9a4250ed17712d85))
* **api:** roll affixes onto items from loot, crafting or a mod ([#147](https://github.com/themaiby/enshwick/issues/147)) ([c40ab9b](https://github.com/themaiby/enshwick/commit/c40ab9be39b5e6fee00652aeb5c03117067ec340))
* **api:** run mod migrations once per world and record them ([#150](https://github.com/themaiby/enshwick/issues/150)) ([0bf89e9](https://github.com/themaiby/enshwick/commit/0bf89e9887a6518f26ab87caefba43149438b88c))
* **api:** show notices on a player's screen ([#117](https://github.com/themaiby/enshwick/issues/117)) ([b174549](https://github.com/themaiby/enshwick/commit/b174549819df1e5285b2b74b626732bf3599ee58))
* **api:** skill, comfort and experience hooks in the platform ([#100](https://github.com/themaiby/enshwick/issues/100)) ([c810a02](https://github.com/themaiby/enshwick/commit/c810a02a60d5d05b8872bf8628afc27123868aa1))
* **api:** spawn entities from templates ([#114](https://github.com/themaiby/enshwick/issues/114)) ([63b6e3f](https://github.com/themaiby/enshwick/commit/63b6e3f2da5d44ad05d0ccc0bcad34582469a64c))
* **api:** survivor lookups, beds, staffs and menu in the platform ([#103](https://github.com/themaiby/enshwick/issues/103)) ([166e1ba](https://github.com/themaiby/enshwick/commit/166e1ba837d789bbd9a36f9bab41e8530666d4ef))
* **api:** typed engine events, kill credit and character stats ([#106](https://github.com/themaiby/enshwick/issues/106)) ([99e1d93](https://github.com/themaiby/enshwick/commit/99e1d93ce64e899a9db5c5c872f199ac92bac6f4))
* **api:** veto crafting and building ([#115](https://github.com/themaiby/enshwick/issues/115)) ([7009d56](https://github.com/themaiby/enshwick/commit/7009d568e78eee315a6f8631df6463342e7b1fd2))
* **api:** write components marked changed, set health stamina mana ([#112](https://github.com/themaiby/enshwick/issues/112)) ([98a104f](https://github.com/themaiby/enshwick/commit/98a104fdc9eb06c525eabbcd73c286a039a5e211))
* **loader:** a Mods screen beside Settings with each mod's settings ([#137](https://github.com/themaiby/enshwick/issues/137)) ([45c2400](https://github.com/themaiby/enshwick/commit/45c240061c0d00578d7c9e28afe26755802316a6))
* **loader:** add content packs of TOML files, signed and reloadable ([#158](https://github.com/themaiby/enshwick/issues/158)) ([7598b97](https://github.com/themaiby/enshwick/commit/7598b977434dfb207cd5c0d30c6cdd936c0cb0cc))
* **loader:** filter drowning, freezing and admin kills ([#181](https://github.com/themaiby/enshwick/issues/181)) ([215297f](https://github.com/themaiby/enshwick/commit/215297f9059d2a21c0d741f34b014988bc5e0993))
* **loader:** keep game settings with the world ([#179](https://github.com/themaiby/enshwick/issues/179)) ([3a1d819](https://github.com/themaiby/enshwick/commit/3a1d819f5f4e34570ce1547b6b8e55368d74f664))
* **loader:** label mods' settings in the player's language ([#141](https://github.com/themaiby/enshwick/issues/141)) ([0cbc46f](https://github.com/themaiby/enshwick/commit/0cbc46fd311d1bc187b9c89236e10d83a429b27a))
* **loader:** mod settings per world ([#145](https://github.com/themaiby/enshwick/issues/145)) ([c06612b](https://github.com/themaiby/enshwick/commit/c06612bf26b00d4cd6175fd4dac343bb637a5ccc))
* **loader:** name the killer entity of a player killed by a hit ([#202](https://github.com/themaiby/enshwick/issues/202)) ([c81f863](https://github.com/themaiby/enshwick/commit/c81f8630e192ec6dceba4c395c4639aafea27e7b))
* **loader:** never start a mod that a renamed mod replaces ([#166](https://github.com/themaiby/enshwick/issues/166)) ([650993c](https://github.com/themaiby/enshwick/commit/650993c7b392be07fc16c4ca47925952c64f1487))
* **loader:** push changed join values and edit server settings remotely ([#138](https://github.com/themaiby/enshwick/issues/138)) ([58bba7c](https://github.com/themaiby/enshwick/commit/58bba7c378f92d5bf832d1f82aa09626591a2899))
* **loader:** refuse knowledge a client grants itself ([#173](https://github.com/themaiby/enshwick/issues/173)) ([a6c2ee7](https://github.com/themaiby/enshwick/commit/a6c2ee7376ec8166b0aa7de9b5cda90b7c28fafa))
* **loader:** reload mods while a development server runs ([#164](https://github.com/themaiby/enshwick/issues/164)) ([16494a1](https://github.com/themaiby/enshwick/commit/16494a1f52b8c473876b6af9ce014f93a71afbc0))
* **loader:** report player deaths and read the shroud timer ([#185](https://github.com/themaiby/enshwick/issues/185)) ([9bcd23c](https://github.com/themaiby/enshwick/commit/9bcd23c64665aeb814bf0bc08109ce48ec62eeed))
* **loader:** ship build tables as signed data with a pattern fallback ([#155](https://github.com/themaiby/enshwick/issues/155)) ([1df2e3f](https://github.com/themaiby/enshwick/commit/1df2e3fdcaeaeac3ca082a18976e6a3f1d3a46c9))
* **loader:** show mod catalogs with updates and mods on the Mods screen ([#180](https://github.com/themaiby/enshwick/issues/180)) ([2e93fb7](https://github.com/themaiby/enshwick/commit/2e93fb7ec219b7c4b4fcab0ff45dcd4c409340d6))
* **loader:** show only updates of installed mods on the Mods screen ([#196](https://github.com/themaiby/enshwick/issues/196)) ([aee82ac](https://github.com/themaiby/enshwick/commit/aee82acb3a6a0f9d8aa2ebbe414a7a31961c1cd7))
* **loader:** take knowledge back and change it for absent players ([#183](https://github.com/themaiby/enshwick/issues/183)) ([13e4883](https://github.com/themaiby/enshwick/commit/13e4883e75df99ecd6101754608161c87c39633d))
* **loader:** watch knowledge requests by default before refusing them ([#190](https://github.com/themaiby/enshwick/issues/190)) ([ba2efcd](https://github.com/themaiby/enshwick/commit/ba2efcd87974e62d758b6c9a85fef53f46d2f026))
* **survivors-per-altar:** copies come only from copy staffs ([#140](https://github.com/themaiby/enshwick/issues/140)) ([ab540fb](https://github.com/themaiby/enshwick/commit/ab540fb687900e7350f452f3403d4bebabd9f919))
* **updater:** accept common GitHub release forms and unsigned updates ([#198](https://github.com/themaiby/enshwick/issues/198)) ([51d3e47](https://github.com/themaiby/enshwick/commit/51d3e4754a34496c5c90ab4b610f3621f0a92d85))
* **updater:** page through releases, word dialogs in the game language ([#170](https://github.com/themaiby/enshwick/issues/170)) ([c6bd27a](https://github.com/themaiby/enshwick/commit/c6bd27a947073a2e4a40dc822f2e3f64606c20a4))


### Bug Fixes

* **api:** audit the modder API for soundness, ABI and reuse ([#95](https://github.com/themaiby/enshwick/issues/95)) ([d800142](https://github.com/themaiby/enshwick/commit/d800142991a2d93aaf943af9f6e5cc629fa54d68))
* **api:** keep Config files and checks in step with serde ([#213](https://github.com/themaiby/enshwick/issues/213)) ([3554bb8](https://github.com/themaiby/enshwick/commit/3554bb8fc24b3dbee15248fe769b29da7d84c4b0))
* **api:** let hook take an alias and guard work after a chain call ([#217](https://github.com/themaiby/enshwick/issues/217)) ([e4b28cd](https://github.com/themaiby/enshwick/commit/e4b28cd16b0e8838600ea8ab26f4170c933432dc))
* **api:** refuse signed bytes in code patterns ([#208](https://github.com/themaiby/enshwick/issues/208)) ([7ec79de](https://github.com/themaiby/enshwick/commit/7ec79dea7624394f38f18edfc065a0d3842b2200))
* **api:** write components through a copy, refuse null resources ([#222](https://github.com/themaiby/enshwick/issues/222)) ([da1a8ee](https://github.com/themaiby/enshwick/commit/da1a8eef8c2e8de808da49469a87cea2f3da4c86))
* build the docs without rustdoc link errors ([#87](https://github.com/themaiby/enshwick/issues/87)) ([57b02cf](https://github.com/themaiby/enshwick/commit/57b02cf899cf0a0bfc97633ea47339e630f0c0e5))
* **loader:** close crash paths found in the loader audit ([#182](https://github.com/themaiby/enshwick/issues/182)) ([7e4fab8](https://github.com/themaiby/enshwick/commit/7e4fab8a0b70efe438d43b6d9649af97c112e9cb))
* **loader:** keep settings texts for the life of the process ([#175](https://github.com/themaiby/enshwick/issues/175)) ([1d56467](https://github.com/themaiby/enshwick/commit/1d5646749a7a9f9f60ebdb966352393d2ab3f499))
* **loader:** refuse world changes inside a step ([#199](https://github.com/themaiby/enshwick/issues/199)) ([56f7b79](https://github.com/themaiby/enshwick/commit/56f7b799d8ba90cce10fcd5f1385f5410e995555))
* **loader:** safety and robustness pass from the conventions review ([#111](https://github.com/themaiby/enshwick/issues/111)) ([52ed976](https://github.com/themaiby/enshwick/commit/52ed976a30d65d7007a56202ed855fbb55e69740))
* **probe:** move the clock only after the weather checks are done ([#151](https://github.com/themaiby/enshwick/issues/151)) ([54c22ed](https://github.com/themaiby/enshwick/commit/54c22edf317990f4258e74133903d4f1a390603b))
* **survivors-per-altar:** sync copy_staffs, forget a last altar removed ([#176](https://github.com/themaiby/enshwick/issues/176)) ([551ab93](https://github.com/themaiby/enshwick/commit/551ab93eccbf0bc3b8913613635ce9f6419ee940))


### Performance

* **optimizer:** rename and tune per platform for Windows and Proton ([#165](https://github.com/themaiby/enshwick/issues/165)) ([71cf9b5](https://github.com/themaiby/enshwick/commit/71cf9b51b0d35b09d12dd4974e2dc91d174e2c0b))


### Other

* **api:** one naming scheme, run-time errors and named abi values ([#110](https://github.com/themaiby/enshwick/issues/110)) ([cbe72c5](https://github.com/themaiby/enshwick/commit/cbe72c5e92104d374272a5b192272e6e276dd37b))
* consolidate into Enshwick Loader, one API crate and one tool ([#85](https://github.com/themaiby/enshwick/issues/85)) ([5ddfde4](https://github.com/themaiby/enshwick/commit/5ddfde457d24f8e000d2dee1c74508f89582d526))


### Dependencies

* The following workspace dependencies were updated
  * dependencies
    * enshwick-loader-macros bumped from 0.9.1 to 0.10.0
</details>

<details><summary>enshwick-loader-builds: 0.10.0</summary>

## [0.10.0](https://github.com/themaiby/enshwick/compare/enshwick-loader-builds-v0.9.1...enshwick-loader-builds-v0.10.0) (2026-10-21)


### Features

* **loader:** filter drowning, freezing and admin kills ([#181](https://github.com/themaiby/enshwick/issues/181)) ([215297f](https://github.com/themaiby/enshwick/commit/215297f9059d2a21c0d741f34b014988bc5e0993))
* **loader:** refuse knowledge a client grants itself ([#173](https://github.com/themaiby/enshwick/issues/173)) ([a6c2ee7](https://github.com/themaiby/enshwick/commit/a6c2ee7376ec8166b0aa7de9b5cda90b7c28fafa))
* **loader:** report player deaths and read the shroud timer ([#185](https://github.com/themaiby/enshwick/issues/185)) ([9bcd23c](https://github.com/themaiby/enshwick/commit/9bcd23c64665aeb814bf0bc08109ce48ec62eeed))
* **loader:** ship build tables as signed data with a pattern fallback ([#155](https://github.com/themaiby/enshwick/issues/155)) ([1df2e3f](https://github.com/themaiby/enshwick/commit/1df2e3fdcaeaeac3ca082a18976e6a3f1d3a46c9))
* **loader:** take knowledge back and change it for absent players ([#183](https://github.com/themaiby/enshwick/issues/183)) ([13e4883](https://github.com/themaiby/enshwick/commit/13e4883e75df99ecd6101754608161c87c39633d))


### Bug Fixes

* **loader:** harden hook writes, chain wiring and the zmm check ([#216](https://github.com/themaiby/enshwick/issues/216)) ([2169e1d](https://github.com/themaiby/enshwick/commit/2169e1d1d5b3d0bb73e55545c18415bb4dae4587))
* **loader:** look up the survivors' component types by hash ([#201](https://github.com/themaiby/enshwick/issues/201)) ([b1d6e57](https://github.com/themaiby/enshwick/commit/b1d6e57aa68fce15f2a6637cd5117dc94e49e3fb))
* **loader:** refuse world changes inside a step ([#199](https://github.com/themaiby/enshwick/issues/199)) ([56f7b79](https://github.com/themaiby/enshwick/commit/56f7b799d8ba90cce10fcd5f1385f5410e995555))
</details>

<details><summary>enshwick-loader-macros: 0.10.0</summary>

## [0.10.0](https://github.com/themaiby/enshwick/compare/enshwick-loader-macros-v0.9.1...enshwick-loader-macros-v0.10.0) (2026-10-21)


###   BREAKING CHANGES

* **api:** check service layouts and add typed mod events ([#146](https://github.com/themaiby/enshwick/issues/146))
* **loader:** mod settings per world ([#145](https://github.com/themaiby/enshwick/issues/145))
* **api:** config stages, ranges, choices, schema and /config ([#130](https://github.com/themaiby/enshwick/issues/130))
* consolidate into Enshwick Loader, one API crate and one tool ([#85](https://github.com/themaiby/enshwick/issues/85))

### Features

* **api:** check service layouts and add typed mod events ([#146](https://github.com/themaiby/enshwick/issues/146)) ([aa701ce](https://github.com/themaiby/enshwick/commit/aa701cef773075939cb480dc1c01e91474883196))
* **api:** config stages, ranges, choices, schema and /config ([#130](https://github.com/themaiby/enshwick/issues/130)) ([8a19e89](https://github.com/themaiby/enshwick/commit/8a19e89afe6ac74d09d9a32c66b1fc133e81bc68))
* **loader:** mod settings per world ([#145](https://github.com/themaiby/enshwick/issues/145)) ([c06612b](https://github.com/themaiby/enshwick/commit/c06612bf26b00d4cd6175fd4dac343bb637a5ccc))
* **loader:** push changed join values and edit server settings remotely ([#138](https://github.com/themaiby/enshwick/issues/138)) ([58bba7c](https://github.com/themaiby/enshwick/commit/58bba7c378f92d5bf832d1f82aa09626591a2899))


### Bug Fixes

* **api:** keep Config files and checks in step with serde ([#213](https://github.com/themaiby/enshwick/issues/213)) ([3554bb8](https://github.com/themaiby/enshwick/commit/3554bb8fc24b3dbee15248fe769b29da7d84c4b0))
* **api:** let hook take an alias and guard work after a chain call ([#217](https://github.com/themaiby/enshwick/issues/217)) ([e4b28cd](https://github.com/themaiby/enshwick/commit/e4b28cd16b0e8838600ea8ab26f4170c933432dc))


### Other

* consolidate into Enshwick Loader, one API crate and one tool ([#85](https://github.com/themaiby/enshwick/issues/85)) ([5ddfde4](https://github.com/themaiby/enshwick/commit/5ddfde457d24f8e000d2dee1c74508f89582d526))
</details>

<details><summary>enshwick-loader-reflect: 0.10.0</summary>

## [0.10.0](https://github.com/themaiby/enshwick/compare/enshwick-loader-reflect-v0.9.1...enshwick-loader-reflect-v0.10.0) (2026-10-21)


###   BREAKING CHANGES

* consolidate into Enshwick Loader, one API crate and one tool ([#85](https://github.com/themaiby/enshwick/issues/85))

### Features

* **api:** write components marked changed, set health stamina mana ([#112](https://github.com/themaiby/enshwick/issues/112)) ([98a104f](https://github.com/themaiby/enshwick/commit/98a104fdc9eb06c525eabbcd73c286a039a5e211))


### Other

* consolidate into Enshwick Loader, one API crate and one tool ([#85](https://github.com/themaiby/enshwick/issues/85)) ([5ddfde4](https://github.com/themaiby/enshwick/commit/5ddfde457d24f8e000d2dee1c74508f89582d526))
</details>

<details><summary>enshwick-loader-stub: 0.10.0</summary>

## [0.10.0](https://github.com/themaiby/enshwick/compare/enshwick-loader-stub-v0.9.1...enshwick-loader-stub-v0.10.0) (2026-10-21)


###   BREAKING CHANGES

* **optimizer:** rename and tune per platform for Windows and Proton ([#165](https://github.com/themaiby/enshwick/issues/165))
* consolidate into Enshwick Loader, one API crate and one tool ([#85](https://github.com/themaiby/enshwick/issues/85))

### Performance

* **optimizer:** rename and tune per platform for Windows and Proton ([#165](https://github.com/themaiby/enshwick/issues/165)) ([71cf9b5](https://github.com/themaiby/enshwick/commit/71cf9b51b0d35b09d12dd4974e2dc91d174e2c0b))


### Other

* consolidate into Enshwick Loader, one API crate and one tool ([#85](https://github.com/themaiby/enshwick/issues/85)) ([5ddfde4](https://github.com/themaiby/enshwick/commit/5ddfde457d24f8e000d2dee1c74508f89582d526))
</details>

<details><summary>enshwick-optimizer: 0.6.0</summary>

## [0.6.0](https://github.com/themaiby/enshwick/compare/enshwick-optimizer-v0.5.4...enshwick-optimizer-v0.6.0) (2026-10-21)


###   BREAKING CHANGES

* **optimizer:** rename and tune per platform for Windows and Proton ([#165](https://github.com/themaiby/enshwick/issues/165))

### Features

* **loader:** never start a mod that a renamed mod replaces ([#166](https://github.com/themaiby/enshwick/issues/166)) ([650993c](https://github.com/themaiby/enshwick/commit/650993c7b392be07fc16c4ca47925952c64f1487))


### Performance

* **optimizer:** rename and tune per platform for Windows and Proton ([#165](https://github.com/themaiby/enshwick/issues/165)) ([71cf9b5](https://github.com/themaiby/enshwick/commit/71cf9b51b0d35b09d12dd4974e2dc91d174e2c0b))
</details>

<details><summary>enshwick-probe: 0.1.10</summary>

### Dependencies


</details>

<details><summary>enshwick-research: 0.1.9</summary>

### Dependencies


</details>

<details><summary>enshwick-safes: 0.7.0</summary>

## [0.7.0](https://github.com/themaiby/enshwick/compare/enshwick-safes-v0.6.5...enshwick-safes-v0.7.0) (2026-10-21)


###   BREAKING CHANGES

* **api:** name mod content mod:name and derive its GUIDs
* **api:** name, describe and credit mods, with recommends and breaks ([#126](https://github.com/themaiby/enshwick/issues/126))
* **api:** config stages, ranges, choices, schema and /config ([#130](https://github.com/themaiby/enshwick/issues/130))
* **api:** one naming scheme, run-time errors and named abi values ([#110](https://github.com/themaiby/enshwick/issues/110))
* consolidate into Enshwick Loader, one API crate and one tool ([#85](https://github.com/themaiby/enshwick/issues/85))

### Features

* add workshops and a Bulk Workbench for bulk recipes ([#67](https://github.com/themaiby/enshwick/issues/67)) ([71a28aa](https://github.com/themaiby/enshwick/commit/71a28aa90793f2285017608b282e134363bad849))
* **api:** config stages, ranges, choices, schema and /config ([#130](https://github.com/themaiby/enshwick/issues/130)) ([8a19e89](https://github.com/themaiby/enshwick/commit/8a19e89afe6ac74d09d9a32c66b1fc133e81bc68))
* **api:** give items a meter, tooltip lines and fill on give ([#128](https://github.com/themaiby/enshwick/issues/128)) ([11beb9b](https://github.com/themaiby/enshwick/commit/11beb9b762be4d3d6b80cc81b2c3baffb2ab3131))
* **api:** interaction filters for chests and placed pieces ([#99](https://github.com/themaiby/enshwick/issues/99)) ([7a47400](https://github.com/themaiby/enshwick/commit/7a47400e8c74afee1e1fcfde60bc32aae24ba6d7))
* **api:** name mod content mod:name and derive its GUIDs ([38f46ce](https://github.com/themaiby/enshwick/commit/38f46ce596e9fa6c25c0d673558ee56887160bfb))
* **api:** name, describe and credit mods, with recommends and breaks ([#126](https://github.com/themaiby/enshwick/issues/126)) ([edfb07c](https://github.com/themaiby/enshwick/commit/edfb07c59676c441f1e8b06ddc2791a80594ae6c))
* author keys: updates must be signed by the installed version's key ([#81](https://github.com/themaiby/enshwick/issues/81)) ([d9d46f3](https://github.com/themaiby/enshwick/commit/d9d46f38231234e958a8762e6c0fff5b6ddcb5d8))
* content and i18n in the API, and the safes mod ([#52](https://github.com/themaiby/enshwick/issues/52)) ([00ae927](https://github.com/themaiby/enshwick/commit/00ae9278664af9209bf1b0fba9137c25527bb397))
* run server mods in games the client hosts ([#61](https://github.com/themaiby/enshwick/issues/61)) ([4c6fe26](https://github.com/themaiby/enshwick/commit/4c6fe269e6137bba6e7190907929fa1b11033744))
* **safes:** owner on hover, renames for owners, /safe allow and deny ([#63](https://github.com/themaiby/enshwick/issues/63)) ([2475ccb](https://github.com/themaiby/enshwick/commit/2475ccb7b3aa6487a8d8fb8a82292207839e1ad2))
* update sources in manifests and staged updates in the stub ([#57](https://github.com/themaiby/enshwick/issues/57)) ([20e72b1](https://github.com/themaiby/enshwick/commit/20e72b1025765d83f3da861ec46ccbb4a163443c))


### Bug Fixes

* **api:** audit the modder API for soundness, ABI and reuse ([#95](https://github.com/themaiby/enshwick/issues/95)) ([d800142](https://github.com/themaiby/enshwick/commit/d800142991a2d93aaf943af9f6e5cc629fa54d68))
* **mods:** audit fixes across every mod ([#94](https://github.com/themaiby/enshwick/issues/94)) ([e83b2d6](https://github.com/themaiby/enshwick/commit/e83b2d6d9f788f3cf9cc60d32fdcdb95196b76d4))
* **safes:** keep owners per world and refuse players not registered yet ([#168](https://github.com/themaiby/enshwick/issues/168)) ([1bfdb8c](https://github.com/themaiby/enshwick/commit/1bfdb8cb5d96975c26c33e40a81848f9b344b6e2))
* **safes:** learn every Safe so base stock skips it from the start ([#214](https://github.com/themaiby/enshwick/issues/214)) ([819cce4](https://github.com/themaiby/enshwick/commit/819cce4d361996b1930a19aa861c89a9185203c5))


### Other

* **api:** one naming scheme, run-time errors and named abi values ([#110](https://github.com/themaiby/enshwick/issues/110)) ([cbe72c5](https://github.com/themaiby/enshwick/commit/cbe72c5e92104d374272a5b192272e6e276dd37b))
* consolidate into Enshwick Loader, one API crate and one tool ([#85](https://github.com/themaiby/enshwick/issues/85)) ([5ddfde4](https://github.com/themaiby/enshwick/commit/5ddfde457d24f8e000d2dee1c74508f89582d526))
</details>

<details><summary>enshwick-shared-experience: 0.5.0</summary>

## [0.5.0](https://github.com/themaiby/enshwick/compare/enshwick-shared-experience-v0.4.7...enshwick-shared-experience-v0.5.0) (2026-10-21)


###   BREAKING CHANGES

* **api:** name, describe and credit mods, with recommends and breaks ([#126](https://github.com/themaiby/enshwick/issues/126))
* **api:** config stages, ranges, choices, schema and /config ([#130](https://github.com/themaiby/enshwick/issues/130))
* **api:** one naming scheme, run-time errors and named abi values ([#110](https://github.com/themaiby/enshwick/issues/110))
* consolidate into Enshwick Loader, one API crate and one tool ([#85](https://github.com/themaiby/enshwick/issues/85))

### Features

* **api:** config stages, ranges, choices, schema and /config ([#130](https://github.com/themaiby/enshwick/issues/130)) ([8a19e89](https://github.com/themaiby/enshwick/commit/8a19e89afe6ac74d09d9a32c66b1fc133e81bc68))
* **api:** name, describe and credit mods, with recommends and breaks ([#126](https://github.com/themaiby/enshwick/issues/126)) ([edfb07c](https://github.com/themaiby/enshwick/commit/edfb07c59676c441f1e8b06ddc2791a80594ae6c))
* **api:** skill, comfort and experience hooks in the platform ([#100](https://github.com/themaiby/enshwick/issues/100)) ([c810a02](https://github.com/themaiby/enshwick/commit/c810a02a60d5d05b8872bf8628afc27123868aa1))
* author keys: updates must be signed by the installed version's key ([#81](https://github.com/themaiby/enshwick/issues/81)) ([d9d46f3](https://github.com/themaiby/enshwick/commit/d9d46f38231234e958a8762e6c0fff5b6ddcb5d8))
* shared experience mod ([#68](https://github.com/themaiby/enshwick/issues/68)) ([43f9b60](https://github.com/themaiby/enshwick/commit/43f9b60c700f72feebfe59e3eca8ac705988ac11))


### Bug Fixes

* **mods:** audit fixes across every mod ([#94](https://github.com/themaiby/enshwick/issues/94)) ([e83b2d6](https://github.com/themaiby/enshwick/commit/e83b2d6d9f788f3cf9cc60d32fdcdb95196b76d4))
* **shared-experience:** count one gain per server step, not per batch ([#215](https://github.com/themaiby/enshwick/issues/215)) ([e511306](https://github.com/themaiby/enshwick/commit/e5113066565121cf4b490d1a7f1c369a63cea7ac))


### Other

* **api:** one naming scheme, run-time errors and named abi values ([#110](https://github.com/themaiby/enshwick/issues/110)) ([cbe72c5](https://github.com/themaiby/enshwick/commit/cbe72c5e92104d374272a5b192272e6e276dd37b))
* consolidate into Enshwick Loader, one API crate and one tool ([#85](https://github.com/themaiby/enshwick/issues/85)) ([5ddfde4](https://github.com/themaiby/enshwick/commit/5ddfde457d24f8e000d2dee1c74508f89582d526))
</details>

<details><summary>enshwick-survivors-per-altar: 0.7.0</summary>

## [0.7.0](https://github.com/themaiby/enshwick/compare/enshwick-survivors-per-altar-v0.6.5...enshwick-survivors-per-altar-v0.7.0) (2026-10-21)


###   BREAKING CHANGES

* **api:** name mod content mod:name and derive its GUIDs
* **api:** name, describe and credit mods, with recommends and breaks ([#126](https://github.com/themaiby/enshwick/issues/126))
* **api:** config stages, ranges, choices, schema and /config ([#130](https://github.com/themaiby/enshwick/issues/130))
* **api:** one naming scheme, run-time errors and named abi values ([#110](https://github.com/themaiby/enshwick/issues/110))
* consolidate into Enshwick Loader, one API crate and one tool ([#85](https://github.com/themaiby/enshwick/issues/85))

### Features

* **api:** altar zones and bases in the platform ([#97](https://github.com/themaiby/enshwick/issues/97)) ([e45cc7b](https://github.com/themaiby/enshwick/commit/e45cc7b58c6d82db2affa56b4fbfa89bd4fc3824))
* **api:** config stages, ranges, choices, schema and /config ([#130](https://github.com/themaiby/enshwick/issues/130)) ([8a19e89](https://github.com/themaiby/enshwick/commit/8a19e89afe6ac74d09d9a32c66b1fc133e81bc68))
* **api:** give items a meter, tooltip lines and fill on give ([#128](https://github.com/themaiby/enshwick/issues/128)) ([11beb9b](https://github.com/themaiby/enshwick/commit/11beb9b762be4d3d6b80cc81b2c3baffb2ab3131))
* **api:** name mod content mod:name and derive its GUIDs ([38f46ce](https://github.com/themaiby/enshwick/commit/38f46ce596e9fa6c25c0d673558ee56887160bfb))
* **api:** name, describe and credit mods, with recommends and breaks ([#126](https://github.com/themaiby/enshwick/issues/126)) ([edfb07c](https://github.com/themaiby/enshwick/commit/edfb07c59676c441f1e8b06ddc2791a80594ae6c))
* **api:** read the game's own texts and resources from its archive ([#191](https://github.com/themaiby/enshwick/issues/191)) ([ebaf029](https://github.com/themaiby/enshwick/commit/ebaf029db0cf95f6cb63602d6b0f617e8dc451e0))
* **api:** survivor lookups, beds, staffs and menu in the platform ([#103](https://github.com/themaiby/enshwick/issues/103)) ([166e1ba](https://github.com/themaiby/enshwick/commit/166e1ba837d789bbd9a36f9bab41e8530666d4ef))
* author keys: updates must be signed by the installed version's key ([#81](https://github.com/themaiby/enshwick/issues/81)) ([d9d46f3](https://github.com/themaiby/enshwick/commit/d9d46f38231234e958a8762e6c0fff5b6ddcb5d8))
* **enshwick-survivors-per-altar:** a copy of each survivor per altar ([#13](https://github.com/themaiby/enshwick/issues/13)) ([1e55736](https://github.com/themaiby/enshwick/commit/1e557367a8a6c9ce39276759f1131091f7130406))
* run server mods in games the client hosts ([#61](https://github.com/themaiby/enshwick/issues/61)) ([4c6fe26](https://github.com/themaiby/enshwick/commit/4c6fe269e6137bba6e7190907929fa1b11033744))
* **survivors-per-altar:** add single-use copy staffs per survivor ([#74](https://github.com/themaiby/enshwick/issues/74)) ([e0f3e6c](https://github.com/themaiby/enshwick/commit/e0f3e6cae7ff80d212fcf7e099cef09654c63075))
* **survivors-per-altar:** copies come only from copy staffs ([#140](https://github.com/themaiby/enshwick/issues/140)) ([ab540fb](https://github.com/themaiby/enshwick/commit/ab540fb687900e7350f452f3403d4bebabd9f919))
* **survivors-per-altar:** give copy staffs a violet icon ([#144](https://github.com/themaiby/enshwick/issues/144)) ([5843f56](https://github.com/themaiby/enshwick/commit/5843f5699cf83547e6f57586ee41079e86fc6723))
* **survivors-per-altar:** give copy staffs charges ([#131](https://github.com/themaiby/enshwick/issues/131)) ([2ff5952](https://github.com/themaiby/enshwick/commit/2ff59529267880d296fb50f43efa2a7e24b3d9d0))
* update sources in manifests and staged updates in the stub ([#57](https://github.com/themaiby/enshwick/issues/57)) ([20e72b1](https://github.com/themaiby/enshwick/commit/20e72b1025765d83f3da861ec46ccbb4a163443c))


### Bug Fixes

* **api:** audit the modder API for soundness, ABI and reuse ([#95](https://github.com/themaiby/enshwick/issues/95)) ([d800142](https://github.com/themaiby/enshwick/commit/d800142991a2d93aaf943af9f6e5cc629fa54d68))
* **loader:** safety and robustness pass from the conventions review ([#111](https://github.com/themaiby/enshwick/issues/111)) ([52ed976](https://github.com/themaiby/enshwick/commit/52ed976a30d65d7007a56202ed855fbb55e69740))
* **mods:** audit fixes across every mod ([#94](https://github.com/themaiby/enshwick/issues/94)) ([e83b2d6](https://github.com/themaiby/enshwick/commit/e83b2d6d9f788f3cf9cc60d32fdcdb95196b76d4))
* **survivors-per-altar:** keep a copy whose altar is not listed yet ([#212](https://github.com/themaiby/enshwick/issues/212)) ([aba90e8](https://github.com/themaiby/enshwick/commit/aba90e88b681a53158d003efe128b3496dc80863))
* **survivors-per-altar:** require flame-altar-zones across 0.x ([#93](https://github.com/themaiby/enshwick/issues/93)) ([4a00ead](https://github.com/themaiby/enshwick/commit/4a00eada80d4dc70065fca8dcba6f43f4bb3bb02))
* **survivors-per-altar:** sync copy_staffs, forget a last altar removed ([#176](https://github.com/themaiby/enshwick/issues/176)) ([551ab93](https://github.com/themaiby/enshwick/commit/551ab93eccbf0bc3b8913613635ce9f6419ee940))


### Other

* **api:** one naming scheme, run-time errors and named abi values ([#110](https://github.com/themaiby/enshwick/issues/110)) ([cbe72c5](https://github.com/themaiby/enshwick/commit/cbe72c5e92104d374272a5b192272e6e276dd37b))
* consolidate into Enshwick Loader, one API crate and one tool ([#85](https://github.com/themaiby/enshwick/issues/85)) ([5ddfde4](https://github.com/themaiby/enshwick/commit/5ddfde457d24f8e000d2dee1c74508f89582d526))
</details>

<details><summary>enshwick-updater: 0.6.0</summary>

## [0.6.0](https://github.com/themaiby/enshwick/compare/enshwick-updater-v0.5.1...enshwick-updater-v0.6.0) (2026-10-21)


###   BREAKING CHANGES

* **updater:** accept common GitHub release forms and unsigned updates ([#198](https://github.com/themaiby/enshwick/issues/198))
* **loader:** show only updates of installed mods on the Mods screen ([#196](https://github.com/themaiby/enshwick/issues/196))
* **api:** name, describe and credit mods, with recommends and breaks ([#126](https://github.com/themaiby/enshwick/issues/126))
* **api:** config stages, ranges, choices, schema and /config ([#130](https://github.com/themaiby/enshwick/issues/130))
* **api:** one naming scheme, run-time errors and named abi values ([#110](https://github.com/themaiby/enshwick/issues/110))
* consolidate into Enshwick Loader, one API crate and one tool ([#85](https://github.com/themaiby/enshwick/issues/85))

### Features

* add the updater mod and report a server's missing mods ([#65](https://github.com/themaiby/enshwick/issues/65)) ([13dfe21](https://github.com/themaiby/enshwick/commit/13dfe21934d5e903aa4aeea56c7450e62e2963c4))
* **api:** config stages, ranges, choices, schema and /config ([#130](https://github.com/themaiby/enshwick/issues/130)) ([8a19e89](https://github.com/themaiby/enshwick/commit/8a19e89afe6ac74d09d9a32c66b1fc133e81bc68))
* **api:** draw with the game's own widgets and show its dialogs ([#129](https://github.com/themaiby/enshwick/issues/129)) ([8601c70](https://github.com/themaiby/enshwick/commit/8601c70f8a0678a50f41301467d713bf41fab855))
* **api:** name, describe and credit mods, with recommends and breaks ([#126](https://github.com/themaiby/enshwick/issues/126)) ([edfb07c](https://github.com/themaiby/enshwick/commit/edfb07c59676c441f1e8b06ddc2791a80594ae6c))
* author keys: updates must be signed by the installed version's key ([#81](https://github.com/themaiby/enshwick/issues/81)) ([d9d46f3](https://github.com/themaiby/enshwick/commit/d9d46f38231234e958a8762e6c0fff5b6ddcb5d8))
* **loader:** add content packs of TOML files, signed and reloadable ([#158](https://github.com/themaiby/enshwick/issues/158)) ([7598b97](https://github.com/themaiby/enshwick/commit/7598b977434dfb207cd5c0d30c6cdd936c0cb0cc))
* **loader:** never start a mod that a renamed mod replaces ([#166](https://github.com/themaiby/enshwick/issues/166)) ([650993c](https://github.com/themaiby/enshwick/commit/650993c7b392be07fc16c4ca47925952c64f1487))
* **loader:** ship build tables as signed data with a pattern fallback ([#155](https://github.com/themaiby/enshwick/issues/155)) ([1df2e3f](https://github.com/themaiby/enshwick/commit/1df2e3fdcaeaeac3ca082a18976e6a3f1d3a46c9))
* **loader:** show mod catalogs with updates and mods on the Mods screen ([#180](https://github.com/themaiby/enshwick/issues/180)) ([2e93fb7](https://github.com/themaiby/enshwick/commit/2e93fb7ec219b7c4b4fcab0ff45dcd4c409340d6))
* **loader:** show only updates of installed mods on the Mods screen ([#196](https://github.com/themaiby/enshwick/issues/196)) ([aee82ac](https://github.com/themaiby/enshwick/commit/aee82acb3a6a0f9d8aa2ebbe414a7a31961c1cd7))
* **updater:** accept common GitHub release forms and unsigned updates ([#198](https://github.com/themaiby/enshwick/issues/198)) ([51d3e47](https://github.com/themaiby/enshwick/commit/51d3e4754a34496c5c90ab4b610f3621f0a92d85))
* **updater:** page through releases, word dialogs in the game language ([#170](https://github.com/themaiby/enshwick/issues/170)) ([c6bd27a](https://github.com/themaiby/enshwick/commit/c6bd27a947073a2e4a40dc822f2e3f64606c20a4))
* **updater:** read url(...) sources from a documented JSON format ([#77](https://github.com/themaiby/enshwick/issues/77)) ([a05aa2e](https://github.com/themaiby/enshwick/commit/a05aa2ed0c2838a5b3ff6a7adc2d06329d99eed1))


### Bug Fixes

* **mods:** audit fixes across every mod ([#94](https://github.com/themaiby/enshwick/issues/94)) ([e83b2d6](https://github.com/themaiby/enshwick/commit/e83b2d6d9f788f3cf9cc60d32fdcdb95196b76d4))
* **updater:** delete a renamed mod's old DLL after a fresh install ([#206](https://github.com/themaiby/enshwick/issues/206)) ([58d2134](https://github.com/themaiby/enshwick/commit/58d2134d700786f92cae1fd917998eac9376b1df))
* **updater:** never stage over an unlisted DLL or through path aliases ([#221](https://github.com/themaiby/enshwick/issues/221)) ([1b0ab4a](https://github.com/themaiby/enshwick/commit/1b0ab4af83230dde1a17c9e592b4f5e9c3687c9e))


### Other

* **api:** one naming scheme, run-time errors and named abi values ([#110](https://github.com/themaiby/enshwick/issues/110)) ([cbe72c5](https://github.com/themaiby/enshwick/commit/cbe72c5e92104d374272a5b192272e6e276dd37b))
* consolidate into Enshwick Loader, one API crate and one tool ([#85](https://github.com/themaiby/enshwick/issues/85)) ([5ddfde4](https://github.com/themaiby/enshwick/commit/5ddfde457d24f8e000d2dee1c74508f89582d526))
</details>

---
This PR was generated with [Release Please](https://github.com/googleapis/release-please). See [documentation](https://github.com/googleapis/release-please#release-please).