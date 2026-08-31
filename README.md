# Tech Fabric — Omarchy Theme

Dark theme built on the Tech Fabric brand red (`#C00500`).

## Install

```bash
omarchy theme install https://github.com/Fabric-Pro/omarchy-techfabric-theme.git
omarchy theme set techfabric
```

## Contents

- `colors.toml` — full palette (dark mode, red accent)
- `backgrounds/techfabric-data-weave.png` — 4K background with the brand logo
- `icons.theme` — Yaru-red file manager icons
- `variants/` — alternate 4K backgrounds (clean, bold). Copy any into
  `~/.config/omarchy/backgrounds/techfabric/` to add it to the rotation
  (`omarchy theme bg next`).

## Optional: VS Code button contrast fix

Omarchy's stock VS Code template renders button/badge text in the background
color, which is unreadable on this theme's dark red buttons
(black on `#C00500`). A patched template that uses bright text instead is
included — install it once per machine:

```bash
mkdir -p ~/.config/omarchy/themed
cp ~/.config/omarchy/themes/techfabric/themed/vscode-theme.json.tpl ~/.config/omarchy/themed/
omarchy theme set techfabric   # regenerate with the override
```
