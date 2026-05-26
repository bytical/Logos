# Bytical brand pack

Generated from `latest logo bytical.png` by `rebuild_bytical_logo_pack.py`.

## Palette

| Token        | Hex        | Role |
|--------------|------------|------|
| Navy 900     | `#071B34`  | Authority ink on light, primary dark background |
| Cyan         | `#00C7FD`  | The signal dot. Constant across all surfaces. |
| White        | `#FFFFFF`  | Light surface, ink on dark |
| Black        | `#000000`  | Maximum-contrast dark surface (alternate to navy) |

## The rule

| Surface              | Wordmark / `b` ink | Dot       |
|----------------------|--------------------|-----------|
| White                | Navy 900 `#071B34` | Cyan      |
| Navy 900 `#071B34`   | White              | Cyan      |
| Black `#000000`      | White              | Cyan      |
| Tiny (≤32 px)        | Navy 900           | Navy 900  |
| Mono print / B&W     | Single color (navy or black) | same |

## Naming convention

    bytical-{lockup}-{variant}[-{size}].{ext}

  lockup   : wordmark | mark | dot
  variant  : on-light | on-dark | mono-navy
  size     : optional descriptor (48, 512, 1024, 1080, 1200x630, h48-2x, …)

## Folders

  masters/   transparent PNG masters (primary deliverables)
  web/       header / hero sizes (h48, h80 + mark squares 48/96/144/192)
  favicon/   browser + apple-touch + multi-res .ico
  social/    LinkedIn DPs (1024), squares (1080), OG (1200x630)
  svg/       SVG wrappers (embed the PNG; portable for CMS)

Root-level 2048x2048 LinkedIn DPs:

  Bytical LinkedIn DP White.png   light-mode DP (white bg + navy + cyan)
  Bytical LinkedIn DP Navy.png    dark-mode DP (navy bg + white + cyan)
  Bytical LinkedIn DP Black.png   alternate dark DP (black bg + white + cyan)
