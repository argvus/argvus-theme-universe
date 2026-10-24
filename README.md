# Universe theme for ARGVUS

Official ARGVUS Dark theme, `universe`, with its Sticky and Float variants.

[![CI](https://github.com/argvus/argvus-theme-universe/actions/workflows/ci.yml/badge.svg)](https://github.com/argvus/argvus-theme-universe/actions/workflows/ci.yml)
[![Release](https://github.com/argvus/argvus-theme-universe/actions/workflows/release.yml/badge.svg)](https://github.com/argvus/argvus-theme-universe/actions/workflows/release.yml)
[![License](https://img.shields.io/badge/License-GPL--3.0-blue.svg)](LICENSE)
[![Language: Shell](https://img.shields.io/badge/Shell-POSIX-4EAA25?logo=gnubash&logoColor=white)](https://www.gnu.org/software/bash/)
[![Platform: Arch Linux | Wayland](https://img.shields.io/badge/platform-Arch%20Linux%20%7C%20Wayland-1793D1?logo=archlinux&logoColor=white)](https://archlinux.org/)
[![Pull requests](https://img.shields.io/github/issues-pr/argvus/argvus-theme-universe)](https://github.com/argvus/argvus-theme-universe/pulls)
[![Issues](https://img.shields.io/github/issues/argvus/argvus-theme-universe)](https://github.com/argvus/argvus-theme-universe/issues)
[![Last commit](https://img.shields.io/github/last-commit/argvus/argvus-theme-universe)](https://github.com/argvus/argvus-theme-universe/commits/main)

## Theme identity

| Field | Value |
| --- | --- |
| Theme ID | `universe` (Float variant: `universe-float`) |
| Display name | Universe |
| Mode | `dark` |
| Default highlight | `#eeeeee` |
| GTK color scheme | `prefer-dark` |
| Calendar stylesheet | `universe` |
| Package | `argvus-theme-universe` |
| Wallpaper | `/usr/share/backgrounds/argvus/abstract/dark/universe-abstract-dark.jxl` |

The values above are the ones declared in
`src/usr/share/argvus/appearance/themes.d/universe/theme.toml`, the manifest that the
desktop reads. The manifest is the source of truth; this page describes it.

## Installing

The package depends on `argvus` and `argvus-appearance`, so pacman installs them with it.

```sh
sudo pacman -S argvus-theme-universe
```

Select the theme in the Control Center (Appearance > Themes), or run
`argvus theme-switch universe`.

## Files

The package installs the theme's per-component files under `/usr/share/argvus` (and the
calendar stylesheet under `/etc/argvus/taskbar/calendar/themes`). Each component that
the theme styles has its own directory, listed by `find src -type f` in this repository.

## Development

Validate with `make validate` before building. The design rules are in
[DEVELOPMENT.md](DEVELOPMENT.md); the ARGVUS documentation for themes is in
`argvus/docs/en/user-guide/appearance.md` of the `argvus` repository.

## Contributing and policies

- [CONTRIBUTING.md](https://github.com/argvus/.github/blob/main/CONTRIBUTING.md) — contribution workflow
- [SECURITY.md](https://github.com/argvus/.github/blob/main/SECURITY.md) — private vulnerability reports
- [Code of Conduct](https://github.com/argvus/.github/blob/main/policies/CODE_OF_CONDUCT.md) — community standards
- [AI usage policy](https://github.com/argvus/.github/blob/main/policies/IA_USAGE.md) — rules for AI-assisted contributions

## License

GPL-3.0-only. See [LICENSE](LICENSE).
