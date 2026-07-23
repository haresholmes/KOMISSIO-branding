# KOMISSIO — Typography

> Purple Era — v2 (2024)

## Typefaces

### Plus Jakarta Sans
Primary typeface for all display text, headings, UI labels, and body copy.
- Source: [Google Fonts](https://fonts.google.com/specimen/Plus+Jakarta+Sans)
- Weights in use: 400 (Regular), 500 (Medium), 600 (SemiBold), 700 (Bold), 800 (ExtraBold)

### JetBrains Mono
Monospace typeface for data, labels, metadata, and system output.
- Source: [Google Fonts](https://fonts.google.com/specimen/JetBrains+Mono)
- Weights in use: 400, 500, 600

## Type Scale

| Role | Size | Weight | Tracking | Line Height | Usage |
|------|------|--------|----------|-------------|-------|
| Display | 72px | 800 | -0.045em | 1.0 | Hero headlines, impact moments |
| H1 | 52px | 700 | -0.03em | 1.05 | Section primary headlines |
| H2 | 38px | 700 | -0.03em | 1.1 | Sub-section heads, card titles |
| H3 | 26px | 600 | -0.02em | 1.2 | Tertiary headings |
| Body | 15px | 400 | 0 | 1.7 | Body copy, descriptions |
| Small | 13px | 400 | 0 | 1.6 | Secondary body, footnotes |
| Mono Label | 10px | 500 | +0.14em | 1.4 | JetBrains Mono — tags, metadata |
| Micro | 8–9px | 500 | +0.08em | 1.3 | JetBrains Mono — chart labels, ticks |

## Principles

- Headings always use negative tracking (`-0.03em` to `-0.045em`) at sizes above 26px.
- Mono labels are always `text-transform: uppercase` and tracking `+0.12em` or above.
- Body text never drops below 14px in the product UI.
- Avoid font weights below 400 in the product UI.
