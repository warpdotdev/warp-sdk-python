# Changelog

## 0.4.0 (2026-01-29)

Full Changelog: [v0.3.0...v0.4.0](https://github.com/warpdotdev/warp-sdk-python/compare/v0.3.0...v0.4.0)

### ⚠ BREAKING CHANGES

* **api:** catch up openapi, rename tasks -> runs

### Features

* **api:** add artifacts, worker_host, and new source types ([4aa1225](https://github.com/warpdotdev/warp-sdk-python/commit/4aa12253c3cd40bbd8460dfe6602fed5080554a4))
* **api:** catch up openapi, rename tasks -&gt; runs ([fe8c5b3](https://github.com/warpdotdev/warp-sdk-python/commit/fe8c5b3f2da07a415ecd21d0f1ae5985e45f1a4d))
* **api:** created at filter in list view ([71adb45](https://github.com/warpdotdev/warp-sdk-python/commit/71adb45481ca3248d892e62ff767b9ea011e7f21))
* **client:** add custom JSON encoder for extended type support ([68f4b61](https://github.com/warpdotdev/warp-sdk-python/commit/68f4b61fd83b1f5576b72ad6ea3a28cd58e06a68))
* **client:** add support for binary request streaming ([c64e6c4](https://github.com/warpdotdev/warp-sdk-python/commit/c64e6c44b6d02a63609d02f4976a7977dc3b0045))


### Chores

* **ci:** upgrade `actions/github-script` ([713ae7d](https://github.com/warpdotdev/warp-sdk-python/commit/713ae7d03ee5f04eeac42b9a213d96ccc91d06d7))
* **internal:** update `actions/checkout` version ([fd0a90f](https://github.com/warpdotdev/warp-sdk-python/commit/fd0a90fae32b8a7e352217e3672e63b9b4dbc594))


### Documentation

* **dev:** Add WARP.md file ([7f1b835](https://github.com/warpdotdev/warp-sdk-python/commit/7f1b835240574dc517d424dca84251f86c4b1276))

## 0.3.0 (2026-01-05)

Full Changelog: [v0.2.1...v0.3.0](https://github.com/warpdotdev/warp-sdk-python/compare/v0.2.1...v0.3.0)

### Features

* **api:** fix array query parameter formatting ([d1a1243](https://github.com/warpdotdev/warp-sdk-python/commit/d1a1243a0ab6b853b2340f8e7d3652bfe05ded20))

## 0.2.1 (2025-12-19)

Full Changelog: [v0.2.0...v0.2.1](https://github.com/warpdotdev/warp-sdk-python/compare/v0.2.0...v0.2.1)

### Bug Fixes

* use async_to_httpx_files in patch method ([c02afdb](https://github.com/warpdotdev/warp-sdk-python/commit/c02afdbec958df84a3e1ec73e213e683c79b04e8))


### Chores

* **internal:** add `--fix` argument to lint script ([46a9b4b](https://github.com/warpdotdev/warp-sdk-python/commit/46a9b4bdceac62a8939f66b0227943d18db5393f))

## 0.2.0 (2025-12-17)

Full Changelog: [v0.1.1...v0.2.0](https://github.com/warpdotdev/warp-sdk-python/compare/v0.1.1...v0.2.0)

### Features

* **api:** manual updates ([2fc23de](https://github.com/warpdotdev/warp-sdk-python/commit/2fc23de0e1d42443e691350804605243c5902026))


### Chores

* update SDK settings ([a94be20](https://github.com/warpdotdev/warp-sdk-python/commit/a94be20a45967c6ec5bd95dcc3ffcf457db84305))

## 0.1.1 (2025-12-17)

Full Changelog: [v0.1.0...v0.1.1](https://github.com/warpdotdev/warp-sdk-python/compare/v0.1.0...v0.1.1)

### Documentation

* add environment and config usage documentation ([487b1cf](https://github.com/warpdotdev/warp-sdk-python/commit/487b1cfac5fcd89d4c91f88903ef8b601da8269d))

## 0.1.0 (2025-12-17)

Full Changelog: [v0.0.1...v0.1.0](https://github.com/warpdotdev/warp-sdk-python/compare/v0.0.1...v0.1.0)

### Features

* **api:** manual updates ([4d4a408](https://github.com/warpdotdev/warp-sdk-python/commit/4d4a4082d453daeb3d388ac1a23cf951ada27a9e))
* **api:** manual updates ([cd0ec74](https://github.com/warpdotdev/warp-sdk-python/commit/cd0ec747479cbb56159a361853787871c1c61395))


### Chores

* **internal:** add missing files argument to base client ([041d054](https://github.com/warpdotdev/warp-sdk-python/commit/041d0540f460ed7ecee3ed66a8db6ea9ae607360))
* speedup initial import ([c6fa047](https://github.com/warpdotdev/warp-sdk-python/commit/c6fa04747ba3b056f9dff28e564e25b4e257ca5e))
* update SDK settings ([217b866](https://github.com/warpdotdev/warp-sdk-python/commit/217b866ef03a583415f0fcdd65385ee76d53c664))
* update SDK settings ([cc95759](https://github.com/warpdotdev/warp-sdk-python/commit/cc9575998cf34b016f70f8209043a02ad1677399))


### Refactors

* **internal:** switch from rye to uv ([d4cdfd0](https://github.com/warpdotdev/warp-sdk-python/commit/d4cdfd0384b63f1ce244cdbb4327043cff02f682))
