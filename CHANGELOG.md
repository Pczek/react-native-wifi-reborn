## [3.1.2](https://github.com/JuanSeBestia/react-native-wifi-reborn/compare/v3.1.1...v3.1.2) (2020-04-16)


### Bug Fixes

* Add null type to password on connectToProtectedSSID ([#60](https://github.com/JuanSeBestia/react-native-wifi-reborn/issues/60)) ([9ad28cc](https://github.com/JuanSeBestia/react-native-wifi-reborn/commit/9ad28cc3642d3b2abf62978e8ed552cf13151f23))

## [3.1.1](https://github.com/JuanSeBestia/react-native-wifi-reborn/compare/v3.1.0...v3.1.1) (2020-03-22)


### Bug Fixes

* add location permission explanation on the readme ([12810b8](https://github.com/JuanSeBestia/react-native-wifi-reborn/commit/12810b8d3cedf1b0bdb980a56ce2075f48e785b8))

# [3.1.0](https://github.com/JuanSeBestia/react-native-wifi-reborn/compare/v3.0.0...v3.1.0) (2020-03-22)


### Features

* **forceWifiUsage:** remove need of the WRITE_SETTINGS. Api calls to a wifi network without internet access can perfectly be done without ([7c9daef](https://github.com/JuanSeBestia/react-native-wifi-reborn/commit/7c9daef69d0c38536d087b1489e753673a8b89fd))

# [3.0.0](https://github.com/JuanSeBestia/react-native-wifi-reborn/compare/v2.4.0...v3.0.0) (2020-03-17)


* Merge pull request #46 from inthepocket/feature/use-wifiutils-for-android-with-semantics ([eeea1af](https://github.com/JuanSeBestia/react-native-wifi-reborn/commit/eeea1afc1e42a78ce785a42dae3ff626cea3fe33)), closes [#46](https://github.com/JuanSeBestia/react-native-wifi-reborn/issues/46)


### BREAKING CHANGES

* Use WifiUtils to connect with a wifi network

# [2.4.0](https://github.com/JuanSeBestia/react-native-wifi-reborn/compare/v2.3.4...v2.4.0) (2020-03-04)


### Features

* Add TypeScript declaration ([#44](https://github.com/JuanSeBestia/react-native-wifi-reborn/issues/44)) ([610fc32](https://github.com/JuanSeBestia/react-native-wifi-reborn/commit/610fc32bc01959518b6d4345a3ddab2e1138f085))

## [2.3.4](https://github.com/JuanSeBestia/react-native-wifi-reborn/compare/v2.3.3...v2.3.4) (2020-03-04)


### Performance Improvements

* Reduce package size ([#43](https://github.com/JuanSeBestia/react-native-wifi-reborn/issues/43)) ([d108823](https://github.com/JuanSeBestia/react-native-wifi-reborn/commit/d108823989538a5d102b034f393bfada21619b75))

## [2.3.3](https://github.com/JuanSeBestia/react-native-wifi-reborn/compare/v2.3.2...v2.3.3) (2020-02-27)


### Bug Fixes

* **iOS:** Fix joinOnce for connectToSSIDPrefix ([#40](https://github.com/JuanSeBestia/react-native-wifi-reborn/issues/40)) ([61185a9](https://github.com/JuanSeBestia/react-native-wifi-reborn/commit/61185a960b06fe621af3c4c8c8d114036b7ff042))

## [2.3.2](https://github.com/JuanSeBestia/react-native-wifi-reborn/compare/v2.3.1...v2.3.2) (2020-01-21)


### Bug Fixes

* **android:** Verify connection after enabling network ([#31](https://github.com/JuanSeBestia/react-native-wifi-reborn/issues/31)) ([9fa86ee](https://github.com/JuanSeBestia/react-native-wifi-reborn/commit/9fa86ee0141535bd142f0e10ff4fd698ccda3533))

## [2.3.1](https://github.com/JuanSeBestia/react-native-wifi-reborn/compare/v2.3.0...v2.3.1) (2020-01-16)


### Bug Fixes

* **iOS:** Use joinOnce as mentioned https://github.com/JuanSeBestia/react-native-wifi-reborn/issues/2. ([#33](https://github.com/JuanSeBestia/react-native-wifi-reborn/issues/33)) ([6c71618](https://github.com/JuanSeBestia/react-native-wifi-reborn/commit/6c7161857b17866594ed49cc96b6bda49b74fb40))

# [2.3.0](https://github.com/JuanSeBestia/react-native-wifi-reborn/compare/v2.2.4...v2.3.0) (2020-01-16)


### Features

* **iOS:** Connect to SSID prefix functions. ([#25](https://github.com/JuanSeBestia/react-native-wifi-reborn/issues/25)) ([5b52c97](https://github.com/JuanSeBestia/react-native-wifi-reborn/commit/5b52c97461753cb2fb7574964a1415ddaa23ba29))

## [2.2.4](https://github.com/JuanSeBestia/react-native-wifi-reborn/compare/v2.2.3...v2.2.4) (2019-12-18)


### Performance Improvements

* **test:** test perf semantic-release ([0d42570](https://github.com/JuanSeBestia/react-native-wifi-reborn/commit/0d425709f01b84a6882d27e2698d8e92783efb43))

## [2.2.3](https://github.com/JuanSeBestia/react-native-wifi-reborn/compare/v2.2.2...v2.2.3) (2019-12-12)


### Bug Fixes

* **iOS:** getCurrentWifiSSID when is deneided or  restrited ([1c6d1fd](https://github.com/JuanSeBestia/react-native-wifi-reborn/commit/1c6d1fd0a30840695201e38c6b1db1e6833cf1bf))

## [2.2.2](https://github.com/JuanSeBestia/react-native-wifi-reborn/compare/v2.2.1...v2.2.2) (2019-12-11)


### Bug Fixes

* **Android:** Bad marge ([b6a3cf5](https://github.com/JuanSeBestia/react-native-wifi-reborn/commit/b6a3cf5acdf701857137d76af98317e20d73cb12))

## [2.2.1](https://github.com/JuanSeBestia/react-native-wifi-reborn/compare/v2.2.0...v2.2.1) (2019-12-10)


### Bug Fixes

* **android:** Added network compatibility ([331a40f](https://github.com/JuanSeBestia/react-native-wifi-reborn/commit/331a40f2016773a87f5e4d134d4ff1fed9f62867))

# [2.2.0](https://github.com/JuanSeBestia/react-native-wifi-reborn/compare/v2.1.1...v2.2.0) (2019-11-19)


### Features

* **Android:** Update all library ([f4cc526](https://github.com/JuanSeBestia/react-native-wifi-reborn/commit/f4cc526ba7c7417fe883c58188dea212bb2b5d20))

## [2.1.1](https://github.com/JuanSeBestia/react-native-wifi-reborn/compare/v2.1.0...v2.1.1) (2019-11-15)


### Bug Fixes

* **Android:** Rename package to avoid colisions ([17da67e](https://github.com/JuanSeBestia/react-native-wifi-reborn/commit/17da67e6bbe2675dd307071414a63bf1b24c58b6))

# [2.1.0](https://github.com/JuanSeBestia/react-native-wifi-reborn/compare/v2.0.4...v2.1.0) (2019-11-03)


### Features

* **Android:** Update gradle configuration ([475cc30](https://github.com/JuanSeBestia/react-native-wifi-reborn/commit/475cc3029fdb1f9406e04894ff9eaee64844464d)), closes [#5](https://github.com/JuanSeBestia/react-native-wifi-reborn/issues/5)

## [2.0.4](https://github.com/JuanSeBestia/react-native-wifi-reborn/compare/v2.0.3...v2.0.4) (2019-11-03)


### Bug Fixes

* **ios:** Change settingsURL value so Apple accepts it. Referencing comments from: ([653330e](https://github.com/JuanSeBestia/react-native-wifi-reborn/commit/653330e7676cf21859f7a0a982c22ae85530c807))

## [2.0.3](https://github.com/JuanSeBestia/react-native-wifi-reborn/compare/v2.0.2...v2.0.3) (2019-10-25)


### Bug Fixes

* **IOS:** Live Reload ([aa44375](https://github.com/JuanSeBestia/react-native-wifi-reborn/commit/aa443754a6188d61af797c5406a631b1811a603e))

## [2.0.2](https://github.com/JuanSeBestia/react-native-wifi-reborn/compare/v2.0.1...v2.0.2) (2019-10-24)


### Bug Fixes

* **semantic-release:** Add more extensions ([40f0e01](https://github.com/JuanSeBestia/react-native-wifi-reborn/commit/40f0e012cf69adeabfc665eb1382a49fbdc8fbbf))
