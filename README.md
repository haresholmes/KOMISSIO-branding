# KOMISSIO Branding

Official brand assets, pitch deck, and design guidelines for **KOMISSIO** — the operating system for UAE commission-driven businesses.

---

## What's in this repository

```
KOMISSIO-branding/
├── logo/                    # All logo files (SVG)
├── branding/                # Brand assets (SVG + HTML)
├── deck/                    # Investor pitch deck (print to PDF)
└── guidelines/              # Brand voice and logo usage guides
```

---

## Logo Files

All logo files are in `/logo/` as SVG (fully scalable — use at any size).

| File | Description | Use For |
|---|---|---|
| `komissio-logo-primary.svg` | Mark + wordmark, teal on light | Website, docs, light backgrounds |
| `komissio-logo-reversed.svg` | Mark + wordmark, all white | Dark slides, dark UI, print on dark paper |
| `komissio-logo-teal.svg` | Mark + wordmark on teal rect | Social headers, presentations |
| `komissio-mark-primary.svg` | Icon mark only, teal + gold | Favicon, app icon, social profile |
| `komissio-mark-white.svg` | Icon mark only, all white | Dark backgrounds |
| `komissio-mark-dark.svg` | Icon mark only, dark ink | Single-colour print, embossing |
| `komissio-wordmark-dark.svg` | Text only, dark ink | Horizontal layouts, footers |
| `komissio-wordmark-white.svg` | Text only, white | Dark footers, reversed layouts |

### Exporting PNG from SVG

SVG is the master format. To get PNG:
1. Open the SVG in **Figma** (drag-and-drop), **Adobe Illustrator**, or **Inkscape**
2. Set the export size (recommend 2× or 3× your display target)
3. Export → PNG, transparent background

For the mark at common sizes:
- 32×32px — favicon
- 64×64px — app icon (1×)
- 128×128px — app icon (2×)
- 512×512px — App Store / Play Store

---

## Branding Assets

All assets in `/branding/` as SVG (or HTML for multi-page documents).

| File | Description | Size |
|---|---|---|
| `color-palette.svg` | Full brand colour palette with hex + RGB | 900×560 |
| `typography-specimen.svg` | Type scale, specimens, font install guide | 900×600 |
| `business-card-front.svg` | Business card front | 1050×600 (3.5"×2" @300dpi) |
| `business-card-back.svg` | Business card back (dark with mark) | 1050×600 |
| `social-banner-linkedin.svg` | LinkedIn company banner | 1584×396 |
| `letterhead.svg` | A4 letterhead template | 794×1123 (A4 @96dpi) |
| `brand-guidelines.html` | Full brand guide (print to PDF) | A4, 6 sections |

### Printing the Brand Guidelines

1. Open `branding/brand-guidelines.html` in Chrome or Safari
2. File → Print (or Cmd+P)
3. Set: **Destination → Save as PDF**, **Paper size → A4**, **Margins → None**
4. Save — you get a clean multi-page PDF

---

## Pitch Deck

The full 20-slide investor pitch deck is in `/deck/komissio-pitch-deck.html`.

### Exporting to PDF

1. Open `deck/komissio-pitch-deck.html` in **Chrome** (Chrome gives best print output)
2. Click the **Export PDF** button in the top-right, OR press **Cmd+P** / **Ctrl+P**
3. Set:
   - **Destination → Save as PDF**
   - **Paper size → Custom**: 1280 × 720 pixels (or use Landscape → Letter for a close approximation)
   - **Margins → None**
   - **Background graphics → ON** (critical — enables all colours)
4. Save

The deck uses `@page { size: 1280px 720px; }` print CSS so each slide is one 16:9 page.

### Slide List

| # | Slide | Style |
|---|---|---|
| 1 | Cover | Dark |
| 2 | Dubai Context | Light |
| 3 | The Problem | Light |
| 4 | What KOMISSIO Is | Light |
| 5 | OS Diagram | Dark |
| 6 | Sales Flow | Light |
| 7 | Legal / Property | Light |
| 8 | Accounting | Light |
| 9 | Owner Dashboard | Dark |
| 10 | Architecture | Light |
| 11 | Compliance | Light |
| 12 | Roadmap | Light |
| 13 | Platform Expansion | Light |
| 14 | Philosophy | Dark |
| 15 | Team | Light |
| 16 | Partners / Round | Light |
| 17 | Impact Vision | Dark |
| 18 | Traction | Light |
| 19 | Appendix | Light |
| 20 | Closing | Dark |

---

## Brand Guidelines

Full brand guidelines are in `branding/brand-guidelines.html` (print to PDF, 6 sections).

Markdown references:
- `guidelines/logo-usage.md` — Logo do's and don'ts, clear space, minimum sizes, file format guide
- `guidelines/brand-voice.md` — Voice attributes, tone by context, headline patterns, language principles

---

## Brand Colours

| Name | Hex | RGB | Use |
|---|---|---|---|
| Deep Teal | `#0D5C63` | 13, 92, 99 | Primary brand, CTAs, icons |
| Commission Gold | `#C9A84C` | 201, 168, 76 | Accents, highlights, financial data |
| Dark Ink | `#0E1117` | 14, 17, 23 | Dark slides, dark UI |
| Off-White | `#F5F3EF` | 245, 243, 239 | Body slide backgrounds |
| Cream | `#FDFCF9` | 253, 252, 249 | Cards, light sections |
| Muted | `#6B6B72` | 107, 107, 114 | Body text, labels |

---

## Typography

**Primary typeface: DM Sans** (Google Fonts — free)
- Use for all headings, body copy, UI labels, buttons
- Weights: 300 Light, 400 Regular, 500 Medium, 600 SemiBold, 700 Bold

**Monospace: DM Mono** (Google Fonts — free)
- Use for tags, codes, data labels, technical metadata
- Weights: 400 Regular, 500 Medium

[Install DM Sans →](https://fonts.google.com/specimen/DM+Sans)
[Install DM Mono →](https://fonts.google.com/specimen/DM+Mono)

---

## Contact

For brand usage questions: **founders@komissio.ae**

---

*KOMISSIO — Built in Dubai.*
