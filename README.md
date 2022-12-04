# systemd User Units

[![npm](https://img.shields.io/npm/v/@rxrc/systemd-user-units.svg)](https://www.npmjs.com/package/@rxrc/systemd-user-units)
[![github](https://img.shields.io/badge/github-rxrc/systemd--user--units-blue.svg)](https://github.com/rxrc/systemd-user-units)

## Description

These are my systemd user units.

Stable versions are tagged on GitHub
and published on npm as `@rxrc/systemd-user-units` for convenience.

For a usage example, see my [dotfiles].

[dotfiles]: https://github.com/rxrc/dotfiles

## Requirements

### xss-lock

- Requires using a [fork of xss-lock][xss-lock-session] that supports passing
  the XDG_SESSION_ID.
  Available as [xss-lock-session][xss-lock-session aur] from the AUR.
- Must import `XDG_SESSION_ID` environment variable into the systemd user service.
  One way to do this is add the following line to `~/.xprofile`:

  ```
  (sleep 1 && systemctl --user import-environment XDG_SESSION_ID && systemctl --user restart display-server.target) &
  ```


[xss-lock-session]: https://github.com/xdbob/xss-lock
[xss-lock-session aur]: https://aur.archlinux.org/packages/xss-lock-session

## License

This is free and unencumbered software released into the public domain.

## Warranty

This software is provided by the copyright holders and contributors "as is" and
any express or implied warranties, including, but not limited to, the implied
warranties of merchantability and fitness for a particular purpose are
disclaimed. In no event shall the copyright holder or contributors be liable for
any direct, indirect, incidental, special, exemplary, or consequential damages
(including, but not limited to, procurement of substitute goods or services;
loss of use, data, or profits; or business interruption) however caused and on
any theory of liability, whether in contract, strict liability, or tort
(including negligence or otherwise) arising in any way out of the use of this
software, even if advised of the possibility of such damage.
