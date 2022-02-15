## [3.6.9](https://git.arcticleaf.io/modules/StencilCLI/compare/v3.6.8...v3.6.9) (2022-02-15)


### Bug Fixes

* bump version ([3e82ac7](https://git.arcticleaf.io/modules/StencilCLI/commit/3e82ac77131b686e26492993d2fac0a405b75a24))

# [1.16.0](https://git.arcticleaf.io/modules/StencilCLI/compare/v1.15.7...v1.16.0) (2022-02-15)


### Bug Fixes

* (strf-5280) Multiple themes - Changes to config.json not reflected ([0b28309](https://git.arcticleaf.io/modules/StencilCLI/commit/0b28309f1c51984a5220339f8be41cdf157112b2))
* (strf-8705) fix broken headers and cookies in local server ([1dc8afd](https://git.arcticleaf.io/modules/StencilCLI/commit/1dc8afd6c9e854650bee2dcf393d948aa5064de5))
* (strf-8734) fix a typo in renderer.module -> getTemplatePath() ([de5a91b](https://git.arcticleaf.io/modules/StencilCLI/commit/de5a91bb5f0a549548e3069bb9eb740221e3f391))
* (strf-8740) fix a typo in StencilStart.assembleTemplates() ([7f58d48](https://git.arcticleaf.io/modules/StencilCLI/commit/7f58d4847d374bad0617825f0646c82c7f12af86))
* (strf-8745) move common headers inside sendApiRequest and refactor NetworkUtils ([21a3522](https://git.arcticleaf.io/modules/StencilCLI/commit/21a352286881651d115667ed39bc5138b1728cf3))
* (strf-8746) make local server parse binary data responses right ([39dacd8](https://git.arcticleaf.io/modules/StencilCLI/commit/39dacd8f89ee3d43951d1c832b9cf917a3037931))
* (strf-8840) add missing rejectUnauthorized parameter to the API requests ([5ee6138](https://git.arcticleaf.io/modules/StencilCLI/commit/5ee6138a36c88bbffbf61004a3b8845db7099116))
* (STRF-9019) wrong reading from stream breaks stencil-download command ([eb9b082](https://git.arcticleaf.io/modules/StencilCLI/commit/eb9b082dcd89f489dbc864b32763a51a2467e5b4))
* (STRF-9087) set upstream=storefront to support multiple channels in start command ([3f6b8ed](https://git.arcticleaf.io/modules/StencilCLI/commit/3f6b8edf50d4fba361b6fb3b07e26424942a82a1))
* (STRF-9294) Added check to ensure we are not looping over undefined object ([bcd2401](https://git.arcticleaf.io/modules/StencilCLI/commit/bcd24010288e49d518a147cbd9021a580c5a71a1))
* add account_payment_methods_v2 to theme config schema ([373a485](https://git.arcticleaf.io/modules/StencilCLI/commit/373a485d0b96b4efc048c4e5baaf8ffabd65fe35))
* add file list to package file to ignore tests and cli release code ([de4468f](https://git.arcticleaf.io/modules/StencilCLI/commit/de4468f86dfda2189ecae4f59a255b4917fdf603))
* add handling cases when redirect link is already stripped in normalizeRedirectUrl ([88fee5d](https://git.arcticleaf.io/modules/StencilCLI/commit/88fee5d62b9992cd190221819a487222af87732d))
* add hapi as a direct dependency to lock down hapi version ([3b9a258](https://git.arcticleaf.io/modules/StencilCLI/commit/3b9a2587dbc33e52306f8fbba3257b33ef2c455b))
* add missed linting step to github actions ([19b4012](https://git.arcticleaf.io/modules/StencilCLI/commit/19b4012910f7d47624ca7f62bcadafad59a81a42))
* add missed test coverage check to github actions ([39d137d](https://git.arcticleaf.io/modules/StencilCLI/commit/39d137dbc03f379cc9da485b0df805ed91d3a8b2))
* added browser-sync to package-lock ([#454](https://git.arcticleaf.io/modules/StencilCLI/issues/454)) ([dcc4795](https://git.arcticleaf.io/modules/StencilCLI/commit/dcc4795d7b96c3224e3bd1f537f9719a682c73a8))
* added bump of package-lock.json to gulp release task ([#448](https://git.arcticleaf.io/modules/StencilCLI/issues/448)) ([f2c423b](https://git.arcticleaf.io/modules/StencilCLI/commit/f2c423b37e9618c02dd77ede9d784bf642c43cfe))
* added fix for scss compilation issue ([e6a20a2](https://git.arcticleaf.io/modules/StencilCLI/commit/e6a20a207ac458a28a96cb8f04c401baab435ebf))
* address chrome cookie SameSite issue ([5938ce1](https://git.arcticleaf.io/modules/StencilCLI/commit/5938ce11f1d11f8be26acec4c63fb6a678aaac2f))
* apply various PR fixes ([c5d964b](https://git.arcticleaf.io/modules/StencilCLI/commit/c5d964b4bd1891331646d9e3bd4d9ad1b0ab165f))
* avoid caching of storefront api responses ([9974a07](https://git.arcticleaf.io/modules/StencilCLI/commit/9974a070bb700112361d5b7d4f5c92795b1faf64))
* broken changelog.md after stencil release command ([ec4a72a](https://git.arcticleaf.io/modules/StencilCLI/commit/ec4a72a72ea016b325b561b21bdb9261237ad4d2))
* bump paper to 2.0.19 ([670a7ad](https://git.arcticleaf.io/modules/StencilCLI/commit/670a7ad6e7557181d6c9e51b4e4e4109ad90ec79))
* bump paper to 3.0.0-rc20 ([e9c7691](https://git.arcticleaf.io/modules/StencilCLI/commit/e9c7691d104f249c3d6c47257da589f23e8bba39))
* bump stencil-styles to 1.2.0 ([97389b9](https://git.arcticleaf.io/modules/StencilCLI/commit/97389b9acaaf5ff71914c593dffcba1eb7fd75d5))
* correcting url for deploy issues docs ([44ef5e9](https://git.arcticleaf.io/modules/StencilCLI/commit/44ef5e966a77373e85ff56b935c85da0a48db616))
* **cp:** STRF-5614 Add enhanced_ecommerce to theme config schema. ([58c6fb9](https://git.arcticleaf.io/modules/StencilCLI/commit/58c6fb9e2ce5fef55068a9dd41b8e5206f51a8c2))
* disable stencil version check ([f386557](https://git.arcticleaf.io/modules/StencilCLI/commit/f386557ebb7c2d9f576b9bfd1f245716d989ab62))
* disable webpack when running in shippy ([537dfe3](https://git.arcticleaf.io/modules/StencilCLI/commit/537dfe3650125d4ab2f12beb380577184d4765bc))
* fix lint errors in lib/stencil-init.js ([a2e7383](https://git.arcticleaf.io/modules/StencilCLI/commit/a2e73831cb47dcef4afac0c56dec465f102fe562))
* fix lint errors in lib/stencil-init.spec.js ([0b2b328](https://git.arcticleaf.io/modules/StencilCLI/commit/0b2b32816b2f122475f8bcce7a98e1e3092538b0))
* fix linting problems on Windows ([bcdfaa4](https://git.arcticleaf.io/modules/StencilCLI/commit/bcdfaa4420a00d59b17b757f878d7aa59d9129bb))
* fix origin sent with graphql requests ([#541](https://git.arcticleaf.io/modules/StencilCLI/issues/541)) ([8f3f02c](https://git.arcticleaf.io/modules/StencilCLI/commit/8f3f02ced8e34b3e5840c0f56f1305ab0fb3ca56))
* fixes merge conflicts ([8a56259](https://git.arcticleaf.io/modules/StencilCLI/commit/8a56259c4726056bd82404656c6d61d9a22f6789))
* inquirer.prompt is not called when not necessary ([beeca29](https://git.arcticleaf.io/modules/StencilCLI/commit/beeca29c8e25927498b38fcc68a9562627491ef9))
* make running tests in verbose mode ([8bdd3d4](https://git.arcticleaf.io/modules/StencilCLI/commit/8bdd3d40f62ef9991b0efc1e57fff4dd6625af4f))
* merc--7873 Support 5 character language code for schema translations ([b1d291a](https://git.arcticleaf.io/modules/StencilCLI/commit/b1d291a37a66305771481503a89c93948ce53785))
* more detailed theme variation error ([96e3a30](https://git.arcticleaf.io/modules/StencilCLI/commit/96e3a30bd52544032bb8f0ee78870c84611c1bec))
* move code to dev dependency ([f1fd570](https://git.arcticleaf.io/modules/StencilCLI/commit/f1fd570190cc9c7594e54b96d804feedde2590c3))
* package name change, semantic release ([13d5a35](https://git.arcticleaf.io/modules/StencilCLI/commit/13d5a355f15baa90f4ddb0e3e55102416d9ec65c))
* remove less dependency and ref since it is not supported or used ([c586dd8](https://git.arcticleaf.io/modules/StencilCLI/commit/c586dd8450780b9ed82018d3cd36f8fb941a7dd7))
* revert paper_2.0.11 pr ([#445](https://git.arcticleaf.io/modules/StencilCLI/issues/445)) ([adf424f](https://git.arcticleaf.io/modules/StencilCLI/commit/adf424fe289f1ceb014bb0ef94b72395a61e7944))
* reverts change to mock test answers ([ea9c76e](https://git.arcticleaf.io/modules/StencilCLI/commit/ea9c76e9b7d02123609524ccb5ac6b16000dd205))
* schema.json formatting ([73c8a26](https://git.arcticleaf.io/modules/StencilCLI/commit/73c8a2699f0e55528cb85e12162c97cc3927c1fc))
* **stencil-init.spec.js:** fixed a broken test ([66ab50d](https://git.arcticleaf.io/modules/StencilCLI/commit/66ab50d489faa47719f952d61071ee78978093b6))
* **stencil-push:** (STRF-8913) increase maxBodyLength in NetworkUtils.sendApiRequest ([f2e3918](https://git.arcticleaf.io/modules/StencilCLI/commit/f2e39181e5c790eb25e444c5aea9ce3c9e8f6062))
* **stencil-release:** (STRF-6905) add updating version in package-lock.json ([8f9ff79](https://git.arcticleaf.io/modules/StencilCLI/commit/8f9ff794f255094e0f9f433b680cdd829fa6b209))
* **stencil-release:** fix typo in the code ([e6dfbc3](https://git.arcticleaf.io/modules/StencilCLI/commit/e6dfbc351bbb06a92bde4f3334b4fd1c10c26be7))
* **stencil-release:** fix uploading broken bundle archive to github ([0271ed4](https://git.arcticleaf.io/modules/StencilCLI/commit/0271ed4200958a0875fa24381efa689bfd7c52e5))
* strf-6383 add check for template size for stencil bundling ([f674c05](https://git.arcticleaf.io/modules/StencilCLI/commit/f674c056066251acdc097b43d0aa910cab4beace))
* strf-7023 move browser-sync back to master ([c3db4db](https://git.arcticleaf.io/modules/StencilCLI/commit/c3db4db61d4e2707b2a69749a9a1a82a9d694b21))
* strf-8574 Bump version of "archiver" to fix security issues ([42f4528](https://git.arcticleaf.io/modules/StencilCLI/commit/42f45287184be385ad20e7823c290352d745f4b0))
* strf-8574 Bump versions of npm modules to fix security issues ([2587d0a](https://git.arcticleaf.io/modules/StencilCLI/commit/2587d0a4705c289b5e881bfa377854b9ba44b5c7))
* strf-8574, bump "hapi" and its modules to fix security issues ([b520daa](https://git.arcticleaf.io/modules/StencilCLI/commit/b520daa6f30703139a87b339e3c97a33202ba564))
* strf-8574, bump version of "@hapi/lab" to fix security issues ([44872f2](https://git.arcticleaf.io/modules/StencilCLI/commit/44872f2a9c50ecd96b65e1035633066d76705b03))
* strf-8574, bump version of "github" package to fix security issues ([1013e3a](https://git.arcticleaf.io/modules/StencilCLI/commit/1013e3a8357fded819ff9764fdb95423e66351f6))
* strf-8574, bump version of "inquirer" to fix security issues ([474c9af](https://git.arcticleaf.io/modules/StencilCLI/commit/474c9afb2896c92234dcb5f7b5154f56b1e957e7))
* strf-8574, remove redundant dependency "hoek" ([9aeb3c1](https://git.arcticleaf.io/modules/StencilCLI/commit/9aeb3c1955db9d943551baa21bea13e5fbcfe48b))
* strf-8846 Send stencil-cli header to storefront api ([#789](https://git.arcticleaf.io/modules/StencilCLI/issues/789)) ([aefa595](https://git.arcticleaf.io/modules/StencilCLI/commit/aefa59527a9dfdbbcb8fc218eb82a5b7c19b5ffb))
* strf-9257 Added check if theme version exists ([#745](https://git.arcticleaf.io/modules/StencilCLI/issues/745)) ([a520a55](https://git.arcticleaf.io/modules/StencilCLI/commit/a520a551f93765f16e46414557d0a15fb88c9dd4))
* strf-9312 Rename github workflow on relaese action ([#763](https://git.arcticleaf.io/modules/StencilCLI/issues/763)) ([c2671de](https://git.arcticleaf.io/modules/StencilCLI/commit/c2671deeb8659bba6d7ee7ce5db5e81e646afc7b))
* strf-9356 Replace ssh to https on node-sass dep ([#775](https://git.arcticleaf.io/modules/StencilCLI/issues/775)) ([8801911](https://git.arcticleaf.io/modules/StencilCLI/commit/8801911f977d2910fdc894b55236cbf74f866707))
* strf-9356 Support npm 7 for stencil cli ([#769](https://git.arcticleaf.io/modules/StencilCLI/issues/769)) ([6131b55](https://git.arcticleaf.io/modules/StencilCLI/commit/6131b55f3becd12696ed84428d62d62e38f7c215))
* strf-9375 Fix custom release tag selection ([#783](https://git.arcticleaf.io/modules/StencilCLI/issues/783)) ([666fb59](https://git.arcticleaf.io/modules/StencilCLI/commit/666fb59f8491b49b6fc4a2ecac1b2c533fd8d9ba))
* tunnel issues and add support for tunnel names ([820fa4d](https://git.arcticleaf.io/modules/StencilCLI/commit/820fa4df8f63a22a4fb765b7f3ea9ad841f657f6))
* typo fix ([5593b32](https://git.arcticleaf.io/modules/StencilCLI/commit/5593b327614066bbbbfe74b974dfc3a314922525))
* unmerged typo fix ([e53ce5a](https://git.arcticleaf.io/modules/StencilCLI/commit/e53ce5a480bb0648f1d3599ca26aede8dc9fcc45))
* update engines for node in package.json ([70ae9a3](https://git.arcticleaf.io/modules/StencilCLI/commit/70ae9a321a232b99e04e515b3f9078a9f4d23b6f))
* update paper to 3.0.0-rc.26 ([32ef114](https://git.arcticleaf.io/modules/StencilCLI/commit/32ef114d8833b55ead0dbb81d5f360a556440ff7))
* update readme to reflect node 8 is no longer supported ([6e793a9](https://git.arcticleaf.io/modules/StencilCLI/commit/6e793a962ce644171cd2b24846a5410ba24e18db))
* workaround for potential BC bug ([b0162cb](https://git.arcticleaf.io/modules/StencilCLI/commit/b0162cbca8ddbba9be24d1e35ff0a8ac21c1cefe))


### Features

* (strf-8608) bump recent updates in npm packages ([e50e231](https://git.arcticleaf.io/modules/StencilCLI/commit/e50e23186c4e08853be48985585252d298d50d16))
* (strf-8608) deleted unused npm dependencies ([1f64ad9](https://git.arcticleaf.io/modules/StencilCLI/commit/1f64ad94dc536626f236293385d50fc5071669da))
* (strf-8608) replace "request" with "node-fetch" ([e758b01](https://git.arcticleaf.io/modules/StencilCLI/commit/e758b01cf923a280ac0c3bedb64d980183c24fc5))
* (strf-8608) replaced lab+code+sinon with jest ([71e952f](https://git.arcticleaf.io/modules/StencilCLI/commit/71e952fb6e21825a082ee2aa25cb3db00e98a222))
* (strf-8608) update "front-matter" ([a0aa6fd](https://git.arcticleaf.io/modules/StencilCLI/commit/a0aa6fd34d1e320d39fe36de8403339ed900b346))
* (strf-8608) update "simple-git" ([7153455](https://git.arcticleaf.io/modules/StencilCLI/commit/7153455ade76a7254a41e4e88929cc57824e5c30))
* (strf-8608) update "tarjan-graph" ([4a27ee6](https://git.arcticleaf.io/modules/StencilCLI/commit/4a27ee6823563cfccb4f377d5db84647605e85c9))
* (strf-8608) updated some npm dependencies ([9059210](https://git.arcticleaf.io/modules/StencilCLI/commit/9059210c113c22cd5d54412c4dfa351f72a1ff69))
* (strf-8625) support Node 12.x ([1449751](https://git.arcticleaf.io/modules/StencilCLI/commit/1449751916e1e90793ba7150c418c26a3046f58c))
* (strf-8630) fix template engine values ([0af2cb5](https://git.arcticleaf.io/modules/StencilCLI/commit/0af2cb589ca0dff294a8ccac85f3d68ceda630b9))
* (strf-8671) replace "wreck" with "node-fetch" ([6dcdd9b](https://git.arcticleaf.io/modules/StencilCLI/commit/6dcdd9bb0e261ea0531051ca76ccf12128e1980e))
* (strf-8672) improve ESLint config and add prettier ([a8b78c8](https://git.arcticleaf.io/modules/StencilCLI/commit/a8b78c8817e00922e12d5278f79f3963f7e6cbf4))
* (strf-8673) update "commander" ([dc3bf29](https://git.arcticleaf.io/modules/StencilCLI/commit/dc3bf296e5f8d4bc852859934428b6d16cfecff9))
* (strf-8674) update "async" npm package ([9f64096](https://git.arcticleaf.io/modules/StencilCLI/commit/9f6409622cb02ec03f523e360d7d66bb3fbf8a30))
* (strf-8684) update 'tmp' package ([b1e932c](https://git.arcticleaf.io/modules/StencilCLI/commit/b1e932cd53e2161e6482148e5c9e950cef774614))
* (strf-8740) cover StencilStart.assembleTemplates() with tests ([0adf1f8](https://git.arcticleaf.io/modules/StencilCLI/commit/0adf1f860ef752fd49fad918d67929081741a327))
* (strf-8747) split .stencil file into 2 configs ([6f3d2dc](https://git.arcticleaf.io/modules/StencilCLI/commit/6f3d2dcaa7205b7c8c54da729c936c649d109e38))
* accept url and token as arguments on stencil init ([b69a9fe](https://git.arcticleaf.io/modules/StencilCLI/commit/b69a9fe65949233139efcb7898de35455fa9aebd))
* add flag to auto-delete oldest theme during push ([ea93793](https://git.arcticleaf.io/modules/StencilCLI/commit/ea93793324589452222bf022b494568f2f6f7ae9))
* Add overwrite option to download command ([#785](https://git.arcticleaf.io/modules/StencilCLI/issues/785)) ([eb78444](https://git.arcticleaf.io/modules/StencilCLI/commit/eb78444a9dd3ac8a80a9b5321852ee5af58b3e01))
* add schema validation to bundle process ([b86d440](https://git.arcticleaf.io/modules/StencilCLI/commit/b86d4400a68bb7680618aef3ae072033ba047613))
* Add support for base_url and secure_base_url ([cc3ca08](https://git.arcticleaf.io/modules/StencilCLI/commit/cc3ca084081a1e5d83ce5e3111232757a0e5a991))
* added re-integration script with new command download ([dc6df02](https://git.arcticleaf.io/modules/StencilCLI/commit/dc6df02839c584f2829ecf8f1334862d7b526a74))
* bump paper ([91acd1c](https://git.arcticleaf.io/modules/StencilCLI/commit/91acd1c64df0617f2a60654e7918ec5a327db072))
* bump paper ([f1d2b5a](https://git.arcticleaf.io/modules/StencilCLI/commit/f1d2b5ac066897c7e22702c1f015799b329a4837))
* bump paper to 2.0.18 ([fa71b05](https://git.arcticleaf.io/modules/StencilCLI/commit/fa71b05cc02a23c65871338edc27c49f973ff707))
* bump paper to 3.0.0-rc.27 ([86e4f74](https://git.arcticleaf.io/modules/StencilCLI/commit/86e4f74c27a56d4617ddb0aa78675f6d0c3074f4))
* bump paper to rc30, release 2.2.0 ([6945a3c](https://git.arcticleaf.io/modules/StencilCLI/commit/6945a3cbd0676b5b0282d82c91ae70b2eb9e3274))
* bump paper to rc31 ([b958744](https://git.arcticleaf.io/modules/StencilCLI/commit/b958744effafdf3351b9af600a41e4ce8e5c6919))
* changelog generator ([#431](https://git.arcticleaf.io/modules/StencilCLI/issues/431)) ([9e6e225](https://git.arcticleaf.io/modules/StencilCLI/commit/9e6e225712d88d31f1e89850e8bd71e64390d976))
* **dependencies:** remove compression as a dependency ([2c02e9e](https://git.arcticleaf.io/modules/StencilCLI/commit/2c02e9e1a9f66c1025ba64e6b263db780c25e5bb))
* **dependencies:** remove dateformat as a direct dependecy ([6044e91](https://git.arcticleaf.io/modules/StencilCLI/commit/6044e91aff6ce38042b015b669a5f0af0a261ccd))
* **dependencies:** remove decompress-zip as a dependency ([34c7fde](https://git.arcticleaf.io/modules/StencilCLI/commit/34c7fde7f19d50ea4e3a741e51ffe8c494468960))
* **dependencies:** remove express as a dependecy since it is not used ([ba1c2c5](https://git.arcticleaf.io/modules/StencilCLI/commit/ba1c2c5234ce5368a8f82aa1851c1eea5f8ab047))
* **dependencies:** remove gulp git, sass, sass-lint dependency ([14dceeb](https://git.arcticleaf.io/modules/StencilCLI/commit/14dceeb7318b69a6530c5477d4d17d52ab003565))
* **dependencies:** remove install as a dependency since it is not used ([1c2549c](https://git.arcticleaf.io/modules/StencilCLI/commit/1c2549cda7674b0da79781c616a97722ef0fad52))
* **dependencies:** remove npm as a dependency ([4733649](https://git.arcticleaf.io/modules/StencilCLI/commit/473364926d3b278328c39f339bf2679a5af378ef))
* **dependencies:** remove script-loader as a direct dependecy ([9a2b817](https://git.arcticleaf.io/modules/StencilCLI/commit/9a2b817a601c9036635f254694660b5dbe8729f6))
* **dependencies:** update dev dependency ([d5bdfe3](https://git.arcticleaf.io/modules/StencilCLI/commit/d5bdfe3e22f56f24a158dc3c94316ebd0ab57297))
* **dependencies:** update eslint to the latest and fix lint errors ([5a2fd85](https://git.arcticleaf.io/modules/StencilCLI/commit/5a2fd8557fc73651bdcc39f4c48ea59dad5859ca))
* deprecate theme editor ([c0466dc](https://git.arcticleaf.io/modules/StencilCLI/commit/c0466dcb36264f41e91f91bfa650416b826c2282))
* **docs:** add project structure and best practices ([251c1ff](https://git.arcticleaf.io/modules/StencilCLI/commit/251c1fff4a1a1809d434b76e213654759fa71440))
* drop node 8 support ([5aa1624](https://git.arcticleaf.io/modules/StencilCLI/commit/5aa162451a818a0cc5a419b0547949cc670db064))
* increase coverage threshold ([9dfa78c](https://git.arcticleaf.io/modules/StencilCLI/commit/9dfa78c050bda5d0d922e85eeeb257b73916d80e))
* init no longer prompts when cli option is present ([a9fee29](https://git.arcticleaf.io/modules/StencilCLI/commit/a9fee29848877fc054d62a379d7d69fccdd949c9))
* **localization:** merc-7830 support for region translations ([9e66d6b](https://git.arcticleaf.io/modules/StencilCLI/commit/9e66d6be6c81adc15651537e1b34d48e4ac4432a))
* make init command more suitable for automation  ([ab9b919](https://git.arcticleaf.io/modules/StencilCLI/commit/ab9b9190bb2cf8c9c225c98a55079fcaf7b202b9))
* move lab to dev deps and update it to 14.3.3 ([0f57631](https://git.arcticleaf.io/modules/StencilCLI/commit/0f576315c2ff4263fd9c667e0cfa40a437fc90eb))
* **other:** merc-7797 added feature to render widgets ([40c410b](https://git.arcticleaf.io/modules/StencilCLI/commit/40c410bcbb46dbcb44968fb4d4a60c849d88fe08))
* **other:** merc-7834 validate theme variation translations ([219dc60](https://git.arcticleaf.io/modules/StencilCLI/commit/219dc600ff90ef376afcb764d3d3ea2a9d0c8582))
* remove client id from required fields ([0cbc093](https://git.arcticleaf.io/modules/StencilCLI/commit/0cbc093eed6766ef5eb6e1a5f524badfdf73d9c5))
* remove hapi as a direct dependecy ([3164fbc](https://git.arcticleaf.io/modules/StencilCLI/commit/3164fbcf65283697ac315da714e691478828316f))
* remove old unused field staplerUrl from local server ([a3ec69f](https://git.arcticleaf.io/modules/StencilCLI/commit/a3ec69f04a4d6fe67f8bcca12eba12afb2c8d796))
* strf-6687 update stencil-paper to add font-display support ([3af5562](https://git.arcticleaf.io/modules/StencilCLI/commit/3af55620d92ee50ee91af8e329349bf6528e6456))
* strf-7175 bump paper to 3.0.0-rc.19 ([eb5ef78](https://git.arcticleaf.io/modules/StencilCLI/commit/eb5ef785684f27d60eb8c79952fbacc911c8d426))
* strf-7393 make cli work with paper 3.x branch ([7ba9688](https://git.arcticleaf.io/modules/StencilCLI/commit/7ba968818f86cdbab28ebf710ce0ab9d4b581f36))
* strf-7651 - update push command to take into account multiple channels ([7582e7c](https://git.arcticleaf.io/modules/StencilCLI/commit/7582e7c85b4b6c858a25670a13e7981611e2ca03))
* strf-8282 - update pull command to take into account multiple channels ([00b4571](https://git.arcticleaf.io/modules/StencilCLI/commit/00b4571e6fe7ecf16ffb47c3cfc01ae734e528a9))
* strf-8282 - use sites instead of channels API ([bf16215](https://git.arcticleaf.io/modules/StencilCLI/commit/bf162151d773fffec289b9a1162ca7b74c507c1e))
* strf-8589, drop JSPM support ([c39c67b](https://git.arcticleaf.io/modules/StencilCLI/commit/c39c67b483fd01caaa79973c239d9a49b1d53de8))
* strf-9040 Support dart-sass as primary engine for css rendering ([#779](https://git.arcticleaf.io/modules/StencilCLI/issues/779)) ([39abce5](https://git.arcticleaf.io/modules/StencilCLI/commit/39abce5a9b83caa55b200e4480af662933b9df21))
* strf-9071 - update download command to support multiple channels ([d6a9f94](https://git.arcticleaf.io/modules/StencilCLI/commit/d6a9f949207cfa15909ce72c17deffec726fe1bd))
* strf-9087 stencil localhost only shows default storefront data ([#720](https://git.arcticleaf.io/modules/StencilCLI/issues/720)) ([85d7733](https://git.arcticleaf.io/modules/StencilCLI/commit/85d77339c7beee1346ce33ad2b4d6dc4881bff04))
* strf-9303 Replaced jsonlint with parse-json ([#758](https://git.arcticleaf.io/modules/StencilCLI/issues/758)) ([48b46cf](https://git.arcticleaf.io/modules/StencilCLI/commit/48b46cf7f052b0acc2ddc4911c561271b89d68c6))
* strf-9319 Github Release for stencil-cli ([#751](https://git.arcticleaf.io/modules/StencilCLI/issues/751)) ([7283549](https://git.arcticleaf.io/modules/StencilCLI/commit/728354906f8bcfbd9d7f4c9a47f44211ca5d2266))
* strf-9332 added timeout parameter for stencil bundle command ([#767](https://git.arcticleaf.io/modules/StencilCLI/issues/767)) ([a4a268c](https://git.arcticleaf.io/modules/StencilCLI/commit/a4a268c4ccd9148489b76b9dd26f8a64efa89ce2))
* strf-9345 Infer apiHost from storeUrl ([5b132e9](https://git.arcticleaf.io/modules/StencilCLI/commit/5b132e90b62ab5583e43fe600431ff4787903f2c))
* strf-9345: Fallback to API_HOST constant in the absense of a provided one ([d138536](https://git.arcticleaf.io/modules/StencilCLI/commit/d138536c82d784b158ed743996311053af121a54))
* strf-9345: Log api host ([51b08a9](https://git.arcticleaf.io/modules/StencilCLI/commit/51b08a9b233c32662c1571d427021664f805192e))
* **theme:** add csrf protection to the list of valid features ([fe4b795](https://git.arcticleaf.io/modules/StencilCLI/commit/fe4b795581b0190c7c88809978c3b156df77c619))
* **translate:** added the translationsSchema.json file into a bundle ([ba04cd6](https://git.arcticleaf.io/modules/StencilCLI/commit/ba04cd6e13b1cf8e906627e61fcef55f654fd0b8))
* **translate:** added validation for schemaTranslations.json ([fccafe2](https://git.arcticleaf.io/modules/StencilCLI/commit/fccafe2dd8aafe031e69dc6670117691278e0b73))
* **translate:** fixed regarding reviewers notes ([0a1f43d](https://git.arcticleaf.io/modules/StencilCLI/commit/0a1f43df3795b04dcad6f1efe0e5d9a52b3606c1))
* update "stencil pull" to use configurations API, improving performance ([2b142fc](https://git.arcticleaf.io/modules/StencilCLI/commit/2b142fc0d911ce7ec62375517740fac1795708d6))
* update browser sync to use latest master ([0916991](https://git.arcticleaf.io/modules/StencilCLI/commit/0916991702f50785902a75592aa338758e7f84b0))
* update cli to use template engine based on the value stored in ([f9ea0a9](https://git.arcticleaf.io/modules/StencilCLI/commit/f9ea0a924dc9701b5b5302a0650a846f96812f0c))
* update colors dependency ([b488557](https://git.arcticleaf.io/modules/StencilCLI/commit/b488557ee6476660d8a8fc51cc99bd8afc1cb415))
* update stencil-paper to add getImageSrcset helper ([892fbfd](https://git.arcticleaf.io/modules/StencilCLI/commit/892fbfd99e4036020f0bb265bd32852008764878))
* upgrade lodash dependency ([640c61d](https://git.arcticleaf.io/modules/StencilCLI/commit/640c61dff545c115b7dbce998403d84f718305d8))
* watch storefront config file ([e7b43d9](https://git.arcticleaf.io/modules/StencilCLI/commit/e7b43d9089f5bb7d9914d09f07a883c7a8e34064))


### Reverts

* Revert "feat: Add support for base_url and secure_base_url" (#453) ([74d1122](https://git.arcticleaf.io/modules/StencilCLI/commit/74d112206f11dbb3325f52f9cfbf2a7602175f3f)), closes [#453](https://git.arcticleaf.io/modules/StencilCLI/issues/453)

### 3.6.2 (2021-10-06)

-   feat: Add overwrite option to download command ([785](https://github.com/bigcommerce/stencil-cli/pull/785))

### 3.6.1 (2021-10-04)

-   fix: strf-9375 Fix custom release tag selection ([f41d6dd44fb](https://github.com/bigcommerce/stencil-cli/commit/f41d6dd44fb))

### 3.6.0 (2021-09-28)

-   feat: strf-9332 added timeout parameter for stencil bundle command ([9c762fa0aa1](https://github.com/bigcommerce/stencil-cli/commit/9c762fa0aa1))
-   feat: strf-9040 Support dart-sass as primary engine for css rendering ([514ea778eda](https://github.com/bigcommerce/stencil-cli/commit/514ea778eda))

### 3.5.2 (2021-09-17)

-   fix: strf-9356 Support npm 7 for stencil cli ([d67747d5384](https://github.com/bigcommerce/stencil-cli/commit/d67747d5384))

### 3.5.1 (2021-09-15)

-   fix: strf-9345: Fallback to API_HOST constant in the absense of a provided one ([d138536c8](https://github.com/bigcommerce/stencil-cli/commit/d138536c8))

### 3.5.0 (2021-09-15)

-   fix: STRF-9351 Stop sending "X-Forwarded-..." headers as it causes remote store to redirect ([36f5663da](https://github.com/bigcommerce/stencil-cli/commit/36f5663da))
-   feat: strf-9303 Replaced jsonlint with parse-json ([b5f16db85](https://github.com/bigcommerce/stencil-cli/commit/b5f16db85))
-   feat: strf-9345: Log api host ([51b08a9b2](https://github.com/bigcommerce/stencil-cli/commit/51b08a9b2))
-   feat: strf-9345 Infer apiHost from storeUrl ([5b132e90b6](https://github.com/bigcommerce/stencil-cli/commit/5b132e90b6))
-   feat: strf-9319 Github Release for stencil-cli ([22949011](https://github.com/bigcommerce/stencil-cli/commit/22949011))

### 3.4.2 (2021-08-17)

-   fix: strf-9257 Added check if theme version exists and release method refactoring ([a520a55](https://github.com/bigcommerce/stencil-cli/commit/a520a55))

### 3.4.1 (2021-08-09)

-   fix: merc-8038 Added check to ensure we are not looping over undefined object ([bcd2401](https://github.com/bigcommerce/stencil-cli/commit/bcd2401))

## 3.4.0 (2021-07-27)

-   feat: merc-7830 support for region translations ([a6bc312](https://github.com/bigcommerce/stencil-cli/commit/a6bc312))
-   feat: merc-7797 added feature to render widgets ([40c410b](https://github.com/bigcommerce/stencil-cli/commit/40c410b))
-   feat: merc-7834 validate theme variation translations ([219dc60](https://github.com/bigcommerce/stencil-cli/commit/219dc60))

## 3.3.0 (2021-06-14)

-   feat: strf-9087 Prompt user to select channel id if multiple storefronts are enabled ([85d773](https://github.com/bigcommerce/stencil-cli/commit/85d773))

## <small>3.2.1 (2021-05-24)</small>

-   refactor: move API requests from commands to themeApiClient ([06f8d61](https://github.com/bigcommerce/stencil-cli/commit/06f8d61))
-   feat: remove old unused field staplerUrl from local server ([a3ec69f](https://github.com/bigcommerce/stencil-cli/commit/a3ec69f))
-   fix: (STRF-9087) set upstream=storefront to support multiple channels in start command ([3f6b8ed](https://github.com/bigcommerce/stencil-cli/commit/3f6b8ed))
-   fix: Typo fix at StencilConfigManager.js([4c2a04d](https://github.com/bigcommerce/stencil-cli/commit/4c2a04d))

## 3.2.0 (2021-03-22)

-   feat: strf-7651 - update push command to take into account multiple channels ([7582e7c](https://github.com/bigcommerce/stencil-cli/commit/7582e7c))
-   feat: strf-8282 - update pull command to take into account multiple channels ([00b4571](https://github.com/bigcommerce/stencil-cli/commit/00b4571))
-   feat: strf-8282 - use sites instead of channels API ([bf16215](https://github.com/bigcommerce/stencil-cli/commit/bf16215))
-   feat: strf-9071 - update download command to support multiple channels ([d6a9f94](https://github.com/bigcommerce/stencil-cli/commit/d6a9f94))

## <small>3.1.1 (2021-03-10)</small>

-   fix: (STRF-9019) wrong reading from stream breaks stencil-download command ([eb9b082](https://github.com/bigcommerce/stencil-cli/commit/eb9b082))
-   fix: broken changelog.md after stencil release command ([ec4a72a](https://github.com/bigcommerce/stencil-cli/commit/ec4a72a))

## 3.1.0 (2021-01-15)

-   fix:(STRF-8909) theme variation not applied with activate flag (#679) ([6830f15](https://github.com/bigcommerce/stencil-cli/commit/6830f15))
-   fix: (strf-8745) move common headers inside sendApiRequest and refactor NetworkUtils ([21a3522](https://github.com/bigcommerce/stencil-cli/commit/21a3522))
-   fix: (strf-8840) add missing rejectUnauthorized parameter to the API requests ([5ee6138](https://github.com/bigcommerce/stencil-cli/commit/5ee6138))
-   fix: add handling cases when redirect link is already stripped in normalizeRedirectUrl ([88fee5d](https://github.com/bigcommerce/stencil-cli/commit/88fee5d))
-   fix(stencil-push): (STRF-8913) increase maxBodyLength in NetworkUtils.sendApiRequest ([f2e3918](https://github.com/bigcommerce/stencil-cli/commit/f2e3918))
-   fix(stencil-release): (STRF-6905) add updating version in package-lock.json ([8f9ff79](https://github.com/bigcommerce/stencil-cli/commit/8f9ff79))
-   fix(stencil-release): fix typo in the code ([e6dfbc3](https://github.com/bigcommerce/stencil-cli/commit/e6dfbc3))
-   fix(stencil-release): fix uploading broken bundle archive to github ([0271ed4](https://github.com/bigcommerce/stencil-cli/commit/0271ed4))
-   refactor: (strf-8745) replace fetch with axios ([946a012](https://github.com/bigcommerce/stencil-cli/commit/946a012))
-   refactor: (strf-8747) move code dealing with .stencil file into a separate class ([7b371e8](https://github.com/bigcommerce/stencil-cli/commit/7b371e8))
-   feat: (strf-8747) split .stencil file into 2 configs ([6f3d2dc](https://github.com/bigcommerce/stencil-cli/commit/6f3d2dc))
-   feat: increase coverage threshold ([9dfa78c](https://github.com/bigcommerce/stencil-cli/commit/9dfa78c))

## <small>3.0.3 (2020-10-19)</small>

-   fix: (strf-8746) make local server parse binary data responses right ([39dacd8](https://github.com/bigcommerce/stencil-cli/commit/39dacd8))

## <small>3.0.2 (2020-10-13)</small>

-   fix: (strf-8740) fix a typo in StencilStart.assembleTemplates() ([7f58d48](https://github.com/bigcommerce/stencil-cli/commit/7f58d48))
-   fix: add missed linting step to github actions ([19b4012](https://github.com/bigcommerce/stencil-cli/commit/19b4012))
-   fix: add missed test coverage check to github actions ([39d137d](https://github.com/bigcommerce/stencil-cli/commit/39d137d))
-   fix: fix linting problems on Windows ([bcdfaa4](https://github.com/bigcommerce/stencil-cli/commit/bcdfaa4))
-   feat: (strf-8740) cover StencilStart.assembleTemplates() with tests ([0adf1f8](https://github.com/bigcommerce/stencil-cli/commit/0adf1f8))
-   refactor: (strf-8740) move recursiveReadDir to fsUtils ([f2e2724](https://github.com/bigcommerce/stencil-cli/commit/f2e2724))

## <small>3.0.1 (2020-10-08)</small>

-   fix: (strf-8734) fix a typo in renderer.module -> getTemplatePath() ([de5a91b](https://github.com/bigcommerce/stencil-cli/commit/de5a91b))
-   fix: add file list to package file to ignore tests and cli release code ([de4468f](https://github.com/bigcommerce/stencil-cli/commit/de4468f))

## 3.0.0 (2020-10-06)

-   fix: (strf-5280) Multiple themes - Changes to config.json not reflected ([0b28309](https://github.com/bigcommerce/stencil-cli/commit/0b28309))
-   fix: (strf-8705) fix broken headers and cookies in local server ([1dc8afd](https://github.com/bigcommerce/stencil-cli/commit/1dc8afd))
-   fix: apply various PR fixes ([c5d964b](https://github.com/bigcommerce/stencil-cli/commit/c5d964b))
-   fix: fix lint errors in lib/stencil-init.js ([a2e7383](https://github.com/bigcommerce/stencil-cli/commit/a2e7383))
-   fix: fix lint errors in lib/stencil-init.spec.js ([0b2b328](https://github.com/bigcommerce/stencil-cli/commit/0b2b328))
-   fix: inquirer.prompt is not called when not necessary ([beeca29](https://github.com/bigcommerce/stencil-cli/commit/beeca29))
-   fix: make running tests in verbose mode ([8bdd3d4](https://github.com/bigcommerce/stencil-cli/commit/8bdd3d4))
-   fix: reverts change to mock test answers ([ea9c76e](https://github.com/bigcommerce/stencil-cli/commit/ea9c76e))
-   fix: strf-8574 Bump version of "archiver" to fix security issues ([42f4528](https://github.com/bigcommerce/stencil-cli/commit/42f4528))
-   fix: strf-8574 Bump versions of npm modules to fix security issues ([2587d0a](https://github.com/bigcommerce/stencil-cli/commit/2587d0a))
-   fix: strf-8574, bump "hapi" and its modules to fix security issues ([b520daa](https://github.com/bigcommerce/stencil-cli/commit/b520daa))
-   fix: strf-8574, bump version of "@hapi/lab" to fix security issues ([44872f2](https://github.com/bigcommerce/stencil-cli/commit/44872f2))
-   fix: strf-8574, bump version of "github" package to fix security issues ([1013e3a](https://github.com/bigcommerce/stencil-cli/commit/1013e3a))
-   fix: strf-8574, bump version of "inquirer" to fix security issues ([474c9af](https://github.com/bigcommerce/stencil-cli/commit/474c9af))
-   fix: strf-8574, remove redundant dependency "hoek" ([9aeb3c1](https://github.com/bigcommerce/stencil-cli/commit/9aeb3c1))
-   fix(stencil-init.spec.js): fixed a broken test ([66ab50d](https://github.com/bigcommerce/stencil-cli/commit/66ab50d))
-   refactor: (strf-8608) make fsUtils async ([bcab218](https://github.com/bigcommerce/stencil-cli/commit/bcab218))
-   refactor: (strf-8672) fix ESLint & Prettier errors and refactor some code ([300de1e](https://github.com/bigcommerce/stencil-cli/commit/300de1e))
-   refactor: move printErrorMessages() from theme-api-client.js to cliCommon.js ([d2c259b](https://github.com/bigcommerce/stencil-cli/commit/d2c259b))
-   refactor: move tests to GitHub Actions, remove Travis and AppVeyor ([18c6ff9](https://github.com/bigcommerce/stencil-cli/commit/18c6ff9))
-   refactor: moved common constants to constants.js ([a205c5b](https://github.com/bigcommerce/stencil-cli/commit/a205c5b))
-   refactor: moved StencilStart class to a separate file ([fdcdd82](https://github.com/bigcommerce/stencil-cli/commit/fdcdd82))
-   refactor: replace Promises with async/await in stencil-start ([9492a42](https://github.com/bigcommerce/stencil-cli/commit/9492a42))
-   refactor: strf-8606; removed unused modules "good", "good-console" ([1db7f5a](https://github.com/bigcommerce/stencil-cli/commit/1db7f5a))
-   refactor: use fs.existsSync instead of Fs.statSync hack ([e097e36](https://github.com/bigcommerce/stencil-cli/commit/e097e36))
-   refactor(.eslintrc): update .eslinrc to allow newer JS syntax ([f132275](https://github.com/bigcommerce/stencil-cli/commit/f132275))
-   refactor(/bin/stencil-start): rearrange some variables ([e8edabb](https://github.com/bigcommerce/stencil-cli/commit/e8edabb))
-   refactor(/lib/release.js): use async/await instead of callbacks ([720fbb1](https://github.com/bigcommerce/stencil-cli/commit/720fbb1))
-   refactor(stencil-init): improve code style and test coverage ([4ac65ff](https://github.com/bigcommerce/stencil-cli/commit/4ac65ff))
-   refactor(stencil-start): refactored the module to OOP style ([2ae5b0c](https://github.com/bigcommerce/stencil-cli/commit/2ae5b0c))
-   refactor(tests): move tests from /bin to /lib ([930922f](https://github.com/bigcommerce/stencil-cli/commit/930922f))
-   feat: (strf-8608) bump recent updates in npm packages ([e50e231](https://github.com/bigcommerce/stencil-cli/commit/e50e231))
-   feat: (strf-8608) deleted unused npm dependencies ([1f64ad9](https://github.com/bigcommerce/stencil-cli/commit/1f64ad9))
-   feat: (strf-8608) replace "request" with "node-fetch" ([e758b01](https://github.com/bigcommerce/stencil-cli/commit/e758b01))
-   feat: (strf-8608) replaced lab+code+sinon with jest ([71e952f](https://github.com/bigcommerce/stencil-cli/commit/71e952f))
-   feat: (strf-8608) update "front-matter" ([a0aa6fd](https://github.com/bigcommerce/stencil-cli/commit/a0aa6fd))
-   feat: (strf-8608) update "simple-git" ([7153455](https://github.com/bigcommerce/stencil-cli/commit/7153455))
-   feat: (strf-8608) update "tarjan-graph" ([4a27ee6](https://github.com/bigcommerce/stencil-cli/commit/4a27ee6))
-   feat: (strf-8608) updated some npm dependencies ([9059210](https://github.com/bigcommerce/stencil-cli/commit/9059210))
-   feat: (strf-8625) support Node 12.x ([1449751](https://github.com/bigcommerce/stencil-cli/commit/1449751))
-   feat: (strf-8630) fix template engine values ([0af2cb5](https://github.com/bigcommerce/stencil-cli/commit/0af2cb5))
-   feat: (strf-8671) replace "wreck" with "node-fetch" ([6dcdd9b](https://github.com/bigcommerce/stencil-cli/commit/6dcdd9b))
-   feat: (strf-8672) improve ESLint config and add prettier ([a8b78c8](https://github.com/bigcommerce/stencil-cli/commit/a8b78c8))
-   feat: (strf-8673) update "commander" ([dc3bf29](https://github.com/bigcommerce/stencil-cli/commit/dc3bf29))
-   feat: (strf-8674) update "async" npm package ([9f64096](https://github.com/bigcommerce/stencil-cli/commit/9f64096))
-   feat: (strf-8684) update 'tmp' package ([b1e932c](https://github.com/bigcommerce/stencil-cli/commit/b1e932c))
-   feat: bump paper to rc30, release 2.2.0 ([6945a3c](https://github.com/bigcommerce/stencil-cli/commit/6945a3c))
-   feat: bump paper to rc31 ([b958744](https://github.com/bigcommerce/stencil-cli/commit/b958744))
-   feat: init no longer prompts when cli option is present ([a9fee29](https://github.com/bigcommerce/stencil-cli/commit/a9fee29))
-   feat: make init command more suitable for automation ([ab9b919](https://github.com/bigcommerce/stencil-cli/commit/ab9b919))
-   feat: strf-8589, drop JSPM support ([c39c67b](https://github.com/bigcommerce/stencil-cli/commit/c39c67b))
-   feat: update "stencil pull" to use configurations API, improving performance ([2b142fc](https://github.com/bigcommerce/stencil-cli/commit/2b142fc))
-   feat: update cli to use template engine based on the value stored in ([f9ea0a9](https://github.com/bigcommerce/stencil-cli/commit/f9ea0a9))
-   feat(docs): add project structure and best practices ([251c1ff](https://github.com/bigcommerce/stencil-cli/commit/251c1ff))
-   Add npm cache ([ad50756](https://github.com/bigcommerce/stencil-cli/commit/ad50756))
-   Resolve Schema Translation Error Logging ([7e668df](https://github.com/bigcommerce/stencil-cli/commit/7e668df))
-   STRF-8582 Bump stencil-styles version ([6611284](https://github.com/bigcommerce/stencil-cli/commit/6611284))
-   Update test badges ([0fdafcf](https://github.com/bigcommerce/stencil-cli/commit/0fdafcf))
-   test: updates integration and unit tests ([9e6131d](https://github.com/bigcommerce/stencil-cli/commit/9e6131d))
-   test: use better naming of methods and constants ([506be68](https://github.com/bigcommerce/stencil-cli/commit/506be68))
-   chore: remove json schema since it has been replaced by ajv ([80911e5](https://github.com/bigcommerce/stencil-cli/commit/80911e5))

<a name="2.1.1"></a>

## <small>2.1.1 (2020-06-12)</small>

-feat: bump paper ([91acd1c](https://github.com/bigcommerce/stencil-cli/commit/91acd1c))
-feat: watch storefront config file ([e7b43d9](https://github.com/bigcommerce/stencil-cli/commit/e7b43d9))

<a name="2.1.0"></a>

## 2.1.0 (2020-04-27)

-   feat: added re-integration script with new command download ([dc6df02](https://github.com/bigcommerce/stencil-cli/commit/dc6df02))

<a name="2.0.0"></a>

## 2.0.0 (2020-03-24)

-   fix: address chrome cookie SameSite issue ([5938ce1](https://github.com/bigcommerce/stencil-cli/commit/5938ce1))
-   feat: add schema validation to bundle process ([b86d440](https://github.com/bigcommerce/stencil-cli/commit/b86d440))
-   feat: bump paper ([f1d2b5a](https://github.com/bigcommerce/stencil-cli/commit/f1d2b5a))
-   feat: deprecate theme editor ([c0466dc](https://github.com/bigcommerce/stencil-cli/commit/c0466dc))
-   feat(translate): added the translationsSchema.json file into a bundle ([ba04cd6](https://github.com/bigcommerce/stencil-cli/commit/ba04cd6))
-   feat(translate): added validation for schemaTranslations.json ([fccafe2](https://github.com/bigcommerce/stencil-cli/commit/fccafe2))
-   feat(translate): fixed regarding reviewers notes ([0a1f43d](https://github.com/bigcommerce/stencil-cli/commit/0a1f43d))

<a name="1.23.1"></a>

## <small>1.23.1 (2020-02-18)</small>

-   fix: add hapi as a direct dependency to lock down hapi version ([3b9a258](https://github.com/bigcommerce/stencil-cli/commit/3b9a258))

<a name="1.23.0"></a>

## 1.23.0 (2020-02-17)

-   fix: move code to dev dependency ([f1fd570](https://github.com/bigcommerce/stencil-cli/commit/f1fd570))
-   fix: remove less dependency and ref since it is not supported or used ([c586dd8](https://github.com/bigcommerce/stencil-cli/commit/c586dd8))
-   fix: tunnel issues and add support for tunnel names ([820fa4d](https://github.com/bigcommerce/stencil-cli/commit/820fa4d))
-   fix: update readme to reflect node 8 is no longer supported ([6e793a9](https://github.com/bigcommerce/stencil-cli/commit/6e793a9))
-   feat: drop node 8 support ([5aa1624](https://github.com/bigcommerce/stencil-cli/commit/5aa1624))
-   feat: move lab to dev deps and update it to 14.3.3 ([0f57631](https://github.com/bigcommerce/stencil-cli/commit/0f57631))
-   feat: remove hapi as a direct dependecy ([3164fbc](https://github.com/bigcommerce/stencil-cli/commit/3164fbc))
-   feat: update browser sync to use latest master ([0916991](https://github.com/bigcommerce/stencil-cli/commit/0916991))
-   feat: update colors dependency ([b488557](https://github.com/bigcommerce/stencil-cli/commit/b488557))
-   feat: upgrade lodash dependency ([640c61d](https://github.com/bigcommerce/stencil-cli/commit/640c61d))
-   feat(dependencies): update eslint to the latest and fix lint errors ([5a2fd85](https://github.com/bigcommerce/stencil-cli/commit/5a2fd85))

<a name="1.22.0"></a>

## 1.22.0 (2020-02-10)

-   feat(dependencies): remove compression as a dependency ([2c02e9e](https://github.com/bigcommerce/stencil-cli/commit/2c02e9e))
-   feat(dependencies): remove decompress-zip as a dependency ([34c7fde](https://github.com/bigcommerce/stencil-cli/commit/34c7fde))
-   feat(dependencies): remove express as a dependecy since it is not used ([ba1c2c5](https://github.com/bigcommerce/stencil-cli/commit/ba1c2c5))
-   feat(dependencies): remove gulp git, sass, sass-lint dependency ([14dceeb](https://github.com/bigcommerce/stencil-cli/commit/14dceeb))
-   feat(dependencies): remove install as a dependency since it is not used ([1c2549c](https://github.com/bigcommerce/stencil-cli/commit/1c2549c))
-   feat(dependencies): remove npm as a dependency ([4733649](https://github.com/bigcommerce/stencil-cli/commit/4733649))
-   feat(dependencies): remove script-loader as a direct dependecy ([9a2b817](https://github.com/bigcommerce/stencil-cli/commit/9a2b817))
-   feat(dependencies): update dev dependency ([d5bdfe3](https://github.com/bigcommerce/stencil-cli/commit/d5bdfe3))

<a name="1.21.6"></a>

## <small>1.21.6 (2020-02-04)</small>

-   Add feature to allow pulling live config files (#550) ([43558fc](https://github.com/bigcommerce/stencil-cli/commit/43558fc))
-   fix: add account_payment_methods_v2 to theme config schema ([373a485](https://github.com/bigcommerce/stencil-cli/commit/373a485))
-   feat(dependencies): remove dateformat as a direct dependecy ([6044e91](https://github.com/bigcommerce/stencil-cli/commit/6044e91))

<a name="1.21.5"></a>

## <small>1.21.5 (2020-01-30)</small>

-   feat: add flag to auto-delete oldest theme during push ([ea93793](https://github.com/bigcommerce/stencil-cli/commit/ea93793))
-   feat: bump paper to 3.0.0-rc.27 ([86e4f74](https://github.com/bigcommerce/stencil-cli/commit/86e4f74))
-   fix: more detailed theme variation error ([96e3a30](https://github.com/bigcommerce/stencil-cli/commit/96e3a30))
-   fix: schema.json formatting ([73c8a26](https://github.com/bigcommerce/stencil-cli/commit/73c8a26))

<a name="1.21.4"></a>

## <small>1.21.4 (2019-12-20)</small>

<a name="1.21.3"></a>

## <small>1.21.3 (2019-12-20)</small>

-   fix: avoid caching of storefront api responses ([9974a07](https://github.com/bigcommerce/stencil-cli/commit/9974a07))
-   fix: correcting url for deploy issues docs ([44ef5e9](https://github.com/bigcommerce/stencil-cli/commit/44ef5e9))
-   fix: fix origin sent with graphql requests (#541) ([8f3f02c](https://github.com/bigcommerce/stencil-cli/commit/8f3f02c))

<a name="1.21.2"></a>

## <small>1.21.2 (2019-11-15)</small>

-   fix: bump stencil-styles to 1.2.0 ([97389b9](https://github.com/bigcommerce/stencil-cli/commit/97389b9))

<a name="1.21.1"></a>

## <small>1.21.1 (2019-10-22)</small>

-   fix: update paper to 3.0.0-rc.26 ([32ef114](https://github.com/bigcommerce/stencil-cli/commit/32ef114))

<a name="1.21.0"></a>

## 1.21.0 (2019-10-14)

-   Adding Support for Node 10 (#525) ([3013fb4](https://github.com/bigcommerce/stencil-cli/commit/3013fb4))

<a name="1.20.3"></a>

## <small>1.20.3 (2019-10-10)</small>

-   feat: strf-7393 make cli work with paper 3.x branch ([7ba9688](https://github.com/bigcommerce/stencil-cli/commit/7ba9688))

<a name="1.20.2"></a>

## <small>1.20.2 (2019-09-12)</small>

-   fix: bump paper to 2.0.19 ([670a7ad](https://github.com/bigcommerce/stencil-cli/commit/670a7ad))
-   Revert "Merge pull request #500 from bc-williamkwon/changePaperBranch" ([3e195e8](https://github.com/bigcommerce/stencil-cli/commit/3e195e8))
-   Revert "Merge pull request #506 from bookernath/paper-rc.20" ([5ada1b4](https://github.com/bigcommerce/stencil-cli/commit/5ada1b4))

<a name="1.20.1"></a>

## <small>1.20.1 (2019-09-05)</small>

-   Revert "Merge pull request #491 from bookernath/browser-sync-master" ([020ca91](https://github.com/bigcommerce/stencil-cli/commit/020ca91))

<a name="1.20.0"></a>

## 1.20.0 (2019-08-16)

-   feat: accept url and token as arguments on stencil init ([b69a9fe](https://github.com/bigcommerce/stencil-cli/commit/b69a9fe))

<a name="1.19.0"></a>

## 1.19.0 (2019-08-07)

-   fix: bump paper to 3.0.0-rc20 ([e9c7691](https://github.com/bigcommerce/stencil-cli/commit/e9c7691))
-   feat: strf-7175 bump paper to 3.0.0-rc.19 ([eb5ef78](https://github.com/bigcommerce/stencil-cli/commit/eb5ef78))

<a name="1.18.0"></a>

## 1.18.0 (2019-08-01)

-   feat: bump paper to 2.0.18 ([fa71b05](https://github.com/bigcommerce/stencil-cli/commit/fa71b05))
-   feat: remove client id from required fields ([0cbc093](https://github.com/bigcommerce/stencil-cli/commit/0cbc093))
-   fix: strf-7023 move browser-sync back to master ([c3db4db](https://github.com/bigcommerce/stencil-cli/commit/c3db4db))

<a name="1.17.0"></a>

## 1.17.0 (2019-07-15)

-   feat: update stencil-paper to add getImageSrcset helper ([892fbfd](https://github.com/bigcommerce/stencil-cli/commit/892fbfd))
-   Update README ([73898c0](https://github.com/bigcommerce/stencil-cli/commit/73898c0))

<a name="1.16.0"></a>

## 1.16.0 (2019-06-04)

-   Remove Node 6 from Travis ([1cab37f](https://github.com/bigcommerce/stencil-cli/commit/1cab37f))
-   fix: strf-6383 add check for template size for stencil bundling ([f674c05](https://github.com/bigcommerce/stencil-cli/commit/f674c05))
-   fix: update engines for node in package.json ([70ae9a3](https://github.com/bigcommerce/stencil-cli/commit/70ae9a3))
-   feat: strf-6687 update stencil-paper to add font-display support ([3af5562](https://github.com/bigcommerce/stencil-cli/commit/3af5562))

<a name="1.15.9"></a>

## <small>1.15.9 (2019-04-03)</small>

-   fix: added browser-sync to package-lock (#454) ([dcc4795](https://github.com/bigcommerce/stencil-cli/commit/dcc4795))
-   Revert "feat: Add support for base_url and secure_base_url" (#453) ([74d1122](https://github.com/bigcommerce/stencil-cli/commit/74d1122))

<a name="1.15.8"></a>

## <small>1.15.8 (2019-04-02)</small>

-   ci: updated paper to 2.0.12 (#451) ([5e83f64](https://github.com/bigcommerce/stencil-cli/commit/5e83f64))
-   docs: Update stencil cli installation link ([834fee2](https://github.com/bigcommerce/stencil-cli/commit/834fee2))
-   feat: Add support for base_url and secure_base_url ([cc3ca08](https://github.com/bigcommerce/stencil-cli/commit/cc3ca08))

<a name="1.15.7"></a>

## <small>1.15.7 (2019-03-26)</small>

<a name="1.15.6"></a>

## <small>1.15.6 (2019-03-07)</small>

-   fix: added bump of package-lock.json to gulp release task (#448) ([f2c423b](https://github.com/bigcommerce/stencil-cli/commit/f2c423b))
-   fix: revert paper_2.0.11 pr (#445) ([adf424f](https://github.com/bigcommerce/stencil-cli/commit/adf424f))
-   docs: updated paper to 2.0.11 + checked package-lock (#446) ([54ddad0](https://github.com/bigcommerce/stencil-cli/commit/54ddad0))
-   docs(release): releasing 1.15.6 ([0bb0eb1](https://github.com/bigcommerce/stencil-cli/commit/0bb0eb1))
-   Docs: upgraded paper (#441) ([26b3937](https://github.com/bigcommerce/stencil-cli/commit/26b3937))
-   feat(theme): add csrf protection to the list of valid features ([fe4b795](https://github.com/bigcommerce/stencil-cli/commit/fe4b795))

<a name="1.15.5"></a>

## <small>1.15.5 (2019-02-05)</small>

-   fix: added fix for scss compilation issue ([e6a20a2](https://github.com/bigcommerce/stencil-cli/commit/e6a20a2))
-   fix(cp): STRF-5614 Add enhanced_ecommerce to theme config schema. ([58c6fb9](https://github.com/bigcommerce/stencil-cli/commit/58c6fb9))
-   feat: changelog generator (#431) ([9e6e225](https://github.com/bigcommerce/stencil-cli/commit/9e6e225))
-   Increase timeout for build worker process to be ready ([794e796](https://github.com/bigcommerce/stencil-cli/commit/794e796))
-   log push errors to the console ([a9aca72](https://github.com/bigcommerce/stencil-cli/commit/a9aca72))
-   PROJECT-1897: Card Management - List, Delete, Edit, Add Cards ([44022a0](https://github.com/bigcommerce/stencil-cli/commit/44022a0))
-   Proper error handling for bundle task ([a4dc6c9](https://github.com/bigcommerce/stencil-cli/commit/a4dc6c9))
-   update paper npm version ([d5f78a4](https://github.com/bigcommerce/stencil-cli/commit/d5f78a4))
-   Update README ([298beaa](https://github.com/bigcommerce/stencil-cli/commit/298beaa))
-   upgrade paper package to 2.0.10 ([b4ec832](https://github.com/bigcommerce/stencil-cli/commit/b4ec832))

<a name="1.15.4"></a>

## <small>1.15.4 (2018-12-17)</small>

-   fix(cp): STRF-5614 Add enhanced_ecommerce to theme config schema. ([58c6fb9](https://github.com/bigcommerce/stencil-cli/commit/58c6fb9))

<a name="1.15.3"></a>

## <small>1.15.3 (2018-12-11)</small>

-   upgrade paper package to 2.0.10 ([b4ec832](https://github.com/bigcommerce/stencil-cli/commit/b4ec832))
-   Proper error handling for bundle task ([a4dc6c9](https://github.com/bigcommerce/stencil-cli/commit/a4dc6c9))
-   PROJECT-1897: Card Management - List, Delete, Edit, Add Cards ([44022a0](https://github.com/bigcommerce/stencil-cli/commit/44022a0))
-   Increase timeout for build worker process to be ready ([794e796](https://github.com/bigcommerce/stencil-cli/commit/794e796))
-   log push errors to the console ([a9aca72](https://github.com/bigcommerce/stencil-cli/commit/a9aca72))
-   update paper npm version ([d5f78a4](https://github.com/bigcommerce/stencil-cli/commit/d5f78a4))
-   Point to http instead of https for stencil editor sdk. ([0a9acf6](https://github.com/bigcommerce/stencil-cli/commit/0a9acf6))
-   Update README ([298beaa](https://github.com/bigcommerce/stencil-cli/commit/298beaa))
-   Deprecate support for node 4.x ([e5c3e96](https://github.com/bigcommerce/stencil-cli/commit/e5c3e96))
-   Deprecate support for node 4.x ([1ead058](https://github.com/bigcommerce/stencil-cli/commit/1ead058))
-   Bundle all webpack files + release 1.15.0 ([537bb93](https://github.com/bigcommerce/stencil-cli/commit/537bb93))
-   STRF-4889: Fix error message for upload limit ([95ba66b](https://github.com/bigcommerce/stencil-cli/commit/95ba66b))
-   Update paper & bump version ([9217d6f](https://github.com/bigcommerce/stencil-cli/commit/9217d6f))
-   adding -a and --activate flags to stencil push ([5f2ceb8](https://github.com/bigcommerce/stencil-cli/commit/5f2ceb8))
-   Update README.md to include min versions of Node ([cf9798c](https://github.com/bigcommerce/stencil-cli/commit/cf9798c))
-   trailing comma on output ([0d77cd6](https://github.com/bigcommerce/stencil-cli/commit/0d77cd6))
-   ability to locally save bundled theme after push ([f9610d0](https://github.com/bigcommerce/stencil-cli/commit/f9610d0))
