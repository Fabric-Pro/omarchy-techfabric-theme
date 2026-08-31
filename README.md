# Tech Fabric — Omarchy Theme

Dark theme built on the Tech Fabric brand red (soft brick `#D14B44` accent, darker `#C00500` borders).

## Install

```bash
omarchy theme install https://github.com/Fabric-Pro/omarchy-techfabric-theme.git
omarchy theme set techfabric
```

## Contents

- `colors.toml` — full palette (dark mode, red accent)
- `backgrounds/techfabric-data-weave.png` — 4K background with the brand logo
- `icons.theme` — Yaru-red file manager icons
- `branding/screensaver.txt` — Tech Fabric lockup as braille ASCII art for the
  Omarchy screensaver
- `variants/` — alternate 4K backgrounds (clean, bold) and a dotted-mark
  artwork. Copy backgrounds into `~/.config/omarchy/backgrounds/techfabric/`
  to add them to the rotation (`omarchy theme bg next`).

## Screensaver

```bash
cp ~/.config/omarchy/themes/techfabric/branding/screensaver.txt ~/.config/omarchy/branding/screensaver.txt
omarchy-launch-screensaver force   # preview (any key exits)
```

Restore the default Omarchy logo anytime with `omarchy branding screensaver reset`.
