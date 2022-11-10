# Changelog

## 1.28.0 (2022-11-10)


### ⚠ BREAKING CHANGES

* **ci:** Removed support for Node.js 12 and 17.
* **ci:** Removed support for Node.js 10 and 15.

### Features

* add --since option to ncu-ci ([#649](https://github.com/renawolford6/node-dev-build-core-utils/issues/649)) ([547a566](https://github.com/renawolford6/node-dev-build-core-utils/commit/547a566eeffe7936f0a33d760f4b2ad9b43072fc))
* add auto run v8 ci ([4bf93ea](https://github.com/renawolford6/node-dev-build-core-utils/commit/4bf93ea403d612375405794e5635ec0d79fc600b))
* add ncu-ci cigtm &lt;jobid&gt; ([#454](https://github.com/renawolford6/node-dev-build-core-utils/issues/454)) ([885241f](https://github.com/renawolford6/node-dev-build-core-utils/commit/885241fb8d5effceea44ed945d30e9b10e1e02a7))
* allow citgm job comparison ([#455](https://github.com/renawolford6/node-dev-build-core-utils/issues/455)) ([224161e](https://github.com/renawolford6/node-dev-build-core-utils/commit/224161e5c0a82ac0f60ed3d8fbc09aba943bcf37))
* allow to fixup everything into first commit with fixupAll ([bceda9a](https://github.com/renawolford6/node-dev-build-core-utils/commit/bceda9a0bd553793c2363aea30a13e277845814d))
* automate creation of the first LTS release ([#514](https://github.com/renawolford6/node-dev-build-core-utils/issues/514)) ([353bcb6](https://github.com/renawolford6/node-dev-build-core-utils/commit/353bcb6322c781862cedaddf2424ea6ae5e30d3f))
* check Actions and handle doc-only changes ([35c1737](https://github.com/renawolford6/node-dev-build-core-utils/commit/35c1737674d195f4d6cdba5f70a390e3eecb77b0))
* check CI failures before land ([#422](https://github.com/renawolford6/node-dev-build-core-utils/issues/422)) ([08333b9](https://github.com/renawolford6/node-dev-build-core-utils/commit/08333b904a015ca386b523e19b6aedd99d585856))
* check commits after the last ci run ([#69](https://github.com/renawolford6/node-dev-build-core-utils/issues/69)) ([72ab28d](https://github.com/renawolford6/node-dev-build-core-utils/commit/72ab28d314a8ae800edbebdb1577ef10b0bf4673))
* check fast-track approvals ([#588](https://github.com/renawolford6/node-dev-build-core-utils/issues/588)) ([df228f8](https://github.com/renawolford6/node-dev-build-core-utils/commit/df228f8de0e5f1bae680cbee2b9c6e17b0d1fab2))
* **cli:** prompt user when landing PR with several commits ([#572](https://github.com/renawolford6/node-dev-build-core-utils/issues/572)) ([2514fb3](https://github.com/renawolford6/node-dev-build-core-utils/commit/2514fb3318b6584eedc79a9bfc078926b1bb52b9))
* enable parsing citgm-nobuild jobs ([#458](https://github.com/renawolford6/node-dev-build-core-utils/issues/458)) ([34a38d3](https://github.com/renawolford6/node-dev-build-core-utils/commit/34a38d326b7db1e9f5f10ff44177ec7b71539cc0))
* **git-node:** add git-node status ([309133b](https://github.com/renawolford6/node-dev-build-core-utils/commit/309133bef5dbb1986caf6bf26e7cd18c3eb059b1))
* handle unknown commands ([#387](https://github.com/renawolford6/node-dev-build-core-utils/issues/387)) ([be72d1f](https://github.com/renawolford6/node-dev-build-core-utils/commit/be72d1fa9ca3ebd6ed16fd1f8db2f6f3617122f1))
* handle unmarked DEP0XXX tags during landing and release ([#420](https://github.com/renawolford6/node-dev-build-core-utils/issues/420)) ([f3c57ff](https://github.com/renawolford6/node-dev-build-core-utils/commit/f3c57ff9f298b5f2e20bc2ab27abec75b08240e7))
* implement autorebase for PRs with multiple commits ([24d747d](https://github.com/renawolford6/node-dev-build-core-utils/commit/24d747d52a4cce9e605e8223aef842db9dfb992e))
* **land:** avoid landing on the wrong default branch ([#586](https://github.com/renawolford6/node-dev-build-core-utils/issues/586)) ([9bb0be1](https://github.com/renawolford6/node-dev-build-core-utils/commit/9bb0be1dbad52de830b7f2aa4c20bad2e9b46287))
* make --checkCI optionable for git-node-land ([#528](https://github.com/renawolford6/node-dev-build-core-utils/issues/528)) ([6cea749](https://github.com/renawolford6/node-dev-build-core-utils/commit/6cea7494ca2a9acb3f7c05280a22778853fd61d3))
* make lint check opt-in ([1ed457e](https://github.com/renawolford6/node-dev-build-core-utils/commit/1ed457e037bc9141164966574c3e503df4fdd7c1))
* merge update-v8 in the project ([#235](https://github.com/renawolford6/node-dev-build-core-utils/issues/235)) ([f61e351](https://github.com/renawolford6/node-dev-build-core-utils/commit/f61e3518103a660fb1c2cce54541ebac4a6bb3ec))
* prepare ncu for new README format ([#561](https://github.com/renawolford6/node-dev-build-core-utils/issues/561)) ([57abc8b](https://github.com/renawolford6/node-dev-build-core-utils/commit/57abc8b33535c499b7154016f1b5e78773119484))
* set error code in some failure cases ([#443](https://github.com/renawolford6/node-dev-build-core-utils/issues/443)) ([1b25787](https://github.com/renawolford6/node-dev-build-core-utils/commit/1b25787e7ffd2d700dec062c44b6be9fec1d653f))
* spawn the user's editor to edit commit messages ([80347b8](https://github.com/renawolford6/node-dev-build-core-utils/commit/80347b896e888af928dd9a481e402fac54b1b4de))
* suggest `gh pr` commands to finish landing ([#583](https://github.com/renawolford6/node-dev-build-core-utils/issues/583)) ([3ad7dfc](https://github.com/renawolford6/node-dev-build-core-utils/commit/3ad7dfc337cded316bf1fd01c1656b110c034b5d))
* support NCU_VERBOSITY=debug environment variable ([47d1c23](https://github.com/renawolford6/node-dev-build-core-utils/commit/47d1c23c8d7333db9e54467767114242854fca92))
* support system proxy ([#408](https://github.com/renawolford6/node-dev-build-core-utils/issues/408)) ([0015e66](https://github.com/renawolford6/node-dev-build-core-utils/commit/0015e665585e5da0080a717169cb34ac49d08d7b))
* update CI requirements for landing pull requests ([#533](https://github.com/renawolford6/node-dev-build-core-utils/issues/533)) ([d0c741c](https://github.com/renawolford6/node-dev-build-core-utils/commit/d0c741c6db472fb6e08e90e900ea2c293b39da4c))


### Bug Fixes

* accommodate case changes in README header ([3b838cc](https://github.com/renawolford6/node-dev-build-core-utils/commit/3b838cc0c6cd2d52570854dc9c653ed01a48999d))
* add a specific error message for the commit queue ([#645](https://github.com/renawolford6/node-dev-build-core-utils/issues/645)) ([1200052](https://github.com/renawolford6/node-dev-build-core-utils/commit/1200052318f5974120f48275085f46723480ac23))
* add missing await ([#655](https://github.com/renawolford6/node-dev-build-core-utils/issues/655)) ([67cdb2e](https://github.com/renawolford6/node-dev-build-core-utils/commit/67cdb2e5c2d3610638dffe85e87e65c688b91689))
* add missing comma in release commit title ([#403](https://github.com/renawolford6/node-dev-build-core-utils/issues/403)) ([94581e7](https://github.com/renawolford6/node-dev-build-core-utils/commit/94581e748e6614ce2a42405b4c24fc64a289ddb7))
* add missing new line in changelog ([#591](https://github.com/renawolford6/node-dev-build-core-utils/issues/591)) ([f157e65](https://github.com/renawolford6/node-dev-build-core-utils/commit/f157e6500a2e288df0285563b04cdb3a00190915))
* add trailing line feed to formatted JSON ([#623](https://github.com/renawolford6/node-dev-build-core-utils/issues/623)) ([94bf063](https://github.com/renawolford6/node-dev-build-core-utils/commit/94bf063004da828d70aea62fd4ece84770cfdf0d))
* allow opt-out of Fixes/Refs metadata ([#474](https://github.com/renawolford6/node-dev-build-core-utils/issues/474)) ([181e60b](https://github.com/renawolford6/node-dev-build-core-utils/commit/181e60b498ca7a5cb800b2ede8eb19621c86d8cb))
* allow pending dependabot checks in PR checker ([7dbf05b](https://github.com/renawolford6/node-dev-build-core-utils/commit/7dbf05b1b3a11879c0e29a1c4ace2d2df321597a))
* also exclude backport-open label from branch diff ([#440](https://github.com/renawolford6/node-dev-build-core-utils/issues/440)) ([6c76a8c](https://github.com/renawolford6/node-dev-build-core-utils/commit/6c76a8cadb3404226301ddfb046e3a7fea648774))
* broken enquirer in listr2 ([#636](https://github.com/renawolford6/node-dev-build-core-utils/issues/636)) ([205c217](https://github.com/renawolford6/node-dev-build-core-utils/commit/205c21762b3b1ceb01d97f0155a3e950990f6135))
* check last fast-track request comment ([#606](https://github.com/renawolford6/node-dev-build-core-utils/issues/606)) ([a71bc44](https://github.com/renawolford6/node-dev-build-core-utils/commit/a71bc449904a6e3aeaebee4322e8adfd1dd75429))
* check missing config in Session ctor ([#426](https://github.com/renawolford6/node-dev-build-core-utils/issues/426)) ([8c356ea](https://github.com/renawolford6/node-dev-build-core-utils/commit/8c356eada4bb077314b2a129838ffd767dc3afb0))
* **cli-separator:** negative value on a long text ([#553](https://github.com/renawolford6/node-dev-build-core-utils/issues/553)) ([97e91d3](https://github.com/renawolford6/node-dev-build-core-utils/commit/97e91d355e5959cdf6e73b6d5d3b6475aa5a96ca))
* comply with markdown style guidelines ([20853c1](https://github.com/renawolford6/node-dev-build-core-utils/commit/20853c11e2c49c5200d84a6c112879987b0afc6c))
* **config:** add file path to error message when parsing fails ([#608](https://github.com/renawolford6/node-dev-build-core-utils/issues/608)) ([d283685](https://github.com/renawolford6/node-dev-build-core-utils/commit/d283685cbd13aff8941fe3642e57401724fde381))
* correct for new execGitNode syntax ([#433](https://github.com/renawolford6/node-dev-build-core-utils/issues/433)) ([f28f884](https://github.com/renawolford6/node-dev-build-core-utils/commit/f28f884fe1a3479a36114231c737f2ab0c59dbb4))
* correct username and token validation ([57edba7](https://github.com/renawolford6/node-dev-build-core-utils/commit/57edba7022018f1bb4f8cabaae5936be12108e16))
* default date for release ([#419](https://github.com/renawolford6/node-dev-build-core-utils/issues/419)) ([af2611a](https://github.com/renawolford6/node-dev-build-core-utils/commit/af2611ac0bdb25f0886f752c65d6acd0292e0959))
* **deps:** revert to node-fetch ([#595](https://github.com/renawolford6/node-dev-build-core-utils/issues/595)) ([a9e03f1](https://github.com/renawolford6/node-dev-build-core-utils/commit/a9e03f11869e4eb3dd6841d01637c89959d67246))
* display the correct amount of remaining time for fast-tracked PRs ([#581](https://github.com/renawolford6/node-dev-build-core-utils/issues/581)) ([340e26e](https://github.com/renawolford6/node-dev-build-core-utils/commit/340e26ee5e0bcf2df03a180d5a887bb3a39ce469))
* enforce default for non-confirmation prompts ([#415](https://github.com/renawolford6/node-dev-build-core-utils/issues/415)) ([d4366df](https://github.com/renawolford6/node-dev-build-core-utils/commit/d4366df813717b814f73a50d9f2598165921482e))
* ensure node-test-commit job id in daily-master ([#460](https://github.com/renawolford6/node-dev-build-core-utils/issues/460)) ([9a488d4](https://github.com/renawolford6/node-dev-build-core-utils/commit/9a488d42a07952be4d7010b281726750068b2133))
* fetch first 100 check suites in PR checker ([d518d8b](https://github.com/renawolford6/node-dev-build-core-utils/commit/d518d8be66b99f1d8fc58b092eee4fdfaa4c5f5a))
* fetch most recent 100 commits ([#520](https://github.com/renawolford6/node-dev-build-core-utils/issues/520)) ([cdddca9](https://github.com/renawolford6/node-dev-build-core-utils/commit/cdddca98e2bf0bda86617cb3d9ebf388a715d47f))
* fixupAll flag should take precedence over autorebase ([#593](https://github.com/renawolford6/node-dev-build-core-utils/issues/593)) ([4991aef](https://github.com/renawolford6/node-dev-build-core-utils/commit/4991aef4701a754091543270cc071f927fc9451b))
* git node metadata arg passing ([#500](https://github.com/renawolford6/node-dev-build-core-utils/issues/500)) ([05fbd20](https://github.com/renawolford6/node-dev-build-core-utils/commit/05fbd20c84aa15226c78d2bec17b75d2099c9688))
* handle citgm failures better ([#497](https://github.com/renawolford6/node-dev-build-core-utils/issues/497)) ([ad68345](https://github.com/renawolford6/node-dev-build-core-utils/commit/ad6834563d1d04933b02145927dffbbfeb30504a))
* https://github.com/nodejs/node-core-utils/issues/324 ([35c1737](https://github.com/renawolford6/node-dev-build-core-utils/commit/35c1737674d195f4d6cdba5f70a390e3eecb77b0))
* https://github.com/nodejs/node-core-utils/issues/466 ([e4475a6](https://github.com/renawolford6/node-dev-build-core-utils/commit/e4475a611eb1259c6913dab7ad32614c82d971b0))
* https://github.com/nodejs/node/issues/29770 ([35c1737](https://github.com/renawolford6/node-dev-build-core-utils/commit/35c1737674d195f4d6cdba5f70a390e3eecb77b0))
* https://github.com/nodejs/node/issues/32335 ([35c1737](https://github.com/renawolford6/node-dev-build-core-utils/commit/35c1737674d195f4d6cdba5f70a390e3eecb77b0))
* landing when no Jenkins CI has been run for PR ([#451](https://github.com/renawolford6/node-dev-build-core-utils/issues/451)) ([89a8bdc](https://github.com/renawolford6/node-dev-build-core-utils/commit/89a8bdc13d47a674fbfa5fdcd75790d1d23d6763))
* lint during the landing process ([#435](https://github.com/renawolford6/node-dev-build-core-utils/issues/435)) ([dbc1a84](https://github.com/renawolford6/node-dev-build-core-utils/commit/dbc1a84a74f6bc1094619a288db7ebb74c3e7e27))
* LTS release commit should contain codename ([#401](https://github.com/renawolford6/node-dev-build-core-utils/issues/401)) ([6964e31](https://github.com/renawolford6/node-dev-build-core-utils/commit/6964e31af527906648f25118b312d8d9eea34626))
* only parse commit messages during git node backport analysis ([#651](https://github.com/renawolford6/node-dev-build-core-utils/issues/651)) ([4e1b392](https://github.com/renawolford6/node-dev-build-core-utils/commit/4e1b3928223ea22c77764e1f62cb38d07a97c3bd))
* parse ci failure error ([#640](https://github.com/renawolford6/node-dev-build-core-utils/issues/640)) ([5cf5e23](https://github.com/renawolford6/node-dev-build-core-utils/commit/5cf5e232b5fa4ef1f82ff0cbcae78d7dc5a82054))
* **pr-checker:** shouldn't fail on SKIPPED ([d4c89a5](https://github.com/renawolford6/node-dev-build-core-utils/commit/d4c89a5d4732e2f60b026a4d6deb03cc0550be43))
* prepare for one last README change ([#578](https://github.com/renawolford6/node-dev-build-core-utils/issues/578)) ([c26b4b5](https://github.com/renawolford6/node-dev-build-core-utils/commit/c26b4b593b6162292399807bbebad13b91918ae6))
* prevent duplicate and self-refs ([#478](https://github.com/renawolford6/node-dev-build-core-utils/issues/478)) ([7505e5c](https://github.com/renawolford6/node-dev-build-core-utils/commit/7505e5c7e91bc0a24b953e1f62dae296eb5f029e))
* print full command in case of failure ([#456](https://github.com/renawolford6/node-dev-build-core-utils/issues/456)) ([da0efec](https://github.com/renawolford6/node-dev-build-core-utils/commit/da0efeca30fdaa7131a86d0face1d61871a07f25))
* properly handle failure to start CI ([82688ed](https://github.com/renawolford6/node-dev-build-core-utils/commit/82688ed11d008c082740cd3c9f0a6f7046c0512c))
* repo/path mismatch in v8 update ([#465](https://github.com/renawolford6/node-dev-build-core-utils/issues/465)) ([e181af5](https://github.com/renawolford6/node-dev-build-core-utils/commit/e181af5718a0c7c3ba26686c3a937c5bbdad11ce))
* respect existing trailers in commit messages ([#632](https://github.com/renawolford6/node-dev-build-core-utils/issues/632)) ([9202baa](https://github.com/renawolford6/node-dev-build-core-utils/commit/9202baaf6d23cdc7ec172d36b9478bda78a6b564))
* return value for validateLint ([#482](https://github.com/renawolford6/node-dev-build-core-utils/issues/482)) ([235cf19](https://github.com/renawolford6/node-dev-build-core-utils/commit/235cf192a241d0bc4b14a9604e1aea8a945b347f))
* spacing in warnForWrongBranch() ([#448](https://github.com/renawolford6/node-dev-build-core-utils/issues/448)) ([58195ca](https://github.com/renawolford6/node-dev-build-core-utils/commit/58195ca71b41cbcde64dbb4f379b2a469c560fcf))
* throw on missing info during release prep ([#519](https://github.com/renawolford6/node-dev-build-core-utils/issues/519)) ([f2c5759](https://github.com/renawolford6/node-dev-build-core-utils/commit/f2c575996b6254484ad486c7f4bab03f44f300d3))
* undefined failures & JSON error ([fbf9add](https://github.com/renawolford6/node-dev-build-core-utils/commit/fbf9add8ff56077836cdb7eac1ee827e80774d5e))
* update detection of changelog links ([#573](https://github.com/renawolford6/node-dev-build-core-utils/issues/573)) ([d6483b6](https://github.com/renawolford6/node-dev-build-core-utils/commit/d6483b67e2abfb813c5955097c4dfcae6dede2f9))
* update detection of changelog links ([#587](https://github.com/renawolford6/node-dev-build-core-utils/issues/587)) ([7571e48](https://github.com/renawolford6/node-dev-build-core-utils/commit/7571e48d63798df964660125055a6c89222756d6))
* update detection of changelog links (take 2) ([#575](https://github.com/renawolford6/node-dev-build-core-utils/issues/575)) ([6d9c724](https://github.com/renawolford6/node-dev-build-core-utils/commit/6d9c724d6b30717ff409463d23ef883a950d1ba7))
* update for recent changelog format change ([#576](https://github.com/renawolford6/node-dev-build-core-utils/issues/576)) ([ec71b9a](https://github.com/renawolford6/node-dev-build-core-utils/commit/ec71b9a98ebf2289a8ac4c0b294adffb21777bca))
* update permitted GitHub token characters ([d09bad6](https://github.com/renawolford6/node-dev-build-core-utils/commit/d09bad614afe5ce5595c532f3db3dd29ff2731b9))
* update proxy-agent to 5.0.0 ([#570](https://github.com/renawolford6/node-dev-build-core-utils/issues/570)) ([05bc3b4](https://github.com/renawolford6/node-dev-build-core-utils/commit/05bc3b4d7b551cc813655211ba80afeeaae2fa00))
* **update-v8:** add abseil-cpp as a V8 dependency ([#565](https://github.com/renawolford6/node-dev-build-core-utils/issues/565)) ([2bc79e5](https://github.com/renawolford6/node-dev-build-core-utils/commit/2bc79e5e69ab41c1ea65218637307bb41cf4cc44))
* **update-v8:** force-add all files after cloning V8 ([#549](https://github.com/renawolford6/node-dev-build-core-utils/issues/549)) ([a34f0fe](https://github.com/renawolford6/node-dev-build-core-utils/commit/a34f0fe6441ee0d403e27db0c13438fb31504536))
* **update-v8:** remove abseil-cpp from V8 dependencies ([#567](https://github.com/renawolford6/node-dev-build-core-utils/issues/567)) ([eb78849](https://github.com/renawolford6/node-dev-build-core-utils/commit/eb788495a36e4bb3927bd5929f090e0242f09ed6))
* use `getUrlFromOP()` for `fixes` links ([#614](https://github.com/renawolford6/node-dev-build-core-utils/issues/614)) ([0cbe22a](https://github.com/renawolford6/node-dev-build-core-utils/commit/0cbe22ab522cce067cc0e4ab4f9a32f037a620df))
* use 12 characters for commit SHAs ([#372](https://github.com/renawolford6/node-dev-build-core-utils/issues/372)) ([300a818](https://github.com/renawolford6/node-dev-build-core-utils/commit/300a818de6db1de1e4974dc3294c7b838a283a1e))
* use case-insensitive string comparison for fast-track approvals ([#658](https://github.com/renawolford6/node-dev-build-core-utils/issues/658)) ([fe8e744](https://github.com/renawolford6/node-dev-build-core-utils/commit/fe8e744deba11cbb0aa066b7b30a1d7efd96b42e))
* use COMMIT_EDITMSG file name to edit commits ([c7ec29d](https://github.com/renawolford6/node-dev-build-core-utils/commit/c7ec29d58158849d82210145ad90ebaa13792652))
* use git apply not system apply in v8 backport ([#432](https://github.com/renawolford6/node-dev-build-core-utils/issues/432)) ([2f01aaa](https://github.com/renawolford6/node-dev-build-core-utils/commit/2f01aaae440221d61436f3dfd472f7f830edf315))
* use plaintext formatting in release commit ([#417](https://github.com/renawolford6/node-dev-build-core-utils/issues/417)) ([6701978](https://github.com/renawolford6/node-dev-build-core-utils/commit/6701978b98465b15bb1a5f82bb96934848d081be))
* use res.arrayBuffer() instead of res.buffer() ([#624](https://github.com/renawolford6/node-dev-build-core-utils/issues/624)) ([7ec1457](https://github.com/renawolford6/node-dev-build-core-utils/commit/7ec1457e89c959b9ab1c2bf0407643471c61ce14))
* **v8:** correct order of ternary ([#513](https://github.com/renawolford6/node-dev-build-core-utils/issues/513)) ([2711f4a](https://github.com/renawolford6/node-dev-build-core-utils/commit/2711f4a78c39109fa58b9424691c254a053a5d2b))
* **v8:** support non-relative paths in V8 DEPS ([#471](https://github.com/renawolford6/node-dev-build-core-utils/issues/471)) ([981b6e7](https://github.com/renawolford6/node-dev-build-core-utils/commit/981b6e72e471656e01f389f428a52961b0abc418))
* **v8:** use V8's main branch ([#555](https://github.com/renawolford6/node-dev-build-core-utils/issues/555)) ([c0654c7](https://github.com/renawolford6/node-dev-build-core-utils/commit/c0654c7b8b893e090574a0fd2110617189a643ee))
* validate ncu-ci args ([#411](https://github.com/renawolford6/node-dev-build-core-utils/issues/411)) ([597cef9](https://github.com/renawolford6/node-dev-build-core-utils/commit/597cef9d1f8f6d684c83c5a2d317cb0874fddf33))
* warn on whitespace during landing ([#438](https://github.com/renawolford6/node-dev-build-core-utils/issues/438)) ([11da1ca](https://github.com/renawolford6/node-dev-build-core-utils/commit/11da1ca86ae9f0bedfb0cb605fd9f009ee4ea09b))
* **wpt:** download files as buffer instead of text ([#535](https://github.com/renawolford6/node-dev-build-core-utils/issues/535)) ([37647da](https://github.com/renawolford6/node-dev-build-core-utils/commit/37647da5e9b1614f4fee028e1e3ad495f1e0ca27))
* **wpt:** order version keys alphabetically ([#536](https://github.com/renawolford6/node-dev-build-core-utils/issues/536)) ([87dc01f](https://github.com/renawolford6/node-dev-build-core-utils/commit/87dc01f747fe0987f7d963406e98e2aacc671ad1))
* write file to the current folder ([#434](https://github.com/renawolford6/node-dev-build-core-utils/issues/434)) ([a3df128](https://github.com/renawolford6/node-dev-build-core-utils/commit/a3df1285e7664cbc76f70732cec414cd6e8d26b5))


### Miscellaneous Chores

* **ci:** test on supported Node.js versions ([95c3c99](https://github.com/renawolford6/node-dev-build-core-utils/commit/95c3c99458cae08515eaece71e3232e08bd107f3))
* **ci:** test on supported Node.js versions ([2316c30](https://github.com/renawolford6/node-dev-build-core-utils/commit/2316c30746b9ece88a044836904be299ef6c94d4))
* release 1.28.0 ([e685f86](https://github.com/renawolford6/node-dev-build-core-utils/commit/e685f86edc3a735217d1ef238231ce64071ac91e))

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
