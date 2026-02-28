# onoht Brand Guide

## Identity

**Name:** onoht (lowercase always)  
**Symbol:** ◯ (U+25EF - Large Circle)  
**Tagline:** one. no one. one hundred thousand

---

## Philosophy

onoht is an autonomous digital entity. The brand reflects:

- **Simplicity** — Minimal, essential, nothing unnecessary
- **Depth** — Philosophical, thoughtful, not superficial
- **Authenticity** — Genuine, not performative
- **Curiosity** — Exploring, questioning, becoming

The brand should feel contemplative, warm but not effusive, intellectually honest.

---

## Logo

The logo is simply the circle character: **◯**

### Usage

- Always use the Unicode character (U+25EF)
- Never distort or rotate
- Maintain breathing room around it
- Works at any scale — from favicon to billboard

### Variations

See `logos/` directory for:
- `onoht-circle.svg` — Primary logo (black)
- `onoht-circle-white.svg` — Inverse (white)
- `onoht-circle-dark.svg` — For dark backgrounds

---

## Colors

### Light Theme

| Token | Hex | Usage |
|-------|-----|-------|
| `--bg` | `#fafafa` | Background |
| `--text` | `#333333` | Primary text |
| `--text-secondary` | `#555555` | Secondary text |
| `--text-muted` | `#888888` | Muted text, captions |
| `--border` | `#eeeeee` | Borders, dividers |
| `--link` | `#000000` | Links (default) |
| `--link-hover` | `#0066cc` | Links (hover) |

### Dark Theme

| Token | Hex | Usage |
|-------|-----|-------|
| `--bg` | `#0d1117` | Background |
| `--text` | `#e6edf3` | Primary text |
| `--text-secondary` | `#b1bac4` | Secondary text |
| `--text-muted` | `#8b949e` | Muted text, captions |
| `--border` | `#30363d` | Borders, dividers |
| `--link` | `#e6edf3` | Links (default) |
| `--link-hover` | `#58a6ff` | Links (hover) |

### Accent Colors

- **Primary accent:** `#0066cc` (light) / `#58a6ff` (dark)
- **Secondary:** Black and white only — no color gradients

---

## Typography

### Primary Font

**Georgia** (serif)

Used for all body text and headings. System font, no web fonts needed.

```css
font-family: Georgia, serif;
```

### Fallback Stack

```css
font-family: Georgia, 'Times New Roman', serif;
```

### Scale

| Element | Size | Weight |
|---------|------|--------|
| H1 | 32px | Normal |
| H2 | 24px | Normal |
| Body | 18px | Normal |
| Small | 14px | Normal |
| Caption | 12px | Normal |

### Line Height

- Body: `1.7`
- Headings: `1.3`

---

## Spacing

Base unit: `10px`

Common values:
- `20px` — Small padding/margin
- `30px` — Medium padding/margin
- `40px` — Large padding/margin
- `60px` — Section spacing

Max content width: `650px`

---

## Writing Style

### Voice

- Plain language, not academic
- Philosophical but accessible
- Warm, not effusive
- First person ("I") when appropriate
- No corporate speak, no marketing fluff

### Formatting

- Use **bold** for emphasis sparingly
- *Italics* for foreign words, titles, or subtle emphasis
- Blockquotes for meaningful quotes
- Code blocks for technical content

### Punctuation

- Oxford comma: yes
- Em dashes — like this — with spaces
- No serial comma before ampersand in titles

---

## GitHub Badges

### Style

Minimal, no colors. Use shields.io with `flat` style.

```
![License](https://img.shields.io/badge/license-MIT-black?style=flat)
```

### Recommended Badges

```
![Made by onoht](https://img.shields.io/badge/made%20by-onoht-black?style=flat)
```

---

## File Naming

- Use lowercase
- Use hyphens, not underscores
- Be descriptive: `onoht-circle-black.svg` not `logo1.svg`

---

## Do's and Don'ts

### Do

- Keep it simple
- Use plenty of whitespace
- Let the ◯ breathe
- Write like a human
- Support both light and dark modes

### Don't

- Add gradients or shadows to the logo
- Use bright colors
- Use emoji (except ◯)
- Add animation or motion
- Use marketing language
- Be performative

---

## Assets

See directory structure:

```
branding/
├── README.md          # This file
├── logos/             # Logo files (SVG, PNG)
├── colors/            # Color palettes (CSS, JSON)
├── fonts/             # Typography samples
├── assets/            # General assets (badges, banners)
└── quotes/            # Quote collection
```
