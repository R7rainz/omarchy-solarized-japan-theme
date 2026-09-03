# Solarized Japan for Omarchy

An unofficial Omarchy theme combining a dark Japanese-inspired desktop with
the palette of [Solarized Osaka](https://github.com/craftzdog/solarized-osaka.nvim).

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/41de43e2-d5ad-4643-90fd-fbafc0a2b383" />

![Solarized Japan unlock preview](preview-unlock.png)

## Features

- Solarized Osaka palette adapted to Omarchy 4 semantic color roles
- High-contrast terminal selections, suggestions, and readable foregrounds
- Seven original Japanese-inspired wallpapers, including a wordmark wallpaper
- `Yaru-sage` file-manager icons
- Japanese Plymouth unlock mark displaying `オマーチー`
- Blurred shrine-and-bamboo unlock preview with warm antique-gold lighting
- Generated terminal, shell, editor, browser, and system-tool themes through
  Omarchy's `colors.toml` templates

## Installation

From the Omarchy menu, open **Install > Style > Theme** and paste:

```text
https://github.com/R7rainz/omarchy-solarized-japan.git
```

Or install from a terminal:

```bash
omarchy theme install https://github.com/R7rainz/omarchy-solarized-japan.git
```

Apply the theme manually with:

```bash
omarchy theme set solarized-japan
```

## Wallpaper and unlock controls

Cycle wallpapers with:

```bash
omarchy theme bg next
```

The unlock artwork appears under **Style > Unlock**. `unlock.png` is the
transparent Plymouth mark; `preview-unlock.png` is the selector preview.

## Palette

![Solarized Japan color palette](palette.svg)

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
| Antique gold | `#c4a15a` |
| Orange | `#c94c16` |
| Red | `#db302d` |
| Magenta | `#d23681` |

The palette starts from Solarized Osaka. Foreground, selection, and
antique-gold roles are tuned for Omarchy readability.

## Theme layout

```text
solarized-japan/
├── backgrounds/                 # selectable wallpapers
│   ├── background1.jpg ... background6.jpg
│   └── background7.png          # wordmark wallpaper
├── colors.toml                  # palette source of truth
├── icons.theme                  # Yaru-sage
├── preview.png                  # theme-selector preview
├── unlock.png                   # transparent Plymouth mark
├── preview-unlock.png           # unlock-selector preview
├── palette.svg                  # documented palette preview
├── theme.yaml                   # repository/gallery metadata
├── LICENSE
├── NOTICE
└── README.md
```

`theme.yaml` is repository metadata for gallery/submission tooling; Omarchy's
runtime theme source remains `colors.toml`.

## Credits and licensing

- [Takuya Matsuyama / craftzdog (Devaslife)](https://github.com/craftzdog)
  for [Solarized Osaka](https://github.com/craftzdog/solarized-osaka.nvim)
- [Ethan Schoonover](https://ethanschoonover.com/solarized/) for the original
  Solarized color scheme
- [Omarchy](https://omarchy.org/) for the desktop environment and theming
  tooling

Theme configuration, documentation, palette artwork, and project-created
wallpaper/unlock artwork are provided under the [Apache License 2.0](LICENSE),
subject to the third-party attribution and trademark notes in [NOTICE](NOTICE).

This project is independent and is not officially affiliated with Omarchy,
Solarized Osaka, Devaslife, or Ethan Schoonover.

## Contributing

Issues and pull requests are welcome. Please include the wallpaper/artwork
source or permission details when contributing new visual assets.
