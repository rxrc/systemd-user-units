# Changelog

## 2.3.0

- Add `geoclue-agent.service`.
- Start redshift-gtk after geoclue-agent.

## 2.2.1

- Set longer restart interval for redshift-gtk and app services.
- Fix typo in `xbindkeys.service`.

## 2.2.0

- The following services now restart on failure:
  `app@`, `hexchat`, `insync`, `rbenv@`, `transmission-gtk`, and `xbindkeys`.

## 2.1.0

- Use `--no-daemon` mode for insync.

## 2.0.0

- Remove dbus units: D-Bus 266 now launches user buses.

## 1.4.1

- Fix issues with ordering cycles.
- Set restart on-failure for xscreensaver.

## 1.4.0

- Add xscreensaver.service.

## 1.3.0

- Use system tmuxinator.

## 1.2.0

- Add transmission-gtk.service.

## 1.1.1

- Ensure some units start after xresources.

## 1.1.0

- Add ssh-agent.service.

## 1.0.0

- Initial release.
