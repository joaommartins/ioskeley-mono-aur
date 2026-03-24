# Ioskeley Mono AUR Packages

Unofficial AUR packages for [Ioskeley Mono](https://github.com/ahatem/IoskeleyMono), a custom Iosevka build tuned to mimic Berkeley Mono.

## Packages

| Package | Description |
|---------|-------------|
| `ttf-ioskeley-mono-bin` | Normal width |
| `ttf-ioskeley-mono-condensed-bin` | Condensed width |
| `ttf-ioskeley-mono-semicondensed-bin` | SemiCondensed width |
| `ttf-ioskeley-mono-nerd-bin` | Normal width + Nerd Font glyphs |
| `ttf-ioskeley-mono-nerd-condensed-bin` | Condensed width + Nerd Font glyphs |
| `ttf-ioskeley-mono-nerd-semicondensed-bin` | SemiCondensed width + Nerd Font glyphs |

## Building

```bash
cd ttf-ioskeley-mono-bin  # or any variant
makepkg -si
```

## Updates

Version tracking is automated via [Renovate](https://github.com/apps/renovate). When a new upstream release is published, Renovate opens a PR updating the `_tag` field, and a GitHub Actions workflow updates `pkgver` and checksums.

## Licence

The PKGBUILDs and associated files in this repository are licensed under the [MIT Licence](LICENSE). The font itself is licensed under the [SIL Open Font Licence 1.1](https://github.com/ahatem/IoskeleyMono/blob/main/LICENSE).
