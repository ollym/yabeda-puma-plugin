# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](http://semver.org/spec/v2.0.0.html).

## 0.5.0 - 2020-11-13

### Changed

- Start Yabeda exporter on `on_booted` hook to support Puma 4.x daemon mode. [@Envek], [#14](https://github.com/yabeda-rb/yabeda-puma-plugin/pull/14)

## 0.4.0 - 2020-04-29

### Added

- `yabeda_prometheus` plugin to allow metrics export on separate port. [@jwhitcraft], [#11](https://github.com/yabeda-rb/yabeda-puma-plugin/pull/11)

## 0.3.0 - 2020-01-27

### Added

- Support for yabeda 0.2 (required by prometheus-client 1.0). [@Envek]

## 0.2.1 - 2019-12-16

### Fixed

- Fix undefined method in TCP socket. [@Neznauy], [#7](https://github.com/yabeda-rb/yabeda-puma-plugin/pull/7)

## 0.2.0 - 2019-12-12

### Added

- Support for TCP puma control panel url. [@dsalahutdinov]

## 0.1.0 - 2019-04-02

Initial release with basic metrics collection. [@dsalahutdinov]

[@jwhitcraft]: https://github.com/jwhitcraft "Jon Whitcraft"
[@Neznauy]: https://github.com/Neznauy "Aleksandr Shlyakov"
[@Envek]: https://github.com/Envek "Andrey Novikov"
[@dsalahutdinov]: https://github.com/dsalahutdinov "Dmitry Salahutdinov"