# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/)
and this project adheres to [Semantic Versioning](https://semver.org/).

## [2.4.3] / 2020-11-16

### Changed

- Update .gitignore.

## [2.4.2] / 2020-11-13

### Fixed

- Replace Travis with GitHub Actions.

## [2.4.1] / 2018-09-23

### Fixed

- Invalid npm token on Travis.

## [2.4.0] / 2018-09-23

### Changed

- Replace Bower support with npm package.

## [2.3.0] / 2018-09-23

### Added

- `geoclue-agent.service`.

### Changed

- Start redshift-gtk after geoclue-agent.

## [2.2.1] / 2016-06-08

### Changed

- Set longer restart interval for redshift-gtk and app services.

### Fixed

- Typo in `xbindkeys.service`.

## [2.2.0] / 2016-06-08

### Changed

- Set longer restart interval for redshift-gtk and app services.

### Fixed

- Typo in `xbindkeys.service`.

## [2.2.0] / 2016-06-08

### Changed

- The following services now restart on failure:
  `app@`, `hexchat`, `insync`, `rbenv@`, `transmission-gtk`, and `xbindkeys`.

## [2.1.0] / 2016-06-07

### Changed

- Use `--no-daemon` mode for insync.

## [2.0.0] / 2015-09-29

### Removed

- Dbus units: D-Bus 266 now launches user buses.

## [1.4.1] / 2015-09-09

### Changed

- Set restart on-failure for xscreensaver.

### Fixed

- Issues with ordering cycles.

## [1.4.0] / 2015-08-22

- `xscreensaver.service`.

## [1.3.0] / 2015-06-11

### Changed

- Use system tmuxinator.

## [1.2.0] / 2015-05-23

- Add transmission-gtk.service.

## [1.1.1] / 2015-05-23

### Fixed

- Ensure some units start after xresources.

## [1.1.0] / 2015-05-16

### Added

- Add ssh-agent.service.

## 1.0.0 / 2015-05-10

- Initial release.

[Unreleased]: https://github.com/rxrc/systemd-user-units/compare/v2.4.3...HEAD
[2.4.3]: https://github.com/rxrc/systemd-user-units/compare/v2.4.2...v2.4.3
[2.4.2]: https://github.com/rxrc/systemd-user-units/compare/v2.4.1...v2.4.2
[2.4.1]: https://github.com/rxrc/systemd-user-units/compare/v2.4.0...v2.4.1
[2.4.0]: https://github.com/rxrc/systemd-user-units/compare/v2.3.0...v2.4.0
[2.3.0]: https://github.com/rxrc/systemd-user-units/compare/v2.2.1...v2.3.0
[2.2.1]: https://github.com/rxrc/systemd-user-units/compare/v2.2.0...v2.2.1
[2.2.0]: https://github.com/rxrc/systemd-user-units/compare/v2.1.0...v2.2.0
[2.1.0]: https://github.com/rxrc/systemd-user-units/compare/v2.0.0...v2.1.0
[2.0.0]: https://github.com/rxrc/systemd-user-units/compare/v1.4.1...v2.0.0
[1.4.1]: https://github.com/rxrc/systemd-user-units/compare/v1.4.0...v1.4.1
[1.4.0]: https://github.com/rxrc/systemd-user-units/compare/v1.3.0...v1.4.0
[1.3.0]: https://github.com/rxrc/systemd-user-units/compare/v1.2.0...v1.3.0
[1.2.0]: https://github.com/rxrc/systemd-user-units/compare/v1.1.1...v1.2.0
[1.1.1]: https://github.com/rxrc/systemd-user-units/compare/v1.1.0...v1.1.1
[1.1.0]: https://github.com/rxrc/systemd-user-units/compare/v1.0.0...v1.1.0
