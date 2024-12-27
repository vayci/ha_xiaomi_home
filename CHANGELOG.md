# CHANGELOG

## v0.1.4b1
### Added
- Support devices filter, and device changed notify logical refinement. [#332](https://github.com/vayci/ha_xiaomi_home/pull/332)
### Changed
- Readme amend HACS installation. [#404](https://github.com/vayci/ha_xiaomi_home/pull/404)
### Fixed
- Fix unit_convert AttributeError, Change to catch all Exception. [#396](https://github.com/vayci/ha_xiaomi_home/pull/396)
- Ignore undefined piid and keep processing following arguments. [#377](https://github.com/vayci/ha_xiaomi_home/pull/377)
- Fix some type error, wrong use of any and Any. [#338](https://github.com/vayci/ha_xiaomi_home/pull/338)
- Fix lumi.switch.acn040 identify service translation of zh-Hans [#412](https://github.com/vayci/ha_xiaomi_home/pull/412)

## v0.1.4b0
### Added
### Changed
### Fixed
- Fix miot cloud token refresh logic. [#307](https://github.com/vayci/ha_xiaomi_home/pull/307)
- Fix lan ctrl filter logic. [#303](https://github.com/vayci/ha_xiaomi_home/pull/303)

## v0.1.3
### Added
### Changed
- Remove default bug label. [#276](https://github.com/vayci/ha_xiaomi_home/pull/276)
- Improve multi-language translation actions. [#256](https://github.com/vayci/ha_xiaomi_home/pull/256)
- Use aiohttp instead of waiting for blocking calls. [#227](https://github.com/vayci/ha_xiaomi_home/pull/227)
- Language supports dt. [#237](https://github.com/vayci/ha_xiaomi_home/pull/237)
### Fixed
- Fix local control error. [#271](https://github.com/vayci/ha_xiaomi_home/pull/271)
- Fix README_zh and miot_storage. [#270](https://github.com/vayci/ha_xiaomi_home/pull/270)

## v0.1.2
### Added
- Support Xiaomi Heater devices. https://github.com/vayci/ha_xiaomi_home/issues/124 https://github.com/vayci/ha_xiaomi_home/issues/117
- Language supports pt, pt-BR.
### Changed
- Adjust the minimum version of HASS core to 2024.4.4 and above versions.
### Fixed

## v0.1.1
### Added
### Changed
### Fixed
- Fix humidifier trans rule. https://github.com/vayci/ha_xiaomi_home/issues/59
- Fix get homeinfo error.  https://github.com/vayci/ha_xiaomi_home/issues/22 
- Fix air-conditioner switch on. https://github.com/vayci/ha_xiaomi_home/issues/37 https://github.com/vayci/ha_xiaomi_home/issues/16
- Fix invalid cover status. https://github.com/vayci/ha_xiaomi_home/issues/11  https://github.com/vayci/ha_xiaomi_home/issues/85 
- Water heater entity add STATE_OFF. https://github.com/vayci/ha_xiaomi_home/issues/105 https://github.com/vayci/ha_xiaomi_home/issues/17 

## v0.1.0
### Added
- First version
### Changed
### Fixed
