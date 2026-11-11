# Branding

Earth-tone color system for `tin+topo`. Use these values for the organization profile, maps, and project UI. Repository-specific brands may override this file.

Tokens live in [`branding.css`](branding.css). Link that file, or copy the custom properties into a project stylesheet.

## Favorites

These four colors are the brand. The rest of the palette is mixed from them.

| Color | Hex | Use |
| --- | --- | --- |
| Ink | `#241F1A` | Wordmark, headings, and body text |
| Stone | `#8A8178` | Borders, rules, and large muted labels |
| Clay | `#A15C38` | The accent: one mark, one chart series, or one call to action |
| Ochre | `#C6A15A` | Highlights and small fills. Put Ink on Ochre |

## Mixed from the favorites

| Color | Hex | Mix | Use |
| --- | --- | --- | --- |
| Ash | `#524B44` | Ink + Stone | Secondary text on Paper |
| Kiln | `#69412A` | Ink + Clay | Filled buttons, with Paper text |
| Field | `#856D40` | Ink + Ochre | Small ochre marks that need more weight |
| Parchment | `#E2DCD4` | Stone + Ochre, lightened | Cards and panels |
| Paper | `#F3F0EA` | Stone + Ochre, mostly white | Page background |

## Maps

| Color | Hex | Use |
| --- | --- | --- |
| Thicket | `#6A6554` | Vegetation |
| Creek | `#5E6B6E` | Water |
| Loam | `#966F58` | Soil and built ground |

On maps, use Clay when one feature has to stand out.

## Pairing

| Pair | Use |
| --- | --- |
| Ink on Paper | Body text. About 15:1 |
| Ash on Paper | Secondary text. About 7.5:1 |
| Paper on Kiln | Filled buttons. About 7.7:1 |
| Ink on Ochre | Highlight fills |
| Stone on Paper | Borders and large labels only. About 3.4:1, too light for small text |

Paper on Clay is about 4.5:1. Use it for large labels, and keep body text in Ink or Ash.

## CSS

`docs/branding.css` defines one custom property per color, plus role tokens such as `--tt-text`, `--tt-bg`, and `--tt-accent`. Class names start with `tt-` so they can sit beside an existing stylesheet without restyling `body`.

```html
<link rel="stylesheet" href="docs/branding.css">
```

```css
.panel {
  background: var(--tt-surface);
  color: var(--tt-text);
  border: 1px solid var(--tt-border);
}
```
