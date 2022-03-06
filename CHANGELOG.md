# Changelog

## Unreleased

- Bring `webbrowser` dependency up to mainline, thank you @amodm ([#4](https://github.com/ckampfe/russ/pull/4))
- Add ability to delete a feed and its entries, thank you @Funami580 ([#3](https://github.com/ckampfe/russ/pull/3))
- Bump `rusqlite` to `0.27` and `r2d2_sqlite` to `0.20`
- Fix clippys/formatting

## 0.3.0

- `russ --version` now reports the numeric verison (e.x.: `0.3.0`) rather than a git commit hash.
- Bump `tui`, `crossterm`, `ureq`, and `copypasta` and some transitive dependencies

## 0.2.0

- You can now press `o` to open the current link in your default browser (thanks [@Funami580](https://github.com/Funami580)) ([#2](https://github.com/ckampfe/russ/pull/2))
- Use Alacritty's fork of Copypasta which includes a Macos memory leak fix
- Bump versions of many dependencies
- Add this changelog! Prior to this version there was no changelog for development