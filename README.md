# Solarized Japan for Omarchy

An unofficial [Omarchy](https://omarchy.org/) theme that combines a Japanese-inspired wallpaper set with the dark palette from [Solarized Osaka](https://github.com/craftzdog/solarized-osaka.nvim).

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/36e79a38-82b9-4a01-9334-ba6f1891ad3f" />

## Features

- Solarized Osaka core palette adapted to Omarchy's semantic color roles
- Contrast-adjusted foreground and selection colors for readable terminal and shell UI
- Two bundled backgrounds, including an Omarchy wordmark wallpaper
- `Yaru-dark` file-manager icons
- Matching transparent Plymouth unlock logo and unlock preview

## Installation

From the Omarchy menu, open **Install > Style > Theme** and paste:

```text
https://github.com/R7rainz/omarchy-solarized-japan.git
```

Or install from a terminal:

```bash
omarchy theme install https://github.com/R7rainz/omarchy-solarized-japan.git
```

Omarchy strips the `omarchy-` repository prefix, installs the theme as `solarized-japan`, and applies it automatically.

## Usage

Apply the theme:

```bash
omarchy theme set solarized-japan
```

Choose a wallpaper:

```bash
omarchy theme bg-switcher
```

The matching unlock design appears under **Style > Unlock**.

Update or remove the installed theme:

```bash
omarchy theme update
omarchy theme remove solarized-japan
```

## Palette

| Role | Color |
| --- | --- |
| Background | `#001419` |
| Raised surface | `#002c38` |
| Foreground | `#adb7b7` |
| Bright foreground | `#fdf5e2` |
| Muted | `#637981` |
| Cyan / accent | `#29a298` |
| Blue | `#268bd3` |
| Green | `#849900` |
| Yellow | `#b28500` |
| Orange | `#c94c16` |
| Red | `#db302d` |
| Magenta | `#d23681` |

The core hues and extended bright accents are exact values emitted by Solarized Osaka. The foreground and selection role choices are an Omarchy-specific readability adaptation.

## Theme files

- `colors.toml` — Omarchy palette and generated-app color source
- `icons.theme` — icon theme selection (`Yaru-dark`)
- `backgrounds/` — selectable wallpapers
- `preview.png` — theme selector preview
- `unlock.png` — transparent Plymouth wordmark
- `preview-unlock.png` — unlock selector preview

## Credits

- [Takuya Matsuyama (craftzdog / Devaslife)](https://github.com/craftzdog) for [Solarized Osaka](https://github.com/craftzdog/solarized-osaka.nvim), the palette this theme adapts
- [Ethan Schoonover](https://ethanschoonover.com/solarized/) for the original Solarized color scheme
- [Omarchy](https://omarchy.org/) for the desktop environment and stock wordmark mask used by the unlock artwork

This project is independent and is not officially affiliated with Solarized Osaka, Devaslife, or Omarchy.

## License

Theme configuration and original project material are available under the [Apache License 2.0](LICENSE). Third-party wallpaper artwork is excluded from that grant; see [NOTICE](NOTICE) before redistributing the repository.

Issues and pull requests are welcome.
