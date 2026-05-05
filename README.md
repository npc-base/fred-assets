# fred-assets

Static image assets served as a CDN for the FredHub app. Hosted on
GitHub via raw.githubusercontent.com.

## Layout

```
<device>/<color>.jpg
```

URL pattern: `https://raw.githubusercontent.com/npc-base/fred-assets/main/<device>/<color>.png`

## Devices

- `lineamini/` — La Marzocco Linea Mini (`black`, `blue`, `red`, `yellow`). Transparent PNG, designed to composite onto the tile background.

## Adding a color

1. Drop the PNG/JPG into `<device>/<color>.<ext>`
2. Commit + push
3. Add a matching entry in `BrandedDevice.colorVariants` in the app
