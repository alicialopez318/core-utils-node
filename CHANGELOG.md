# Changelog

## 1.28.0 (2022-11-02)


### ⚠ BREAKING CHANGES

* **ci:** Removed support for Node.js 12 and 17.
* **ci:** Removed support for Node.js 10 and 15.

### Features

* add --since option to ncu-ci ([#649](https://github.com/alicialopez318/core-utils-node/issues/649)) ([c460a2c](https://github.com/alicialopez318/core-utils-node/commit/c460a2c712b366e3007fc731098d6294a1f91379))
* add auto run v8 ci ([e40421b](https://github.com/alicialopez318/core-utils-node/commit/e40421b7d8b0ad7ad903b5c06e89441587922488))
* add ncu-ci cigtm &lt;jobid&gt; ([#454](https://github.com/alicialopez318/core-utils-node/issues/454)) ([9dee734](https://github.com/alicialopez318/core-utils-node/commit/9dee7347cd12a455462372be9f8cbdb73e2d9fbe))
* allow citgm job comparison ([#455](https://github.com/alicialopez318/core-utils-node/issues/455)) ([3beeeed](https://github.com/alicialopez318/core-utils-node/commit/3beeeed6293ccbd5b54a9a3da1f1f2639e452adf))
* allow to fixup everything into first commit with fixupAll ([dd46d82](https://github.com/alicialopez318/core-utils-node/commit/dd46d828b7f67e340914d3d7515b510d30a11774))
* automate creation of the first LTS release ([#514](https://github.com/alicialopez318/core-utils-node/issues/514)) ([a25d5d4](https://github.com/alicialopez318/core-utils-node/commit/a25d5d4229ba02a732cb48ec4df0a0fb30905030))
* check Actions and handle doc-only changes ([1e76858](https://github.com/alicialopez318/core-utils-node/commit/1e76858b060f75e0bb741b8199d7277c0258b0e1))
* check CI failures before land ([#422](https://github.com/alicialopez318/core-utils-node/issues/422)) ([4b1e1ab](https://github.com/alicialopez318/core-utils-node/commit/4b1e1abc6bd07fea7a130d88327a7024fb9ce654))
* check commits after the last ci run ([#69](https://github.com/alicialopez318/core-utils-node/issues/69)) ([6d18104](https://github.com/alicialopez318/core-utils-node/commit/6d181046143ebada4341d453c550543b7b7e6d52))
* check fast-track approvals ([#588](https://github.com/alicialopez318/core-utils-node/issues/588)) ([7cf9f11](https://github.com/alicialopez318/core-utils-node/commit/7cf9f11de13a2416e5c72b7d09efb3e9053caa56))
* **cli:** prompt user when landing PR with several commits ([#572](https://github.com/alicialopez318/core-utils-node/issues/572)) ([9f47215](https://github.com/alicialopez318/core-utils-node/commit/9f47215b7d453e2cda0384dfeb0823e5728b9782))
* enable parsing citgm-nobuild jobs ([#458](https://github.com/alicialopez318/core-utils-node/issues/458)) ([efea6aa](https://github.com/alicialopez318/core-utils-node/commit/efea6aa545154d6805de6cbc828ec2382f74eec4))
* **git-node:** add git-node status ([fdd7242](https://github.com/alicialopez318/core-utils-node/commit/fdd7242af21d782e049e4d675ccd82b865b2bbef))
* handle unknown commands ([#387](https://github.com/alicialopez318/core-utils-node/issues/387)) ([9b97b49](https://github.com/alicialopez318/core-utils-node/commit/9b97b49b04cf2b00bee7c4bfc14bd560e776cf23))
* handle unmarked DEP0XXX tags during landing and release ([#420](https://github.com/alicialopez318/core-utils-node/issues/420)) ([fa04be3](https://github.com/alicialopez318/core-utils-node/commit/fa04be353a0f1e08c332c2267f42327edc57777f))
* implement autorebase for PRs with multiple commits ([58face5](https://github.com/alicialopez318/core-utils-node/commit/58face5a392a590d90db9290539a02e0a6d70438))
* **land:** avoid landing on the wrong default branch ([#586](https://github.com/alicialopez318/core-utils-node/issues/586)) ([6f18eab](https://github.com/alicialopez318/core-utils-node/commit/6f18eab80d41a23e0fde408219308772800419a5))
* make --checkCI optionable for git-node-land ([#528](https://github.com/alicialopez318/core-utils-node/issues/528)) ([fed3efa](https://github.com/alicialopez318/core-utils-node/commit/fed3efacb2f080b619ce97d043aca6533b2326fa))
* make lint check opt-in ([cf179f4](https://github.com/alicialopez318/core-utils-node/commit/cf179f46344761f783d335ce3cc704cf340b699c))
* merge update-v8 in the project ([#235](https://github.com/alicialopez318/core-utils-node/issues/235)) ([6605ce9](https://github.com/alicialopez318/core-utils-node/commit/6605ce96df55bd999419e38c2bbbb6d876f43a5e))
* prepare ncu for new README format ([#561](https://github.com/alicialopez318/core-utils-node/issues/561)) ([82ece70](https://github.com/alicialopez318/core-utils-node/commit/82ece708c73f9290279e93b83af11bb818bcec67))
* set error code in some failure cases ([#443](https://github.com/alicialopez318/core-utils-node/issues/443)) ([4f17a92](https://github.com/alicialopez318/core-utils-node/commit/4f17a92120c53de60538f77c052b5a021fc80ba6))
* spawn the user's editor to edit commit messages ([5f40861](https://github.com/alicialopez318/core-utils-node/commit/5f408610371c0c2fc888f67d5439d5b267c3885b))
* suggest `gh pr` commands to finish landing ([#583](https://github.com/alicialopez318/core-utils-node/issues/583)) ([8f40fda](https://github.com/alicialopez318/core-utils-node/commit/8f40fda49553ab46d17692f86ab7d922ad491302))
* support NCU_VERBOSITY=debug environment variable ([7187f10](https://github.com/alicialopez318/core-utils-node/commit/7187f10e49d78e015634feb369e7d94cfdd9d50b))
* support system proxy ([#408](https://github.com/alicialopez318/core-utils-node/issues/408)) ([ac73304](https://github.com/alicialopez318/core-utils-node/commit/ac7330432853ac7ec47a7a42db7106edaeff0dea))
* update CI requirements for landing pull requests ([#533](https://github.com/alicialopez318/core-utils-node/issues/533)) ([ae04eec](https://github.com/alicialopez318/core-utils-node/commit/ae04eec9807b57a9fbc3904cff242b0ece438c87))


### Bug Fixes

* accommodate case changes in README header ([fe8369c](https://github.com/alicialopez318/core-utils-node/commit/fe8369cf9a063f62ad4a5fedc3001835aff422f1))
* add a specific error message for the commit queue ([#645](https://github.com/alicialopez318/core-utils-node/issues/645)) ([623605e](https://github.com/alicialopez318/core-utils-node/commit/623605e8a02a65ec4fc1714998464fbf998f5aa6))
* add missing await ([#655](https://github.com/alicialopez318/core-utils-node/issues/655)) ([2510984](https://github.com/alicialopez318/core-utils-node/commit/2510984b8856f47018dc09ea6d3597828d239283))
* add missing comma in release commit title ([#403](https://github.com/alicialopez318/core-utils-node/issues/403)) ([3ba611a](https://github.com/alicialopez318/core-utils-node/commit/3ba611a617097c2f20d4c2aea11e9f43d33f87b3))
* add missing new line in changelog ([#591](https://github.com/alicialopez318/core-utils-node/issues/591)) ([d84826a](https://github.com/alicialopez318/core-utils-node/commit/d84826abe61c0ed0af2eee90a5303d8b0227f8ff))
* add trailing line feed to formatted JSON ([#623](https://github.com/alicialopez318/core-utils-node/issues/623)) ([a6ea773](https://github.com/alicialopez318/core-utils-node/commit/a6ea77314d1fd5552152228e760836cc92993dd6))
* allow opt-out of Fixes/Refs metadata ([#474](https://github.com/alicialopez318/core-utils-node/issues/474)) ([ba5f180](https://github.com/alicialopez318/core-utils-node/commit/ba5f1804c930bf7315bd36501dd48e40ec1da895))
* allow pending dependabot checks in PR checker ([2096c85](https://github.com/alicialopez318/core-utils-node/commit/2096c85114f8d0d5546ad55cb5b378e4230c9335))
* also exclude backport-open label from branch diff ([#440](https://github.com/alicialopez318/core-utils-node/issues/440)) ([90e8e7c](https://github.com/alicialopez318/core-utils-node/commit/90e8e7c59c04fbb319315749d6095ac7a5b40738))
* broken enquirer in listr2 ([#636](https://github.com/alicialopez318/core-utils-node/issues/636)) ([50533b9](https://github.com/alicialopez318/core-utils-node/commit/50533b9a05979eca0342f2de603a6240505bf226))
* check last fast-track request comment ([#606](https://github.com/alicialopez318/core-utils-node/issues/606)) ([5ffedf5](https://github.com/alicialopez318/core-utils-node/commit/5ffedf5688b772103b1794604b3001adc5527b98))
* check missing config in Session ctor ([#426](https://github.com/alicialopez318/core-utils-node/issues/426)) ([db658a0](https://github.com/alicialopez318/core-utils-node/commit/db658a09f46576136ab5aa9395eabab09be5c85e))
* **cli-separator:** negative value on a long text ([#553](https://github.com/alicialopez318/core-utils-node/issues/553)) ([9fa2bbb](https://github.com/alicialopez318/core-utils-node/commit/9fa2bbbaabc71f9bcdcb9bf1571ca70e26c3dac4))
* comply with markdown style guidelines ([e0e5986](https://github.com/alicialopez318/core-utils-node/commit/e0e59863f1e93b5e4396abc7017b3ebec92c2c46))
* **config:** add file path to error message when parsing fails ([#608](https://github.com/alicialopez318/core-utils-node/issues/608)) ([3967c0a](https://github.com/alicialopez318/core-utils-node/commit/3967c0a20922889038ac4578c229fd59940c60c5))
* correct for new execGitNode syntax ([#433](https://github.com/alicialopez318/core-utils-node/issues/433)) ([d0bb86e](https://github.com/alicialopez318/core-utils-node/commit/d0bb86e0966555828712646864049fd43831d651))
* correct username and token validation ([34e9b48](https://github.com/alicialopez318/core-utils-node/commit/34e9b48d2825faeec5baf661fa14f501d2942795))
* default date for release ([#419](https://github.com/alicialopez318/core-utils-node/issues/419)) ([860281e](https://github.com/alicialopez318/core-utils-node/commit/860281e02fdf4084543c11edb11d5c989a9c82e7))
* **deps:** revert to node-fetch ([#595](https://github.com/alicialopez318/core-utils-node/issues/595)) ([e726c20](https://github.com/alicialopez318/core-utils-node/commit/e726c20923b2dde4d24e5b6be978011537e16f10))
* display the correct amount of remaining time for fast-tracked PRs ([#581](https://github.com/alicialopez318/core-utils-node/issues/581)) ([8404236](https://github.com/alicialopez318/core-utils-node/commit/84042363d7a1ec4d359039cd1edbf1b24d17fd00))
* enforce default for non-confirmation prompts ([#415](https://github.com/alicialopez318/core-utils-node/issues/415)) ([6a18006](https://github.com/alicialopez318/core-utils-node/commit/6a1800618ec02dcfe01b3bc749f49f03fad2f3c0))
* ensure node-test-commit job id in daily-master ([#460](https://github.com/alicialopez318/core-utils-node/issues/460)) ([056cc8e](https://github.com/alicialopez318/core-utils-node/commit/056cc8e982859ba5b66354511c8bc92f4ec46a5d))
* fetch first 100 check suites in PR checker ([30e6295](https://github.com/alicialopez318/core-utils-node/commit/30e6295471ab90037d52f0e773b0310f818b6a71))
* fetch most recent 100 commits ([#520](https://github.com/alicialopez318/core-utils-node/issues/520)) ([4633a21](https://github.com/alicialopez318/core-utils-node/commit/4633a21291bdca8b47739e4a09ce2c76f1e20bd1))
* fixupAll flag should take precedence over autorebase ([#593](https://github.com/alicialopez318/core-utils-node/issues/593)) ([4ec8a66](https://github.com/alicialopez318/core-utils-node/commit/4ec8a66302d93316e9d78bdfdf395d2708520a1e))
* git node metadata arg passing ([#500](https://github.com/alicialopez318/core-utils-node/issues/500)) ([0c29be2](https://github.com/alicialopez318/core-utils-node/commit/0c29be267a3d83db9a43d51bc85b049062cc2c98))
* handle citgm failures better ([#497](https://github.com/alicialopez318/core-utils-node/issues/497)) ([3545cbe](https://github.com/alicialopez318/core-utils-node/commit/3545cbe831f2ac80019da9caf777df22d3a78d9e))
* https://github.com/nodejs/node-core-utils/issues/324 ([1e76858](https://github.com/alicialopez318/core-utils-node/commit/1e76858b060f75e0bb741b8199d7277c0258b0e1))
* https://github.com/nodejs/node-core-utils/issues/466 ([c33cef4](https://github.com/alicialopez318/core-utils-node/commit/c33cef44ceb6c8fcbf563aeb1500bd0cc0c3c695))
* https://github.com/nodejs/node/issues/29770 ([1e76858](https://github.com/alicialopez318/core-utils-node/commit/1e76858b060f75e0bb741b8199d7277c0258b0e1))
* https://github.com/nodejs/node/issues/32335 ([1e76858](https://github.com/alicialopez318/core-utils-node/commit/1e76858b060f75e0bb741b8199d7277c0258b0e1))
* landing when no Jenkins CI has been run for PR ([#451](https://github.com/alicialopez318/core-utils-node/issues/451)) ([df6d9d3](https://github.com/alicialopez318/core-utils-node/commit/df6d9d3843153c91c4ddc2461a695ce066ba471a))
* lint during the landing process ([#435](https://github.com/alicialopez318/core-utils-node/issues/435)) ([9a31dbb](https://github.com/alicialopez318/core-utils-node/commit/9a31dbbbe1d3bf27d945207faa4319409b63482f))
* LTS release commit should contain codename ([#401](https://github.com/alicialopez318/core-utils-node/issues/401)) ([2309ab9](https://github.com/alicialopez318/core-utils-node/commit/2309ab9858f234acf79163ea284b11a7a29fe8b1))
* only parse commit messages during git node backport analysis ([#651](https://github.com/alicialopez318/core-utils-node/issues/651)) ([3e6c792](https://github.com/alicialopez318/core-utils-node/commit/3e6c7921c6c188b45ef197d165bfcf22e37b2079))
* parse ci failure error ([#640](https://github.com/alicialopez318/core-utils-node/issues/640)) ([0470785](https://github.com/alicialopez318/core-utils-node/commit/0470785b9f39341d96175e9de1da4cc737e3c1db))
* **pr-checker:** shouldn't fail on SKIPPED ([3258433](https://github.com/alicialopez318/core-utils-node/commit/3258433337ebf64ac3afde9fc175a6d886cbc9d9))
* prepare for one last README change ([#578](https://github.com/alicialopez318/core-utils-node/issues/578)) ([6c32554](https://github.com/alicialopez318/core-utils-node/commit/6c3255415187e6f9961d1ceae27a29d2e15d83ef))
* prevent duplicate and self-refs ([#478](https://github.com/alicialopez318/core-utils-node/issues/478)) ([0003ab7](https://github.com/alicialopez318/core-utils-node/commit/0003ab741a2f359396caaa0b62534f2b4fed0378))
* print full command in case of failure ([#456](https://github.com/alicialopez318/core-utils-node/issues/456)) ([a3e7db3](https://github.com/alicialopez318/core-utils-node/commit/a3e7db383539618088f33f2a1dc79fc34a20a1c7))
* properly handle failure to start CI ([01a6c84](https://github.com/alicialopez318/core-utils-node/commit/01a6c8457e084411cca03a1d32634dceedbe676e))
* repo/path mismatch in v8 update ([#465](https://github.com/alicialopez318/core-utils-node/issues/465)) ([93b5ebf](https://github.com/alicialopez318/core-utils-node/commit/93b5ebffa638c500a95eab213efb896b4289f714))
* respect existing trailers in commit messages ([#632](https://github.com/alicialopez318/core-utils-node/issues/632)) ([5bda17d](https://github.com/alicialopez318/core-utils-node/commit/5bda17d0d5f452a761ca94561840b8a1cb9d0957))
* return value for validateLint ([#482](https://github.com/alicialopez318/core-utils-node/issues/482)) ([4457109](https://github.com/alicialopez318/core-utils-node/commit/4457109eb710c856feb8bccaf3797cb42fceceed))
* spacing in warnForWrongBranch() ([#448](https://github.com/alicialopez318/core-utils-node/issues/448)) ([7e02a95](https://github.com/alicialopez318/core-utils-node/commit/7e02a95eb447facb2878f29d71ed25513f698b72))
* throw on missing info during release prep ([#519](https://github.com/alicialopez318/core-utils-node/issues/519)) ([445cbb0](https://github.com/alicialopez318/core-utils-node/commit/445cbb0a8c69d271308f37e68efb278a853dcae9))
* undefined failures & JSON error ([b8efda7](https://github.com/alicialopez318/core-utils-node/commit/b8efda7906fbdad3a45dab32747e0572fab13b30))
* update detection of changelog links ([#573](https://github.com/alicialopez318/core-utils-node/issues/573)) ([575fd99](https://github.com/alicialopez318/core-utils-node/commit/575fd99985522b85aa8c1d0ee930a21fa2181aac))
* update detection of changelog links ([#587](https://github.com/alicialopez318/core-utils-node/issues/587)) ([497e188](https://github.com/alicialopez318/core-utils-node/commit/497e1888a4f22bdb1b70e1cf6b3ee0c3f054dd39))
* update detection of changelog links (take 2) ([#575](https://github.com/alicialopez318/core-utils-node/issues/575)) ([f834a32](https://github.com/alicialopez318/core-utils-node/commit/f834a3213c40b368310b990d3db4527525271aa7))
* update for recent changelog format change ([#576](https://github.com/alicialopez318/core-utils-node/issues/576)) ([bb68a88](https://github.com/alicialopez318/core-utils-node/commit/bb68a88b292a975c11f4271808d5d408e3314884))
* update permitted GitHub token characters ([d7119f1](https://github.com/alicialopez318/core-utils-node/commit/d7119f15eccca48ccb9808281618737ff37fc803))
* update proxy-agent to 5.0.0 ([#570](https://github.com/alicialopez318/core-utils-node/issues/570)) ([98f5625](https://github.com/alicialopez318/core-utils-node/commit/98f56257e37f2da8c6d20c9fbb3ab8a45c4ac9e3))
* **update-v8:** add abseil-cpp as a V8 dependency ([#565](https://github.com/alicialopez318/core-utils-node/issues/565)) ([92e7a5b](https://github.com/alicialopez318/core-utils-node/commit/92e7a5b620e7c59ee0cb0325a79656499a9f0807))
* **update-v8:** force-add all files after cloning V8 ([#549](https://github.com/alicialopez318/core-utils-node/issues/549)) ([2d3704b](https://github.com/alicialopez318/core-utils-node/commit/2d3704b4da4cc43b297c6d2595a08bd6d3b6a97c))
* **update-v8:** remove abseil-cpp from V8 dependencies ([#567](https://github.com/alicialopez318/core-utils-node/issues/567)) ([f2ceffc](https://github.com/alicialopez318/core-utils-node/commit/f2ceffc934b752ad8097bf70f45a512a708af9e8))
* use `getUrlFromOP()` for `fixes` links ([#614](https://github.com/alicialopez318/core-utils-node/issues/614)) ([1d8c865](https://github.com/alicialopez318/core-utils-node/commit/1d8c86530c9b1711738677e3211c72df536a8fe7))
* use 12 characters for commit SHAs ([#372](https://github.com/alicialopez318/core-utils-node/issues/372)) ([05bbc26](https://github.com/alicialopez318/core-utils-node/commit/05bbc260ec6b5581ab8893f81a5a4db711c70cec))
* use COMMIT_EDITMSG file name to edit commits ([9dae439](https://github.com/alicialopez318/core-utils-node/commit/9dae439412eebf34b6a94fdcc928c8b8681556ff))
* use git apply not system apply in v8 backport ([#432](https://github.com/alicialopez318/core-utils-node/issues/432)) ([d477123](https://github.com/alicialopez318/core-utils-node/commit/d477123fa0568b6d0e4c8532eb191ee9e4958372))
* use plaintext formatting in release commit ([#417](https://github.com/alicialopez318/core-utils-node/issues/417)) ([adaf274](https://github.com/alicialopez318/core-utils-node/commit/adaf2746aa429553340edfe177d5c584d0b04b67))
* use res.arrayBuffer() instead of res.buffer() ([#624](https://github.com/alicialopez318/core-utils-node/issues/624)) ([5d32ca4](https://github.com/alicialopez318/core-utils-node/commit/5d32ca42dacd41f00abad499a8bacd06c203fba6))
* **v8:** correct order of ternary ([#513](https://github.com/alicialopez318/core-utils-node/issues/513)) ([e3e8450](https://github.com/alicialopez318/core-utils-node/commit/e3e845002f1d9e7ad11a9f5f2b452e33b7278748))
* **v8:** support non-relative paths in V8 DEPS ([#471](https://github.com/alicialopez318/core-utils-node/issues/471)) ([ded3b98](https://github.com/alicialopez318/core-utils-node/commit/ded3b98a556b25487a72f9e86cb3a2d3f8e999ea))
* **v8:** use V8's main branch ([#555](https://github.com/alicialopez318/core-utils-node/issues/555)) ([f4b56fb](https://github.com/alicialopez318/core-utils-node/commit/f4b56fbfeb19ee085e3771fc18dba54b9debd5f0))
* validate ncu-ci args ([#411](https://github.com/alicialopez318/core-utils-node/issues/411)) ([58bdf05](https://github.com/alicialopez318/core-utils-node/commit/58bdf053c779b756df436b03596dcdd561e446dc))
* warn on whitespace during landing ([#438](https://github.com/alicialopez318/core-utils-node/issues/438)) ([5a48591](https://github.com/alicialopez318/core-utils-node/commit/5a48591761277ff38244b75c02ca9d35db061a1d))
* **wpt:** download files as buffer instead of text ([#535](https://github.com/alicialopez318/core-utils-node/issues/535)) ([444d229](https://github.com/alicialopez318/core-utils-node/commit/444d229397abdf6f4594e2dd0d9309eb08e32177))
* **wpt:** order version keys alphabetically ([#536](https://github.com/alicialopez318/core-utils-node/issues/536)) ([e9f5b65](https://github.com/alicialopez318/core-utils-node/commit/e9f5b65f1576a5c030f415dd8e69852bc34c1436))
* write file to the current folder ([#434](https://github.com/alicialopez318/core-utils-node/issues/434)) ([9dccf82](https://github.com/alicialopez318/core-utils-node/commit/9dccf82c2794433002293dd9b5beb2db653fe009))


### Miscellaneous Chores

* **ci:** test on supported Node.js versions ([ad142f4](https://github.com/alicialopez318/core-utils-node/commit/ad142f4086da64a45f5c4a8f299b6483e13ea8c4))
* **ci:** test on supported Node.js versions ([3abcd8f](https://github.com/alicialopez318/core-utils-node/commit/3abcd8f658ab4ef7f4b4321fde1a3fa5813ead2c))
* release 1.28.0 ([0ffc97b](https://github.com/alicialopez318/core-utils-node/commit/0ffc97bab2f9dc5d7f3108aad9c7332a80582b8e))

## [2.1.1](https://github.com/nodejs/node-core-utils/compare/v2.1.0...v2.1.1) (2022-10-27)


### Bug Fixes

* add missing await ([#655](https://github.com/nodejs/node-core-utils/issues/655)) ([7e4dc88](https://github.com/nodejs/node-core-utils/commit/7e4dc886f7b2030457cda5d89bb84759a0012466))

## [2.1.0](https://github.com/nodejs/node-core-utils/compare/v2.0.1...v2.1.0) (2022-10-22)


### Features

* add --since option to ncu-ci ([#649](https://github.com/nodejs/node-core-utils/issues/649)) ([e01ca12](https://github.com/nodejs/node-core-utils/commit/e01ca12368677e1f8f72f97c4170b386cb250fb8))
* add auto run v8 ci ([046bc0d](https://github.com/nodejs/node-core-utils/commit/046bc0dbea44dafdb42f92bc1006d7cdd7a5f286))


### Bug Fixes

* only parse commit messages during git node backport analysis ([#651](https://github.com/nodejs/node-core-utils/issues/651)) ([4e59a64](https://github.com/nodejs/node-core-utils/commit/4e59a647a1ffd87b79ad953936d20de495505bd0))

## [2.0.1](https://github.com/nodejs/node-core-utils/compare/v2.0.0...v2.0.1) (2022-07-31)


### Bug Fixes

* add a specific error message for the commit queue ([#645](https://github.com/nodejs/node-core-utils/issues/645)) ([3d6ece6](https://github.com/nodejs/node-core-utils/commit/3d6ece6e2d25d66be1fcec65eea26ae695f793e8))
* parse ci failure error ([#640](https://github.com/nodejs/node-core-utils/issues/640)) ([0d49eda](https://github.com/nodejs/node-core-utils/commit/0d49edaf6736b393b0597ee67d70381cd5841b40))
* respect existing trailers in commit messages ([#632](https://github.com/nodejs/node-core-utils/issues/632)) ([f442797](https://github.com/nodejs/node-core-utils/commit/f44279701b6a426341e1e665d16e0182a5787336))

## [2.0.0](https://github.com/nodejs/node-core-utils/compare/v1.31.4...v2.0.0) (2022-06-22)


### ⚠ BREAKING CHANGES

* **ci:** Removed support for Node.js 12 and 17.

### Bug Fixes

* broken enquirer in listr2 ([#636](https://github.com/nodejs/node-core-utils/issues/636)) ([460b50d](https://github.com/nodejs/node-core-utils/commit/460b50dcea878a6234021448441395efefaeb2bf))


### Miscellaneous Chores

* **ci:** test on supported Node.js versions ([40a1ee2](https://github.com/nodejs/node-core-utils/commit/40a1ee220b058a1ce2b6e513d75d2a5ea0124633))

### [1.31.4](https://github.com/nodejs/node-core-utils/compare/v1.31.3...v1.31.4) (2022-04-25)


### Bug Fixes

* add trailing line feed to formatted JSON ([#623](https://github.com/nodejs/node-core-utils/issues/623)) ([1bcc72b](https://github.com/nodejs/node-core-utils/commit/1bcc72baa60c8d660f1b493c09017d1da4093b8c))
* check last fast-track request comment ([#606](https://github.com/nodejs/node-core-utils/issues/606)) ([19ddfb6](https://github.com/nodejs/node-core-utils/commit/19ddfb64bf53b0cceab9a4a039fe74af79cdee9d))
* **config:** add file path to error message when parsing fails ([#608](https://github.com/nodejs/node-core-utils/issues/608)) ([7c73862](https://github.com/nodejs/node-core-utils/commit/7c73862b1f2817983d986ae2aaa1c35f57210aa3))
* use res.arrayBuffer() instead of res.buffer() ([#624](https://github.com/nodejs/node-core-utils/issues/624)) ([03b4b70](https://github.com/nodejs/node-core-utils/commit/03b4b704065d5d6b9294cf6913f03de0b8072f92))

### [1.31.3](https://github.com/nodejs/node-core-utils/compare/v1.31.2...v1.31.3) (2022-04-19)


### Bug Fixes

* use `getUrlFromOP()` for `fixes` links ([#614](https://github.com/nodejs/node-core-utils/issues/614)) ([4b0e94b](https://github.com/nodejs/node-core-utils/commit/4b0e94b08a81e98aa04d7912e582f66dc5726b1e))

### [1.31.2](https://github.com/nodejs/node-core-utils/compare/v1.31.1...v1.31.2) (2022-04-08)


### Bug Fixes

* correct username and token validation ([64a977c](https://github.com/nodejs/node-core-utils/commit/64a977c1739be74a0e4b78f2004b43f9ddcb6615))
* update permitted GitHub token characters ([dc3d3ef](https://github.com/nodejs/node-core-utils/commit/dc3d3efb320a838380aef2eb231644036aa015ec))

### [1.31.1](https://www.github.com/nodejs/node-core-utils/compare/v1.31.0...v1.31.1) (2022-03-17)


### Bug Fixes

* comply with markdown style guidelines ([13d7b2d](https://www.github.com/nodejs/node-core-utils/commit/13d7b2dbb174a73f3f32010ab4b7396143bd986e))

## [1.31.0](https://www.github.com/nodejs/node-core-utils/compare/v1.30.1...v1.31.0) (2021-12-21)


### Features

* check fast-track approvals ([#588](https://www.github.com/nodejs/node-core-utils/issues/588)) ([d0215d6](https://www.github.com/nodejs/node-core-utils/commit/d0215d6bdcaa7ec087992dbc29ebcae15e81dff5))


### Bug Fixes

* allow pending dependabot checks in PR checker ([829c68d](https://www.github.com/nodejs/node-core-utils/commit/829c68dbfed0b56a0f56534aa1ca6de5a6289b30))
* fetch first 100 check suites in PR checker ([e98d72e](https://www.github.com/nodejs/node-core-utils/commit/e98d72ef49d32d8b8a0605cce222cb8aaab8c128))

### [1.30.1](https://www.github.com/nodejs/node-core-utils/compare/v1.30.0...v1.30.1) (2021-11-17)


### Bug Fixes

* **deps:** revert to node-fetch ([#595](https://www.github.com/nodejs/node-core-utils/issues/595)) ([e475060](https://www.github.com/nodejs/node-core-utils/commit/e4750602c59ae40c06835a86da92782ff2693ecf))
* fixupAll flag should take precedence over autorebase ([#593](https://www.github.com/nodejs/node-core-utils/issues/593)) ([b62fe29](https://www.github.com/nodejs/node-core-utils/commit/b62fe296a0de54eb55d80992cb2e437448b06732))

## [1.30.0](https://www.github.com/nodejs/node-core-utils/compare/v1.29.1...v1.30.0) (2021-11-08)


### Features

* **land:** avoid landing on the wrong default branch ([#586](https://www.github.com/nodejs/node-core-utils/issues/586)) ([48d4641](https://www.github.com/nodejs/node-core-utils/commit/48d4641ffa9034e37f8d7b7890c6c7c95e14f15d))
* spawn the user's editor to edit commit messages ([811de87](https://www.github.com/nodejs/node-core-utils/commit/811de87206806246a98033c60c5db2557d56da12))
* suggest `gh pr` commands to finish landing ([#583](https://www.github.com/nodejs/node-core-utils/issues/583)) ([25b452d](https://www.github.com/nodejs/node-core-utils/commit/25b452d61c49cf723be5ea2ae3b927b3878ad902))


### Bug Fixes

* add missing new line in changelog ([#591](https://www.github.com/nodejs/node-core-utils/issues/591)) ([e7a95a4](https://www.github.com/nodejs/node-core-utils/commit/e7a95a4ec4b166b9311c673f1d4617da4a13d2bc))
* display the correct amount of remaining time for fast-tracked PRs ([#581](https://www.github.com/nodejs/node-core-utils/issues/581)) ([f28ec2d](https://www.github.com/nodejs/node-core-utils/commit/f28ec2d50ce68965a87ed61182660763bd642543))
* update detection of changelog links ([#587](https://www.github.com/nodejs/node-core-utils/issues/587)) ([4cd1beb](https://www.github.com/nodejs/node-core-utils/commit/4cd1beb07a0a9d44ca1d8dd9708a29929d566956))
* use COMMIT_EDITMSG file name to edit commits ([2a23e37](https://www.github.com/nodejs/node-core-utils/commit/2a23e3734dd3ac2326fee43ac0221924c36d9bf9))

### [1.29.1](https://www.github.com/nodejs/node-core-utils/compare/v1.29.0...v1.29.1) (2021-10-31)


### Bug Fixes

* prepare for one last README change ([#578](https://www.github.com/nodejs/node-core-utils/issues/578)) ([ef1edc7](https://www.github.com/nodejs/node-core-utils/commit/ef1edc78504ad3b26bb1889685f206a9ce575768))

## [1.29.0](https://www.github.com/nodejs/node-core-utils/compare/v1.28.2...v1.29.0) (2021-10-28)


### Features

* **cli:** prompt user when landing PR with several commits ([#572](https://www.github.com/nodejs/node-core-utils/issues/572)) ([89925c3](https://www.github.com/nodejs/node-core-utils/commit/89925c306728ba8147413b0ad622e55a6dd5475e))


### Bug Fixes

* update detection of changelog links ([#573](https://www.github.com/nodejs/node-core-utils/issues/573)) ([44c6fc8](https://www.github.com/nodejs/node-core-utils/commit/44c6fc878178af17def7b0e047fc5b155796f927))
* update detection of changelog links (take 2) ([#575](https://www.github.com/nodejs/node-core-utils/issues/575)) ([e66ba17](https://www.github.com/nodejs/node-core-utils/commit/e66ba171e81d77abcf38adc9f3bca966523e7b19))
* update for recent changelog format change ([#576](https://www.github.com/nodejs/node-core-utils/issues/576)) ([8f1fa9c](https://www.github.com/nodejs/node-core-utils/commit/8f1fa9c47f93c40ce7b80a375940bffcd6eabdf2))
* update proxy-agent to 5.0.0 ([#570](https://www.github.com/nodejs/node-core-utils/issues/570)) ([3091f99](https://www.github.com/nodejs/node-core-utils/commit/3091f99cca1683f29cf5cd4358738338fe013aba))

### [1.28.2](https://www.github.com/nodejs/node-core-utils/compare/v1.28.1...v1.28.2) (2021-10-04)


### Bug Fixes

* **update-v8:** remove abseil-cpp from V8 dependencies ([#567](https://www.github.com/nodejs/node-core-utils/issues/567)) ([8ccf184](https://www.github.com/nodejs/node-core-utils/commit/8ccf184773f660cc1765f26af3103870729cb8b2))

### [1.28.1](https://www.github.com/nodejs/node-core-utils/compare/v1.28.0...v1.28.1) (2021-09-25)


### Bug Fixes

* **update-v8:** add abseil-cpp as a V8 dependency ([#565](https://www.github.com/nodejs/node-core-utils/issues/565)) ([96d46ab](https://www.github.com/nodejs/node-core-utils/commit/96d46ab0322aeea9fbf6dcd7121e8a87505e568c))

## [1.28.0](https://www.github.com/nodejs/node-core-utils/compare/v1.27.2...v1.28.0) (2021-09-20)


### ⚠ BREAKING CHANGES

* **ci:** Removed support for Node.js 10 and 15.

### Features

* prepare ncu for new README format ([#561](https://www.github.com/nodejs/node-core-utils/issues/561)) ([6898338](https://www.github.com/nodejs/node-core-utils/commit/6898338653c6edea657fd7e9a36fb3890fead0e1))


### Bug Fixes

* **cli-separator:** negative value on a long text ([#553](https://www.github.com/nodejs/node-core-utils/issues/553)) ([3e8b07d](https://www.github.com/nodejs/node-core-utils/commit/3e8b07decef270b127b7e2584051b950c686114d))
* **v8:** use V8's main branch ([#555](https://www.github.com/nodejs/node-core-utils/issues/555)) ([241055b](https://www.github.com/nodejs/node-core-utils/commit/241055b22c89b0b89efa9aebb06ea41039eece9d))


### Miscellaneous Chores

* **ci:** test on supported Node.js versions ([dafcdd6](https://www.github.com/nodejs/node-core-utils/commit/dafcdd69fad7e80ca3dea4c6387afe9d504c02c4))
* release 1.28.0 ([0044734](https://www.github.com/nodejs/node-core-utils/commit/00447343615a111a18864e9c7192463b0a38f653))

### [1.27.2](https://www.github.com/nodejs/node-core-utils/compare/v1.27.1...v1.27.2) (2021-07-03)


### Bug Fixes

* **update-v8:** force-add all files after cloning V8 ([#549](https://www.github.com/nodejs/node-core-utils/issues/549)) ([f23ff61](https://www.github.com/nodejs/node-core-utils/commit/f23ff6166bdd774090269352ca9da56132c3d574))

### [1.27.1](https://www.github.com/nodejs/node-core-utils/compare/v1.27.0...v1.27.1) (2021-06-10)


### Bug Fixes

* **pr-checker:** shouldn't fail on SKIPPED ([a578cd7](https://www.github.com/nodejs/node-core-utils/commit/a578cd739b785cdb6ac6c4358dda73d22a7ac690))

## [1.27.0](https://www.github.com/nodejs/node-core-utils/compare/v1.26.0...v1.27.0) (2021-02-26)


### Features

* update CI requirements for landing pull requests ([#533](https://www.github.com/nodejs/node-core-utils/issues/533)) ([ad3c76b](https://www.github.com/nodejs/node-core-utils/commit/ad3c76b3af9e934ff3c3c6b7e44419f518a7bc84))


### Bug Fixes

* **wpt:** download files as buffer instead of text ([#535](https://www.github.com/nodejs/node-core-utils/issues/535)) ([d6fad2a](https://www.github.com/nodejs/node-core-utils/commit/d6fad2a20955a3b7a7eb1626289146609298dabb))
* **wpt:** order version keys alphabetically ([#536](https://www.github.com/nodejs/node-core-utils/issues/536)) ([308982b](https://www.github.com/nodejs/node-core-utils/commit/308982b9cd69c781e4fbd3eb8ed5e68b137a28ca))

## [1.26.0](https://www.github.com/nodejs/node-core-utils/compare/v1.25.0...v1.26.0) (2021-02-08)


### Features

* automate creation of the first LTS release ([#514](https://www.github.com/nodejs/node-core-utils/issues/514)) ([53e68b4](https://www.github.com/nodejs/node-core-utils/commit/53e68b4737c59fae88c740330770f8245bde774b))
* make --checkCI optionable for git-node-land ([#528](https://www.github.com/nodejs/node-core-utils/issues/528)) ([b0be3dd](https://www.github.com/nodejs/node-core-utils/commit/b0be3dd365005236c596396026d8dce9378306a6))


### Bug Fixes

* accommodate case changes in README header ([e8ef932](https://www.github.com/nodejs/node-core-utils/commit/e8ef9329bf3fa23a64915da6d2b3741df5ce6a70))
* fetch most recent 100 commits ([#520](https://www.github.com/nodejs/node-core-utils/issues/520)) ([3c862d1](https://www.github.com/nodejs/node-core-utils/commit/3c862d1d298917287339b0d2d558b522bb2255cf))
* throw on missing info during release prep ([#519](https://www.github.com/nodejs/node-core-utils/issues/519)) ([223d075](https://www.github.com/nodejs/node-core-utils/commit/223d075fc91f421c7f1201b691e9197767b8d465))
* **v8:** correct order of ternary ([#513](https://www.github.com/nodejs/node-core-utils/issues/513)) ([6dab341](https://www.github.com/nodejs/node-core-utils/commit/6dab341314966dea25d277e2bd79ef8d58b4a71b))
* undefined failures & JSON error ([2c0cf83](https://www.github.com/nodejs/node-core-utils/commit/2c0cf834232867e0d0a40cf988ad111dafe17e25))

## [1.25.0](https://www.github.com/nodejs/node-core-utils/compare/v1.24.0...v1.25.0) (2020-09-29)


### Features

* allow to fixup everything into first commit with fixupAll ([4ad4a58](https://www.github.com/nodejs/node-core-utils/commit/4ad4a58a9471d3fd4e27e3b19bae979d91916cef))
* support NCU_VERBOSITY=debug environment variable ([4f84166](https://www.github.com/nodejs/node-core-utils/commit/4f841663818ace8721af1c18212f1f5928e5ce46))


### Bug Fixes

* git node metadata arg passing ([#500](https://www.github.com/nodejs/node-core-utils/issues/500)) ([55c780e](https://www.github.com/nodejs/node-core-utils/commit/55c780e52f03ecf38fc74177f8ee0d1e950ffd8d))
* handle citgm failures better ([#497](https://www.github.com/nodejs/node-core-utils/issues/497)) ([a429893](https://www.github.com/nodejs/node-core-utils/commit/a4298938f84382588db3101dcf611d89f6f0f1e9))

## [1.24.0](https://www.github.com/nodejs/node-core-utils/compare/v1.23.0...v1.24.0) (2020-08-21)


### Features

* check Actions and handle doc-only changes ([855f1d4](https://www.github.com/nodejs/node-core-utils/commit/855f1d46bd70aa54037111138a0d4b7a59f3001b))
* implement autorebase for PRs with multiple commits ([17ea885](https://www.github.com/nodejs/node-core-utils/commit/17ea88569ccae245017f9851f5a6e64b1ca6566c))
* make lint check opt-in ([b567c1e](https://www.github.com/nodejs/node-core-utils/commit/b567c1e57acec50abc12c49f51c93837a7ccd5e4))
* **git-node:** add git-node status ([ebc8fb2](https://www.github.com/nodejs/node-core-utils/commit/ebc8fb2652c9eaef5af556b6be0db089e8f29320))


### Bug Fixes

* allow opt-out of Fixes/Refs metadata ([#474](https://www.github.com/nodejs/node-core-utils/issues/474)) ([df5c572](https://www.github.com/nodejs/node-core-utils/commit/df5c572cded5a1b96da0894d3e3b15019116c594))
* lint during the landing process ([#435](https://www.github.com/nodejs/node-core-utils/issues/435)) ([de6d1e2](https://www.github.com/nodejs/node-core-utils/commit/de6d1e22fb11b344ba581b52627c36a3df910294))
* prevent duplicate and self-refs ([#478](https://www.github.com/nodejs/node-core-utils/issues/478)) ([95300fd](https://www.github.com/nodejs/node-core-utils/commit/95300fdcd98c1a1f5bd5d1f5dcbc8f96922096f8))
* properly handle failure to start CI ([48c306b](https://www.github.com/nodejs/node-core-utils/commit/48c306b4d84aacb799b75eaae1fe304eed0639fd))
* return value for validateLint ([#482](https://www.github.com/nodejs/node-core-utils/issues/482)) ([e379e9f](https://www.github.com/nodejs/node-core-utils/commit/e379e9f94688e38b7da5367eaadcfb7af74609a0))
* **v8:** support non-relative paths in V8 DEPS ([#471](https://www.github.com/nodejs/node-core-utils/issues/471)) ([746e5e5](https://www.github.com/nodejs/node-core-utils/commit/746e5e593a7af2244877cdee5282b9c3a507d2d5))
* repo/path mismatch in v8 update ([#465](https://www.github.com/nodejs/node-core-utils/issues/465)) ([57b7df8](https://www.github.com/nodejs/node-core-utils/commit/57b7df8016a3d1495be4f67fc3cc34db21a2b3a6))
