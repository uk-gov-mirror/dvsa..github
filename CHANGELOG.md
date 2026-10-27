# Changelog

## [8.0.0](https://github.com/uk-gov-mirror/dvsa..github/compare/v7.0.0...v8.0.0) (2026-10-27)


### ⚠ BREAKING CHANGES

* use the project's .nvmrc when no node-version is given ([#127](https://github.com/uk-gov-mirror/dvsa..github/issues/127))
* update upload and download artifact actions to latest ([#109](https://github.com/uk-gov-mirror/dvsa..github/issues/109))
* update setup-node action to latest ([#106](https://github.com/uk-gov-mirror/dvsa..github/issues/106))
* update cache action to latest ([#107](https://github.com/uk-gov-mirror/dvsa..github/issues/107))
* update configure-aws-credentials action to latest ([#104](https://github.com/uk-gov-mirror/dvsa..github/issues/104))
* Use latest versions ([#105](https://github.com/uk-gov-mirror/dvsa..github/issues/105))
* update checkout action to latest ([#102](https://github.com/uk-gov-mirror/dvsa..github/issues/102))
* update actions to node 20 ([#56](https://github.com/uk-gov-mirror/dvsa..github/issues/56))

### Features

* Add `--no-transfer-progress` to `mvn` command ([769984d](https://github.com/uk-gov-mirror/dvsa..github/commit/769984d4cc278eed6fbb3efd696104fd863ef9eb))
* add actions to .github repo ([#27](https://github.com/uk-gov-mirror/dvsa..github/issues/27)) ([b195ff6](https://github.com/uk-gov-mirror/dvsa..github/commit/b195ff6a9d67330a472d486af594186aba6fb574))
* Add display-jest-test-summary action  ([#43](https://github.com/uk-gov-mirror/dvsa..github/issues/43)) ([2d9e507](https://github.com/uk-gov-mirror/dvsa..github/commit/2d9e507dec2368efd1cb98983b5544d2e0b2f2db))
* Add extra info to README and fix indentation ([cbb5a31](https://github.com/uk-gov-mirror/dvsa..github/commit/cbb5a318a9270470e2f714b301fab421b811cbe2))
* add option to change composer package stability levels VOL-6497 ([#86](https://github.com/uk-gov-mirror/dvsa..github/issues/86)) ([796d22d](https://github.com/uk-gov-mirror/dvsa..github/commit/796d22d55dd8b12cf75cc8546f706388e6297995))
* add pass_percentage option to surefire report summary VOL-6038 ([#76](https://github.com/uk-gov-mirror/dvsa..github/issues/76)) ([29671fc](https://github.com/uk-gov-mirror/dvsa..github/commit/29671fccd0d9fc6e141bb30b72efb0f06308a80c))
* add reusable secrets-scan workflow + template ([60d5efe](https://github.com/uk-gov-mirror/dvsa..github/commit/60d5efe911f2c9082d07f87771952c17e4c4fe29))
* add reusable secrets-scan workflow + template ([a604392](https://github.com/uk-gov-mirror/dvsa..github/commit/a604392630e9b3b92461bc622318b801c0baea40))
* add support for no `max-warnings` ([#79](https://github.com/uk-gov-mirror/dvsa..github/issues/79)) ([66f3fa8](https://github.com/uk-gov-mirror/dvsa..github/commit/66f3fa8baab0c95faf1b840cf44afcdb54e5489e))
* add terraform static ([9226335](https://github.com/uk-gov-mirror/dvsa..github/commit/9226335d5c7db5ab5903d25ec86a14a352cee967))
* add workflow template to validate PR title ([#38](https://github.com/uk-gov-mirror/dvsa..github/issues/38)) ([d817033](https://github.com/uk-gov-mirror/dvsa..github/commit/d817033d602b2ab77718c1bf06d6097ab88482e1))
* added conventional-commits.yaml ([#84](https://github.com/uk-gov-mirror/dvsa..github/issues/84)) ([b18ce51](https://github.com/uk-gov-mirror/dvsa..github/commit/b18ce51e36460decc2def3a026891378db26b4e2))
* added optional tags to workflow ([cf1ca9f](https://github.com/uk-gov-mirror/dvsa..github/commit/cf1ca9fd489aaf883cb2ba73ecbeb20a94ba2ec3))
* added optional working directory ([#83](https://github.com/uk-gov-mirror/dvsa..github/issues/83)) ([fae1ef8](https://github.com/uk-gov-mirror/dvsa..github/commit/fae1ef8ca44dce48f13be6af3cef6639cc16c9bc))
* Added publish job step for optional downloading of previously built artefact ([a5e37dc](https://github.com/uk-gov-mirror/dvsa..github/commit/a5e37dc46f7f58fa70a198f082b688973fd3e0fe))
* added support for severity threshold for php-security ([#49](https://github.com/uk-gov-mirror/dvsa..github/issues/49)) ([fcbada1](https://github.com/uk-gov-mirror/dvsa..github/commit/fcbada149e522a791a74598e81029a5c77f17a02))
* BL-17232 add composer version as input to php actions ([#63](https://github.com/uk-gov-mirror/dvsa..github/issues/63)) ([499d241](https://github.com/uk-gov-mirror/dvsa..github/commit/499d241bc437f6513836937ae9473771f3926555))
* bump the version for the ci workflow ([#32](https://github.com/uk-gov-mirror/dvsa..github/issues/32)) ([ec4d90e](https://github.com/uk-gov-mirror/dvsa..github/commit/ec4d90e10c84d6ab8bb514c185fdd3a4bd4aad39))
* create npmjs publish workflow ([d546891](https://github.com/uk-gov-mirror/dvsa..github/commit/d546891f4b704e49358864f59539e04df2dec766))
* feature/promote php actions ([#23](https://github.com/uk-gov-mirror/dvsa..github/issues/23)) ([5899a5e](https://github.com/uk-gov-mirror/dvsa..github/commit/5899a5e32a8c6fef68365e6176da1a71b5c396d2))
* make maven step optional ([#118](https://github.com/uk-gov-mirror/dvsa..github/issues/118)) ([c0033c8](https://github.com/uk-gov-mirror/dvsa..github/commit/c0033c818828a377779a55e6c0bb77584125ecf7))
* New GitHub actions ([8f514cd](https://github.com/uk-gov-mirror/dvsa..github/commit/8f514cd65bd6e9f77bbd5f2776fa507363d14e33))
* New PR template ([909c34c](https://github.com/uk-gov-mirror/dvsa..github/commit/909c34c146e36e79adfa81375bc74f411ea76116))
* New workflow starter templates ([efa6ebc](https://github.com/uk-gov-mirror/dvsa..github/commit/efa6ebcf5f7f9f53cb87a3383da0e1c10c9cd42f))
* New workflow to Update Lambda Code on AWS ([a29337f](https://github.com/uk-gov-mirror/dvsa..github/commit/a29337fc459ad52addfbd7f8a86ed47d270c67d6))
* New workflow to upload build to s3 ([c7339e9](https://github.com/uk-gov-mirror/dvsa..github/commit/c7339e9f2c259962f37fc46fe50011900a727caa))
* php library workflows ([0b80022](https://github.com/uk-gov-mirror/dvsa..github/commit/0b8002294d317ec3cbacc43f5b297a5ea4e3177f))
* php-*tests allows definition of optional config and php-*static/tests support php versions ([#44](https://github.com/uk-gov-mirror/dvsa..github/issues/44)) ([161097f](https://github.com/uk-gov-mirror/dvsa..github/commit/161097f5e12c59e99c631779bb15a65199991da9))
* remove empty line in README.md ([#96](https://github.com/uk-gov-mirror/dvsa..github/issues/96)) ([e5c5262](https://github.com/uk-gov-mirror/dvsa..github/commit/e5c5262eb26d4fb73db130c31057f0bbdff043ee))
* RSP-2091 Optional tags in S3 Upload ([3d79994](https://github.com/uk-gov-mirror/dvsa..github/commit/3d799945f0e7bbbe0d56f0e51d51afc9795cf3fd))
* **secrets:** add step to configure aws credentials ([b3cde8a](https://github.com/uk-gov-mirror/dvsa..github/commit/b3cde8a661f2375d70fffc6de23454f2ee65771c))
* setup release please ([#93](https://github.com/uk-gov-mirror/dvsa..github/issues/93)) ([db31872](https://github.com/uk-gov-mirror/dvsa..github/commit/db318726e17cd58ea0cc9f73fdc60d80866db0a5))
* terraform static full scan for scheduling ([f62f4bd](https://github.com/uk-gov-mirror/dvsa..github/commit/f62f4bdf85f587f182560ec384d77673f1892f83))
* update actions to node 20 ([#56](https://github.com/uk-gov-mirror/dvsa..github/issues/56)) ([4d91508](https://github.com/uk-gov-mirror/dvsa..github/commit/4d91508c05b189d84939a69b4e4552be31e8c0b5))
* update cache action to latest ([#107](https://github.com/uk-gov-mirror/dvsa..github/issues/107)) ([cd4376d](https://github.com/uk-gov-mirror/dvsa..github/commit/cd4376d2da470ad1c9dede211bb2f7cd1af3b891))
* update cache action to latest ([#125](https://github.com/uk-gov-mirror/dvsa..github/issues/125)) ([75be4c6](https://github.com/uk-gov-mirror/dvsa..github/commit/75be4c649de7603ee0d0e3ebada9a8d4b61dec31))
* update checkout action to latest ([#102](https://github.com/uk-gov-mirror/dvsa..github/issues/102)) ([cf66f6e](https://github.com/uk-gov-mirror/dvsa..github/commit/cf66f6e938a7549370e13f1b6aa63d63bbb46788))
* update configure-aws-credentials action to latest ([#104](https://github.com/uk-gov-mirror/dvsa..github/issues/104)) ([46c8078](https://github.com/uk-gov-mirror/dvsa..github/commit/46c80788e650a39579364f7a1170dec3abb7a741))
* update graphql-action to latest ([#124](https://github.com/uk-gov-mirror/dvsa..github/issues/124)) ([0405a84](https://github.com/uk-gov-mirror/dvsa..github/commit/0405a84f1ee58df6f7683952af4b204274f607ee))
* Update matrix actions to add 'fail-fast' input ([#42](https://github.com/uk-gov-mirror/dvsa..github/issues/42)) ([b85ace6](https://github.com/uk-gov-mirror/dvsa..github/commit/b85ace6db21a8c948e3535cf42e2e57c76653efd))
* update references to latest major ([#101](https://github.com/uk-gov-mirror/dvsa..github/issues/101)) ([f6d4d75](https://github.com/uk-gov-mirror/dvsa..github/commit/f6d4d754f1017c80a7df7f18b6687edde534b16e))
* update setup-node action to latest ([#106](https://github.com/uk-gov-mirror/dvsa..github/issues/106)) ([f74c186](https://github.com/uk-gov-mirror/dvsa..github/commit/f74c186aa2da201c75c684b4efa9d28900f6ad05))
* update terraform action artifact custom name ([#82](https://github.com/uk-gov-mirror/dvsa..github/issues/82)) ([8074d1e](https://github.com/uk-gov-mirror/dvsa..github/commit/8074d1ee3110321283a5b2394453ba6cd6d22e75))
* update upload and download artifact actions to latest ([#109](https://github.com/uk-gov-mirror/dvsa..github/issues/109)) ([60784bf](https://github.com/uk-gov-mirror/dvsa..github/commit/60784bf9234fc195aa8c0d8401b7089f7f09d536))
* Updates for Node version deprecation warnings ([5e1b5b2](https://github.com/uk-gov-mirror/dvsa..github/commit/5e1b5b2af26334fe1399f7c345c55e55afa2fdd9))
* Use latest versions ([#105](https://github.com/uk-gov-mirror/dvsa..github/issues/105)) ([57cdcc3](https://github.com/uk-gov-mirror/dvsa..github/commit/57cdcc3ac1c22794feffade93d930109cfff6796))
* use the project's .nvmrc when no node-version is given ([#127](https://github.com/uk-gov-mirror/dvsa..github/issues/127)) ([09cae38](https://github.com/uk-gov-mirror/dvsa..github/commit/09cae381562e364de9b3c7a5f39f539aa6915423))


### Bug Fixes

* add additional workflow trigger and correct typo in run command ([68605c2](https://github.com/uk-gov-mirror/dvsa..github/commit/68605c27a6d1c4ccb3621b5e0badec897219d060))
* add env variable for trivy to prevent rate limit ([aabd0ee](https://github.com/uk-gov-mirror/dvsa..github/commit/aabd0ee613cdcfb20598a891bc958a0fa9c16399))
* add missing ext to fix pslam CI errors ([#62](https://github.com/uk-gov-mirror/dvsa..github/issues/62)) ([04529e3](https://github.com/uk-gov-mirror/dvsa..github/commit/04529e315a6c14637f73fb135d54d4a10afb23f6))
* add new versions to work flows ([#81](https://github.com/uk-gov-mirror/dvsa..github/issues/81)) ([1a956bc](https://github.com/uk-gov-mirror/dvsa..github/commit/1a956bc4ee8d71309437fe6b4ef580c0dae57673))
* address review — pin git-secrets, conditional fetch-depth, default-branch placeholder, pin reusable to v5.0.11 ([4fd6b80](https://github.com/uk-gov-mirror/dvsa..github/commit/4fd6b80fd95520ab5be247b51700a2a89a068072))
* Allow project path to be empty for whole repo. ([#73](https://github.com/uk-gov-mirror/dvsa..github/issues/73)) ([7dca3a1](https://github.com/uk-gov-mirror/dvsa..github/commit/7dca3a13a19534850a1cae160be44ebeb712c979))
* bump setup-terraform to v3 ([#60](https://github.com/uk-gov-mirror/dvsa..github/issues/60)) ([00117d1](https://github.com/uk-gov-mirror/dvsa..github/commit/00117d12768478aa3c4d6bca7488f4e0230f7d37))
* compile dist for pass-percentage feature ([abd6eb7](https://github.com/uk-gov-mirror/dvsa..github/commit/abd6eb77eefe1b1543aaa0174f90f2ff10e1c29b))
* conventional commits workflow ([#122](https://github.com/uk-gov-mirror/dvsa..github/issues/122)) ([f980d21](https://github.com/uk-gov-mirror/dvsa..github/commit/f980d21d822a8db9a946259fb7cdc5b0df5293a8))
* error in step sequencing for tfformat ([22a01ab](https://github.com/uk-gov-mirror/dvsa..github/commit/22a01ab6630038bdd63c06e6a4e85aaad81823ec))
* fix broken links in README.md ([#46](https://github.com/uk-gov-mirror/dvsa..github/issues/46)) ([baa92f7](https://github.com/uk-gov-mirror/dvsa..github/commit/baa92f7c6c2b9bc851bee98fc6a91e75374bba0e))
* Fix env var for GitHub repo name ([633d5fd](https://github.com/uk-gov-mirror/dvsa..github/commit/633d5fdb7b6936931ad552efa5e54dafee0d55a2))
* fix workflow template ([#30](https://github.com/uk-gov-mirror/dvsa..github/issues/30)) ([d237a36](https://github.com/uk-gov-mirror/dvsa..github/commit/d237a36c86dabb6bf973a5604fe2f83782965994))
* linting workflow when using biome ([9aa8df9](https://github.com/uk-gov-mirror/dvsa..github/commit/9aa8df97b50989cfefd5fa4e6a67a8480b3b4d45))
* linting workflow when using biome ([283aca9](https://github.com/uk-gov-mirror/dvsa..github/commit/283aca920b6615f3f24564e31df0e3b3ee0c60ba))
* Release Please configuration ([#99](https://github.com/uk-gov-mirror/dvsa..github/issues/99)) ([12960c8](https://github.com/uk-gov-mirror/dvsa..github/commit/12960c8c987034e65121510b845f81ffa525f85a))
* Remove `.zip` from pretty branch name ([cdaf881](https://github.com/uk-gov-mirror/dvsa..github/commit/cdaf8818fff3f8b63a11ba1271ead0c121d8ceee))
* Stop outputting Lambda Update Code output ([d9d18f5](https://github.com/uk-gov-mirror/dvsa..github/commit/d9d18f55249ce2339f0a45b23e0acfbd175f4515))
* template fix and updating readme to latest version ([0d4b422](https://github.com/uk-gov-mirror/dvsa..github/commit/0d4b42252fa87a71ad8327f8361e7e7fe7c27855))
* Update path for TF artifacts archiving ([#78](https://github.com/uk-gov-mirror/dvsa..github/issues/78)) ([a332141](https://github.com/uk-gov-mirror/dvsa..github/commit/a33214109186b01363cd48386745004abb079072))
* Update workflow names ([6c5fe0d](https://github.com/uk-gov-mirror/dvsa..github/commit/6c5fe0de6ba20063dee77baecdc0d89368626627))


### Documentation

* tweaking README formatting for readability ([cea87e7](https://github.com/uk-gov-mirror/dvsa..github/commit/cea87e7f9087d06abf81083b247fa07e1f7247a8))
* update readme ([#58](https://github.com/uk-gov-mirror/dvsa..github/issues/58)) ([1042b85](https://github.com/uk-gov-mirror/dvsa..github/commit/1042b85a611f42d63ec3e269e5dad207c831ac8a))
* update readme to use release v4.0.1 ([#59](https://github.com/uk-gov-mirror/dvsa..github/issues/59)) ([5b99675](https://github.com/uk-gov-mirror/dvsa..github/commit/5b99675a46f4e334b42ff2fc85f519bf008ee55a))
* updated README to document latest changes, punctuation fixes ([b8e2e29](https://github.com/uk-gov-mirror/dvsa..github/commit/b8e2e29250cce89963c669aeacc45e0949a44494))


### Miscellaneous

* add .editorconfig ([#111](https://github.com/uk-gov-mirror/dvsa..github/issues/111)) ([eb60cbf](https://github.com/uk-gov-mirror/dvsa..github/commit/eb60cbfb68d1f8ffdb57766004c9fc4d01044c46))
* add some shared actions into shared gh repo ([#71](https://github.com/uk-gov-mirror/dvsa..github/issues/71)) ([d4f5cee](https://github.com/uk-gov-mirror/dvsa..github/commit/d4f5cee61ec51b93fabc0807ee7bef8c6d4e4fde))
* bump surefire-report-summary action and test workflow to Node 24 ([#98](https://github.com/uk-gov-mirror/dvsa..github/issues/98)) ([a226fa5](https://github.com/uk-gov-mirror/dvsa..github/commit/a226fa52aa83be9007b7c068cd22bf3b81afc929))
* **cb2-21380:** update checkout to version 6 ([441c489](https://github.com/uk-gov-mirror/dvsa..github/commit/441c489ed5deef4e84106f36eff9b08ec0cd8471))
* **cb2-21380:** update checkout version ([1d27153](https://github.com/uk-gov-mirror/dvsa..github/commit/1d27153db3a147d10c487efa79061bc28dd9205a))
* **main:** release 5.1.0 ([#94](https://github.com/uk-gov-mirror/dvsa..github/issues/94)) ([0a7b0da](https://github.com/uk-gov-mirror/dvsa..github/commit/0a7b0dae3d78d5f294f0e33e67e750557589f821))
* **main:** release 5.2.0 ([#97](https://github.com/uk-gov-mirror/dvsa..github/issues/97)) ([f945a4f](https://github.com/uk-gov-mirror/dvsa..github/commit/f945a4f2e9a41751c24d464fc4ddb3b0b5a658bf))
* **main:** release 5.3.0 ([#100](https://github.com/uk-gov-mirror/dvsa..github/issues/100)) ([cf043af](https://github.com/uk-gov-mirror/dvsa..github/commit/cf043af2a20762554bc3ff1848d2cc82b89c4f12))
* **main:** release 6.0.0 ([#103](https://github.com/uk-gov-mirror/dvsa..github/issues/103)) ([f4efb2c](https://github.com/uk-gov-mirror/dvsa..github/commit/f4efb2c15fe391aeb7f5fa472c1569dd00a0648a))
* **main:** release 6.1.0 ([#119](https://github.com/uk-gov-mirror/dvsa..github/issues/119)) ([e749f56](https://github.com/uk-gov-mirror/dvsa..github/commit/e749f563a29af5a6cfe84a2f6c52fe131ff4aa09))
* **main:** release 6.1.1 ([#120](https://github.com/uk-gov-mirror/dvsa..github/issues/120)) ([97e7d2d](https://github.com/uk-gov-mirror/dvsa..github/commit/97e7d2d064b855c85cd4dcf3adb26003e89cbe7a))
* **main:** release 6.1.2 ([#123](https://github.com/uk-gov-mirror/dvsa..github/issues/123)) ([39badda](https://github.com/uk-gov-mirror/dvsa..github/commit/39badda1ab1dac5067813dd4646725773c2e6d81))
* **main:** release 6.2.0 ([#126](https://github.com/uk-gov-mirror/dvsa..github/issues/126)) ([1ed2aa4](https://github.com/uk-gov-mirror/dvsa..github/commit/1ed2aa439986ee10c92217744caf9f77705f5362))
* **main:** release 7.0.0 ([#128](https://github.com/uk-gov-mirror/dvsa..github/issues/128)) ([fa509b1](https://github.com/uk-gov-mirror/dvsa..github/commit/fa509b159d1f679b657a906673b3cf75518a7c07))
* Prepare v6 for release ([#108](https://github.com/uk-gov-mirror/dvsa..github/issues/108)) ([378869d](https://github.com/uk-gov-mirror/dvsa..github/commit/378869d09e09d666f1c487ae1d5487b65aae556d))
* prepare v7 for release ([#129](https://github.com/uk-gov-mirror/dvsa..github/issues/129)) ([452757a](https://github.com/uk-gov-mirror/dvsa..github/commit/452757a8817db11fd79c1edfa7f600ab8e2614c2))
* remove trivy ([45f9cdd](https://github.com/uk-gov-mirror/dvsa..github/commit/45f9cddf270cc55e807577677101cc82fc39083d))
* remove trivy ([dfa3688](https://github.com/uk-gov-mirror/dvsa..github/commit/dfa3688deef9fca495bc48135aaac39f1bd51280))
* update checkout version ([788ed92](https://github.com/uk-gov-mirror/dvsa..github/commit/788ed929f4b9c3f11f1b9cc5dd3b49605b3d716a))


### Build System

* compile dist for pass-percentage feature ([f424057](https://github.com/uk-gov-mirror/dvsa..github/commit/f4240577ebd32c72a637dedcb2b53d196e181fbc))
* **deps:** bump 1arp/create-a-file-action from 0.4.5 to 0.4.6 ([#116](https://github.com/uk-gov-mirror/dvsa..github/issues/116)) ([863384f](https://github.com/uk-gov-mirror/dvsa..github/commit/863384fee6db412e9246ce0964baa6ae3ce6cdc9))
* **deps:** bump actions/setup-java from 4 to 5 ([#115](https://github.com/uk-gov-mirror/dvsa..github/issues/115)) ([72819e2](https://github.com/uk-gov-mirror/dvsa..github/commit/72819e2488bccc6fa16c06e11d588112901ba39f))
* **deps:** bump actions/setup-java from 5 to 6 ([#121](https://github.com/uk-gov-mirror/dvsa..github/issues/121)) ([41d9225](https://github.com/uk-gov-mirror/dvsa..github/commit/41d9225d583e8837d52cc20ae12745352edfbd52))
* **deps:** bump github/codeql-action from 2 to 4 ([#113](https://github.com/uk-gov-mirror/dvsa..github/issues/113)) ([53722da](https://github.com/uk-gov-mirror/dvsa..github/commit/53722da9b49fbe632bb42317154c12e9320d9bca))
* **deps:** bump googleapis/release-please-action from 4 to 5 ([#112](https://github.com/uk-gov-mirror/dvsa..github/issues/112)) ([b880f3d](https://github.com/uk-gov-mirror/dvsa..github/commit/b880f3d7d78e944d423451fa3f834f3a4e90c3b3))
* **deps:** bump terraform-linters/setup-tflint from 4 to 6 ([#117](https://github.com/uk-gov-mirror/dvsa..github/issues/117)) ([f1c4077](https://github.com/uk-gov-mirror/dvsa..github/commit/f1c407727bf8569fd3c7bd2f3bb9981f49bd4728))
* **deps:** bump tj-actions/changed-files from 45 to 47 ([#114](https://github.com/uk-gov-mirror/dvsa..github/issues/114)) ([a28df4f](https://github.com/uk-gov-mirror/dvsa..github/commit/a28df4fe74491b02a0c919d01f454c3636b93d49))


### Continuous Integration

* escape user input in workflow ([#29](https://github.com/uk-gov-mirror/dvsa..github/issues/29)) ([0d94161](https://github.com/uk-gov-mirror/dvsa..github/commit/0d94161f5c820d96619104852e084eede7d17f74))
* setup dependabot ([#110](https://github.com/uk-gov-mirror/dvsa..github/issues/110)) ([d92ee4e](https://github.com/uk-gov-mirror/dvsa..github/commit/d92ee4e9b11d693bf7db33e26c36268b602bacf5))

## [7.0.0](https://github.com/dvsa/.github/compare/v6.2.0...v7.0.0) (2026-10-27)


### ⚠ BREAKING CHANGES

* use the project's .nvmrc when no node-version is given ([#127](https://github.com/dvsa/.github/issues/127))

### Features

* use the project's .nvmrc when no node-version is given ([#127](https://github.com/dvsa/.github/issues/127)) ([09cae38](https://github.com/dvsa/.github/commit/09cae381562e364de9b3c7a5f39f539aa6915423))


### Miscellaneous

* add .editorconfig ([#111](https://github.com/dvsa/.github/issues/111)) ([eb60cbf](https://github.com/dvsa/.github/commit/eb60cbfb68d1f8ffdb57766004c9fc4d01044c46))
* prepare v7 for release ([#129](https://github.com/dvsa/.github/issues/129)) ([452757a](https://github.com/dvsa/.github/commit/452757a8817db11fd79c1edfa7f600ab8e2614c2))


### Build System

* **deps:** bump actions/setup-java from 5 to 6 ([#121](https://github.com/dvsa/.github/issues/121)) ([41d9225](https://github.com/dvsa/.github/commit/41d9225d583e8837d52cc20ae12745352edfbd52))

## [6.2.0](https://github.com/dvsa/.github/compare/v6.1.2...v6.2.0) (2026-09-17)


### Features

* update cache action to latest ([#125](https://github.com/dvsa/.github/issues/125)) ([75be4c6](https://github.com/dvsa/.github/commit/75be4c649de7603ee0d0e3ebada9a8d4b61dec31))
* update graphql-action to latest ([#124](https://github.com/dvsa/.github/issues/124)) ([0405a84](https://github.com/dvsa/.github/commit/0405a84f1ee58df6f7683952af4b204274f607ee))

## [6.1.2](https://github.com/dvsa/.github/compare/v6.1.1...v6.1.2) (2026-09-08)


### Bug Fixes

* conventional commits workflow ([#122](https://github.com/dvsa/.github/issues/122)) ([f980d21](https://github.com/dvsa/.github/commit/f980d21d822a8db9a946259fb7cdc5b0df5293a8))

## [6.1.1](https://github.com/dvsa/.github/compare/v6.1.0...v6.1.1) (2026-08-19)


### Miscellaneous

* bump surefire-report-summary action and test workflow to Node 24 ([#98](https://github.com/dvsa/.github/issues/98)) ([a226fa5](https://github.com/dvsa/.github/commit/a226fa52aa83be9007b7c068cd22bf3b81afc929))

## [6.1.0](https://github.com/dvsa/.github/compare/v6.0.0...v6.1.0) (2026-08-18)


### Features

* make maven step optional ([#118](https://github.com/dvsa/.github/issues/118)) ([c0033c8](https://github.com/dvsa/.github/commit/c0033c818828a377779a55e6c0bb77584125ecf7))

## [6.0.0](https://github.com/dvsa/.github/compare/v5.3.0...v6.0.0) (2026-08-12)


### ⚠ BREAKING CHANGES

* update upload and download artifact actions to latest ([#109](https://github.com/dvsa/.github/issues/109))
* update setup-node action to latest ([#106](https://github.com/dvsa/.github/issues/106))
* update cache action to latest ([#107](https://github.com/dvsa/.github/issues/107))
* update configure-aws-credentials action to latest ([#104](https://github.com/dvsa/.github/issues/104))
* Use latest versions ([#105](https://github.com/dvsa/.github/issues/105))
* update checkout action to latest ([#102](https://github.com/dvsa/.github/issues/102))

### Features

* update cache action to latest ([#107](https://github.com/dvsa/.github/issues/107)) ([cd4376d](https://github.com/dvsa/.github/commit/cd4376d2da470ad1c9dede211bb2f7cd1af3b891))
* update checkout action to latest ([#102](https://github.com/dvsa/.github/issues/102)) ([cf66f6e](https://github.com/dvsa/.github/commit/cf66f6e938a7549370e13f1b6aa63d63bbb46788))
* update configure-aws-credentials action to latest ([#104](https://github.com/dvsa/.github/issues/104)) ([46c8078](https://github.com/dvsa/.github/commit/46c80788e650a39579364f7a1170dec3abb7a741))
* update setup-node action to latest ([#106](https://github.com/dvsa/.github/issues/106)) ([f74c186](https://github.com/dvsa/.github/commit/f74c186aa2da201c75c684b4efa9d28900f6ad05))
* update upload and download artifact actions to latest ([#109](https://github.com/dvsa/.github/issues/109)) ([60784bf](https://github.com/dvsa/.github/commit/60784bf9234fc195aa8c0d8401b7089f7f09d536))
* Use latest versions ([#105](https://github.com/dvsa/.github/issues/105)) ([57cdcc3](https://github.com/dvsa/.github/commit/57cdcc3ac1c22794feffade93d930109cfff6796))


### Miscellaneous

* Prepare v6 for release ([#108](https://github.com/dvsa/.github/issues/108)) ([378869d](https://github.com/dvsa/.github/commit/378869d09e09d666f1c487ae1d5487b65aae556d))


### Build System

* **deps:** bump 1arp/create-a-file-action from 0.4.5 to 0.4.6 ([#116](https://github.com/dvsa/.github/issues/116)) ([863384f](https://github.com/dvsa/.github/commit/863384fee6db412e9246ce0964baa6ae3ce6cdc9))
* **deps:** bump actions/setup-java from 4 to 5 ([#115](https://github.com/dvsa/.github/issues/115)) ([72819e2](https://github.com/dvsa/.github/commit/72819e2488bccc6fa16c06e11d588112901ba39f))
* **deps:** bump github/codeql-action from 2 to 4 ([#113](https://github.com/dvsa/.github/issues/113)) ([53722da](https://github.com/dvsa/.github/commit/53722da9b49fbe632bb42317154c12e9320d9bca))
* **deps:** bump googleapis/release-please-action from 4 to 5 ([#112](https://github.com/dvsa/.github/issues/112)) ([b880f3d](https://github.com/dvsa/.github/commit/b880f3d7d78e944d423451fa3f834f3a4e90c3b3))
* **deps:** bump terraform-linters/setup-tflint from 4 to 6 ([#117](https://github.com/dvsa/.github/issues/117)) ([f1c4077](https://github.com/dvsa/.github/commit/f1c407727bf8569fd3c7bd2f3bb9981f49bd4728))
* **deps:** bump tj-actions/changed-files from 45 to 47 ([#114](https://github.com/dvsa/.github/issues/114)) ([a28df4f](https://github.com/dvsa/.github/commit/a28df4fe74491b02a0c919d01f454c3636b93d49))


### Continuous Integration

* setup dependabot ([#110](https://github.com/dvsa/.github/issues/110)) ([d92ee4e](https://github.com/dvsa/.github/commit/d92ee4e9b11d693bf7db33e26c36268b602bacf5))

## [5.3.0](https://github.com/dvsa/.github/compare/v5.2.0...v5.3.0) (2026-08-10)


### Features

* update references to latest major ([#101](https://github.com/dvsa/.github/issues/101)) ([f6d4d75](https://github.com/dvsa/.github/commit/f6d4d754f1017c80a7df7f18b6687edde534b16e))


### Bug Fixes

* Release Please configuration ([#99](https://github.com/dvsa/.github/issues/99)) ([12960c8](https://github.com/dvsa/.github/commit/12960c8c987034e65121510b845f81ffa525f85a))

## [5.2.0](https://github.com/dvsa/.github/compare/v5.1.0...v5.2.0) (2026-05-14)


### Features

* remove empty line in README.md ([#96](https://github.com/dvsa/.github/issues/96)) ([e5c5262](https://github.com/dvsa/.github/commit/e5c5262eb26d4fb73db130c31057f0bbdff043ee))

## [5.1.0](https://github.com/dvsa/.github/compare/v5.0.11...v5.1.0) (2026-05-13)


### Features

* setup release please ([#93](https://github.com/dvsa/.github/issues/93)) ([db31872](https://github.com/dvsa/.github/commit/db318726e17cd58ea0cc9f73fdc60d80866db0a5))
