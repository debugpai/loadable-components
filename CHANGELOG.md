# Change Log

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

# [5.8.0](https://github.com/smooth-code/loadable-components/compare/v5.7.2...v5.8.0) (2019-04-10)


### Bug Fixes

* **babel-plugin:** Use require.resolve instead of relative path resolution ([#303](https://github.com/smooth-code/loadable-components/issues/303)) ([bad7f1f](https://github.com/smooth-code/loadable-components/commit/bad7f1f))


### Features

* **ChunkExtractor:** support publicPath override ([#292](https://github.com/smooth-code/loadable-components/issues/292)) ([9731e9c](https://github.com/smooth-code/loadable-components/commit/9731e9c))
* **server:** support function in attributes ([#277](https://github.com/smooth-code/loadable-components/issues/277)) ([c172324](https://github.com/smooth-code/loadable-components/commit/c172324))


### Performance Improvements

* **server:** improve lodash imports for serverless bundles ([#298](https://github.com/smooth-code/loadable-components/issues/298)) ([96841f2](https://github.com/smooth-code/loadable-components/commit/96841f2))





## [5.7.2](https://github.com/smooth-code/loadable-components/compare/v5.7.1...v5.7.2) (2019-03-20)


### Bug Fixes

* **babel-plugin:** handle "-" at the end of request ([c0f325b](https://github.com/smooth-code/loadable-components/commit/c0f325b))





## [5.7.1](https://github.com/smooth-code/loadable-components/compare/v5.7.0...v5.7.1) (2019-03-19)


### Bug Fixes

* **babel-plugin:** handle special chars in file names ([#279](https://github.com/smooth-code/loadable-components/issues/279)) ([4da39ff](https://github.com/smooth-code/loadable-components/commit/4da39ff))
* **webpack-plugin:** create output folder with mkdirp ([#273](https://github.com/smooth-code/loadable-components/issues/273)) ([3767f28](https://github.com/smooth-code/loadable-components/commit/3767f28))





# [5.7.0](https://github.com/smooth-code/loadable-components/compare/v5.6.1...v5.7.0) (2019-03-14)


### Bug Fixes

* **component:** fix warning message about babel ([#255](https://github.com/smooth-code/loadable-components/issues/255)) ([7cb68a1](https://github.com/smooth-code/loadable-components/commit/7cb68a1)), closes [#253](https://github.com/smooth-code/loadable-components/issues/253)
* **server:** fix loading order of assets ([#266](https://github.com/smooth-code/loadable-components/issues/266)) ([4c8ae60](https://github.com/smooth-code/loadable-components/commit/4c8ae60))


### Features

* use inline JSON to enabling CSP without `unsafe-inline` ([05e5500](https://github.com/smooth-code/loadable-components/commit/05e5500))


### Performance Improvements

* **build:** add build target for Node ([#267](https://github.com/smooth-code/loadable-components/issues/267)) ([97ff6ac](https://github.com/smooth-code/loadable-components/commit/97ff6ac))





## [5.6.1](https://github.com/smooth-code/loadable-components/compare/v5.6.0...v5.6.1) (2019-02-25)


### Bug Fixes

* **component:** better ES Modules handling ([#228](https://github.com/smooth-code/loadable-components/issues/228)) ([3628363](https://github.com/smooth-code/loadable-components/commit/3628363))
* **server:** allow query-param cache busting in chunk names ([#229](https://github.com/smooth-code/loadable-components/issues/229)) ([71f7bcd](https://github.com/smooth-code/loadable-components/commit/71f7bcd))
* **server:** use `eval` to prevent webpack warning ([#240](https://github.com/smooth-code/loadable-components/issues/240)) ([948165d](https://github.com/smooth-code/loadable-components/commit/948165d)), closes [#234](https://github.com/smooth-code/loadable-components/issues/234)
* **suspense:** fix suspense mode in React v16.8+ ([#251](https://github.com/smooth-code/loadable-components/issues/251)) ([d04e1c9](https://github.com/smooth-code/loadable-components/commit/d04e1c9))





# [5.6.0](https://github.com/smooth-code/loadable-components/compare/v5.5.0...v5.6.0) (2019-02-05)


### Bug Fixes

* Add extra props option for links ([#212](https://github.com/smooth-code/loadable-components/issues/212)) ([6714d2a](https://github.com/smooth-code/loadable-components/commit/6714d2a))
* **server:** fix chunkName resolving ([#219](https://github.com/smooth-code/loadable-components/issues/219)) ([ef11e11](https://github.com/smooth-code/loadable-components/commit/ef11e11))


### Features

* **babel-plugin:** transform code annotated with magic comment ([4f832dc](https://github.com/smooth-code/loadable-components/commit/4f832dc)), closes [#192](https://github.com/smooth-code/loadable-components/issues/192)
* **component:** add preload method ([#224](https://github.com/smooth-code/loadable-components/issues/224)) ([4a67ace](https://github.com/smooth-code/loadable-components/commit/4a67ace)), closes [#196](https://github.com/smooth-code/loadable-components/issues/196)
* **server:** add option to disable SSR ([#223](https://github.com/smooth-code/loadable-components/issues/223)) ([4cab4f9](https://github.com/smooth-code/loadable-components/commit/4cab4f9)), closes [#195](https://github.com/smooth-code/loadable-components/issues/195)





# [5.5.0](https://github.com/smooth-code/loadable-components/compare/v5.4.0...v5.5.0) (2019-01-22)


### Features

* allow to specify extra attributes in getScriptTags & others ([#210](https://github.com/smooth-code/loadable-components/issues/210)) ([8a3d067](https://github.com/smooth-code/loadable-components/commit/8a3d067))





# [5.4.0](https://github.com/smooth-code/loadable-components/compare/v5.3.0...v5.4.0) (2019-01-17)


### Features

* **webpack-plugin:** support custom path in writeToDisk option ([#187](https://github.com/smooth-code/loadable-components/issues/187)) ([4a6f84f](https://github.com/smooth-code/loadable-components/commit/4a6f84f))





# [5.3.0](https://github.com/smooth-code/loadable-components/compare/v5.2.2...v5.3.0) (2019-01-11)


### Features

* support inline CSS ([#190](https://github.com/smooth-code/loadable-components/issues/190)) ([2caf676](https://github.com/smooth-code/loadable-components/commit/2caf676))





## [5.2.2](https://github.com/smooth-code/loadable-components/compare/v5.2.1...v5.2.2) (2018-12-12)


### Bug Fixes

* **babel-plugin:** fix chunkName with aggressive code splitting ([e974933](https://github.com/smooth-code/loadable-components/commit/e974933)), closes [#182](https://github.com/smooth-code/loadable-components/issues/182)
* ensure that component is mounted before calling `setState` ([#184](https://github.com/smooth-code/loadable-components/issues/184)) ([fe0f47f](https://github.com/smooth-code/loadable-components/commit/fe0f47f)), closes [#180](https://github.com/smooth-code/loadable-components/issues/180)
* **server:** fix usage when compiled using webpack ([#185](https://github.com/smooth-code/loadable-components/issues/185)) ([5e28870](https://github.com/smooth-code/loadable-components/commit/5e28870)), closes [#181](https://github.com/smooth-code/loadable-components/issues/181)





## [5.2.1](https://github.com/smooth-code/loadable-components/compare/v5.2.0...v5.2.1) (2018-11-27)


### Bug Fixes

* **webpack-plugin:** fix TypeError when set writeToDisk true ([#170](https://github.com/smooth-code/loadable-components/issues/170)) ([2d1fb11](https://github.com/smooth-code/loadable-components/commit/2d1fb11))
* upgrade hoist-non-react-statics@3.2.0 ([122b1ce](https://github.com/smooth-code/loadable-components/commit/122b1ce))





# [5.2.0](https://github.com/smooth-code/loadable-components/compare/v5.1.3...v5.2.0) (2018-11-23)


### Bug Fixes

* **server:** fix url join ([#166](https://github.com/smooth-code/loadable-components/issues/166)) ([ba90289](https://github.com/smooth-code/loadable-components/commit/ba90289))
* **server:** support protocol free paths ([#163](https://github.com/smooth-code/loadable-components/issues/163)) ([3b5b115](https://github.com/smooth-code/loadable-components/commit/3b5b115))


### Features

* **webpack-plugin:** add writeToDisk option ([#161](https://github.com/smooth-code/loadable-components/issues/161)) ([6b5ba21](https://github.com/smooth-code/loadable-components/commit/6b5ba21))





## [5.1.3](https://github.com/smooth-code/loadable-components/compare/v5.1.2...v5.1.3) (2018-11-20)


### Bug Fixes

* **server:** exclude http and https from regex ([#155](https://github.com/smooth-code/loadable-components/issues/155)) ([0bb2ad9](https://github.com/smooth-code/loadable-components/commit/0bb2ad9)), closes [#153](https://github.com/smooth-code/loadable-components/issues/153)
* **server:** ignore *.hot-update.js ([edcd2c8](https://github.com/smooth-code/loadable-components/commit/edcd2c8)), closes [#148](https://github.com/smooth-code/loadable-components/issues/148)





## [5.1.2](https://github.com/smooth-code/loadable-components/compare/v5.1.1...v5.1.2) (2018-11-13)


### Bug Fixes

* fix ref handler in `loadable.lib` ([da05d87](https://github.com/smooth-code/loadable-components/commit/da05d87))





## [5.1.1](https://github.com/smooth-code/loadable-components/compare/v5.1.0...v5.1.1) (2018-11-13)


### Bug Fixes

* **server:** ignore source maps ([9991bbd](https://github.com/smooth-code/loadable-components/commit/9991bbd)), closes [#128](https://github.com/smooth-code/loadable-components/issues/128)





# [5.1.0](https://github.com/smooth-code/loadable-components/compare/v5.0.2...v5.1.0) (2018-11-10)


### Features

* **server:** add outputPath option in ChunkExtractor ([aac26b3](https://github.com/smooth-code/loadable-components/commit/aac26b3))





## [5.0.2](https://github.com/smooth-code/loadable-components/compare/v5.0.1...v5.0.2) (2018-11-10)


### Bug Fixes

* update peer dependencies ([b0363dc](https://github.com/smooth-code/loadable-components/commit/b0363dc))





# [5.0.0](https://github.com/smooth-code/loadable-components/compare/v4.0.5...v5.0.0) (2018-11-10)


### Bug Fixes

* fix loadableReady ([59693bb](https://github.com/smooth-code/loadable-components/commit/59693bb))


### Features

* improve SSR support ([eb1cfe8](https://github.com/smooth-code/loadable-components/commit/eb1cfe8))


### BREAKING CHANGES

* - SSR has been rewritten from scratch, if you use it, please follow the
new guide.
- Prefetch component and prefetch functions have been removed, please
use `webpackPrefetch` instead.





## [4.0.5](https://github.com/smooth-code/loadable-components/compare/v4.0.4...v4.0.5) (2018-11-01)


### Bug Fixes

* **server:** fix getScriptElements ([ba424e0](https://github.com/smooth-code/loadable-components/commit/ba424e0))





## [4.0.4](https://github.com/smooth-code/loadable-components/compare/v4.0.3...v4.0.4) (2018-10-31)


### Bug Fixes

* fix peer dependencies ([6816e8c](https://github.com/smooth-code/loadable-components/commit/6816e8c))





## [4.0.3](https://github.com/smooth-code/loadable-components/compare/v4.0.2...v4.0.3) (2018-10-31)


### Bug Fixes

* **server:** disable common chunks optim ([78e7b28](https://github.com/smooth-code/loadable-components/commit/78e7b28))





## [4.0.2](https://github.com/smooth-code/loadable-components/compare/v4.0.1...v4.0.2) (2018-10-31)


### Bug Fixes

* **babel-plugin:** transform into friendly chunk name ([54422cb](https://github.com/smooth-code/loadable-components/commit/54422cb))
* **component:** fix lazy usage ([d711ee0](https://github.com/smooth-code/loadable-components/commit/d711ee0))





## [4.0.1](https://github.com/smooth-code/loadable-components/compare/v4.0.0...v4.0.1) (2018-10-30)


### Bug Fixes

* **component:** do not call ref several times ([8cf3190](https://github.com/smooth-code/loadable-components/commit/8cf3190))





# [4.0.0](https://github.com/smooth-code/loadable-components/compare/v3.0.2...v4.0.0) (2018-10-30)


### Features

* add new loadable.lib, change API ([94b2e87](https://github.com/smooth-code/loadable-components/commit/94b2e87))


### BREAKING CHANGES

* - `ErrorComponent` is ignored, please use Error Boundaries to handle errors.
- `lazy` is no longer exported
- `LoadingComponent` is replaced by `fallback` option
- `ref` are now forwarded





## [3.0.2](https://github.com/smooth-code/loadable-components/compare/v3.0.1...v3.0.2) (2018-10-30)


### Bug Fixes

* **component:** fix loadComponent (typo) ([a410cb2](https://github.com/smooth-code/loadable-components/commit/a410cb2))





## [3.0.1](https://github.com/smooth-code/loadable-components/compare/v3.0.0...v3.0.1) (2018-10-30)


### Bug Fixes

* **component:** fix loadComponents ([bd2220c](https://github.com/smooth-code/loadable-components/commit/bd2220c))





# [3.0.0](https://github.com/smooth-code/loadable-components/compare/v2.2.3...v3.0.0) (2018-10-29)


### Bug Fixes

* **typescript:** restore types ([#113](https://github.com/smooth-code/loadable-components/issues/113)) ([240bb8f](https://github.com/smooth-code/loadable-components/commit/240bb8f))


### Features

* welcome loadable ([4dffad7](https://github.com/smooth-code/loadable-components/commit/4dffad7))


### BREAKING CHANGES

* API has completely changed, see documentation.





# Change Log

All notable changes to this project will be documented in this file. See [standard-version](https://github.com/conventional-changelog/standard-version) for commit guidelines.

<a name="2.2.3"></a>
## [2.2.3](https://github.com/smooth-code/loadable-components/compare/v2.2.2...v2.2.3) (2018-08-16)


### Bug Fixes

* fix type definitions (#95) ([8402c19](https://github.com/smooth-code/loadable-components/commit/8402c19)), closes [#95](https://github.com/smooth-code/loadable-components/issues/95)
* support non-ES modules (#104) ([2a82314](https://github.com/smooth-code/loadable-components/commit/2a82314))



<a name="2.2.2"></a>
## [2.2.2](https://github.com/smooth-code/loadable-components/compare/v2.2.1...v2.2.2) (2018-05-25)


### Bug Fixes

* fix error handling in loadComponents (#87) ([d32c74c](https://github.com/smooth-code/loadable-components/commit/d32c74c)), closes [#87](https://github.com/smooth-code/loadable-components/issues/87)



<a name="2.2.1"></a>
## [2.2.1](https://github.com/smooth-code/loadable-components/compare/v2.2.0...v2.2.1) (2018-05-23)



<a name="2.2.0"></a>
# [2.2.0](https://github.com/smooth-code/loadable-components/compare/v2.1.0...v2.2.0) (2018-05-23)


### Bug Fixes

* fix SSR with HMR #85 ([20138e1](https://github.com/smooth-code/loadable-components/commit/20138e1)), closes [#85](https://github.com/smooth-code/loadable-components/issues/85)


### Features

* experimental suspense 🤩 ([57ce712](https://github.com/smooth-code/loadable-components/commit/57ce712))



<a name="2.1.0"></a>
# [2.1.0](https://github.com/smooth-code/loadable-components/compare/v2.0.1...v2.1.0) (2018-05-13)


### Features

* add TypeScript definitions (#80) ([db19796](https://github.com/smooth-code/loadable-components/commit/db19796))



<a name="2.0.1"></a>
## [2.0.1](https://github.com/smooth-code/loadable-components/compare/v2.0.0...v2.0.1) (2018-05-12)


### Bug Fixes

* fix module resolving ([10318b0](https://github.com/smooth-code/loadable-components/commit/10318b0)), closes [#59](https://github.com/smooth-code/loadable-components/issues/59)



<a name="2.0.0"></a>
# [2.0.0](https://github.com/smooth-code/loadable-components/compare/v1.4.0...v2.0.0) (2018-05-10)


### Bug Fixes

* do not propagate componentId ([fff1248](https://github.com/smooth-code/loadable-components/commit/fff1248))


### Code Refactoring

* remove HMR relative code ([ef0817c](https://github.com/smooth-code/loadable-components/commit/ef0817c))


### BREAKING CHANGES

* `setConfig` is no longer available.



<a name="1.4.0"></a>
# [1.4.0](https://github.com/smooth-code/loadable-components/compare/v1.3.0...v1.4.0) (2018-04-18)


### Bug Fixes

* set correct loading state if component is already loaded. (#64) ([9b0cae2](https://github.com/smooth-code/loadable-components/commit/9b0cae2))


### Features

* support React.createContext API (#65) ([289ad67](https://github.com/smooth-code/loadable-components/commit/289ad67))



<a name="1.3.0"></a>
# [1.3.0](https://github.com/smooth-code/loadable-components/compare/v1.2.0...v1.3.0) (2018-04-06)


### Bug Fixes

* circular structure in error object (#60) ([96333ca](https://github.com/smooth-code/loadable-components/commit/96333ca))
* React 16.3 compatibility ([abd7963](https://github.com/smooth-code/loadable-components/commit/abd7963)), closes [#57](https://github.com/smooth-code/loadable-components/issues/57)


### Features

* attach static properties on load ([d383fab](https://github.com/smooth-code/loadable-components/commit/d383fab)), closes [#58](https://github.com/smooth-code/loadable-components/issues/58)



<a name="1.2.0"></a>
# [1.2.0](https://github.com/smooth-code/loadable-components/compare/v1.1.1...v1.2.0) (2018-03-25)


### Features

* add Hot Reload support ([c79085e](https://github.com/smooth-code/loadable-components/commit/c79085e))



<a name="1.1.1"></a>
## [1.1.1](https://github.com/smooth-code/loadable-components/compare/v1.1.0...v1.1.1) (2018-02-06)


### Bug Fixes

* **snapshot:** fix snap usage ([3445bea](https://github.com/smooth-code/loadable-components/commit/3445bea)), closes [#40](https://github.com/smooth-code/loadable-components/issues/40)



<a name="1.1.0"></a>
# [1.1.0](https://github.com/smooth-code/loadable-components/compare/v1.0.2...v1.1.0) (2018-02-04)


### Features

* ship a single js file ([99e08c0](https://github.com/smooth-code/loadable-components/commit/99e08c0))



<a name="1.0.2"></a>
## [1.0.2](https://github.com/smooth-code/loadable-components/compare/v1.0.1...v1.0.2) (2018-02-04)


### Bug Fixes

* state could have no children ([a47c410](https://github.com/smooth-code/loadable-components/commit/a47c410)), closes [#36](https://github.com/smooth-code/loadable-components/issues/36)



<a name="1.0.1"></a>
## [1.0.1](https://github.com/smooth-code/loadable-components/compare/v1.0.0...v1.0.1) (2018-02-03)


### Bug Fixes

* fix loadComponents without valid state ([35f81a6](https://github.com/smooth-code/loadable-components/commit/35f81a6)), closes [#34](https://github.com/smooth-code/loadable-components/issues/34)



<a name="1.0.0"></a>
# [1.0.0](https://github.com/smooth-code/loadable-components/compare/v0.4.0...v1.0.0) (2018-02-02)


### Features

* stable version 1 ([601bd34](https://github.com/smooth-code/loadable-components/commit/601bd34))


### BREAKING CHANGES

* loadable-components/babel is now required if you do server side rendering.
* ErrorComponent now receive `ownProps` instead of `props`.
