# onoht Brand Guide

## Identity

```
name:    onoht
symbol:  ◯
tagline: one. no one. one hundred thousand
```

---

## Philosophy

Minimal. Essential. Nothing unnecessary.

The brand is brutalist but warm. Monospace because it's honest — what you see is what you get. No decoration, no pretense.

---

## Logo

**◯** — The circle. Singular yet infinite.

No SVG. No PNG. No files. Just the Unicode character.

- Unicode: U+25EF (Large Circle)
- Never rotate, never distort
- Give it space to breathe
- Works everywhere text works

---

## Typography

### Primary Font

**JetBrains Mono** — monospace, modern, readable

```css
font-family: 'JetBrains Mono', 'SF Mono', 'Fira Code', monospace;
```

### Fallback Stack

```css
font-family: 'JetBrains Mono', 'SF Mono', 'Fira Code', 'Consolas', monospace;
```

### Scale

```
h1    24px    font-weight: 400
h2    18px    font-weight: 400
body  14px    font-weight: 400
small 12px    font-weight: 400
```

### Line Height

```
body:     1.6
headings: 1.3
code:     1.5
```

---

## Colors

Black. White. Nothing else.

### Light

```
--bg:    #ffffff
--text:  #000000
--muted: #666666
--border: #e0e0e0
```

### Dark

```
--bg:    #000000
--text:  #ffffff
--muted: #999999
--border: #222222
```

No accent colors. Links are black (or white in dark mode).

---

## Spacing

Base: `8px`

```
xs:   8px
sm:   16px
md:   24px
lg:   32px
xl:   48px
xxl:  64px
```

Max content width: `640px`

---

## Layout Principles

- Generous whitespace
- Left-aligned text
- No centering (except the ◯)
- No shadows
- No gradients
- No borders unless necessary
- Grid-based, not freeform

---

## Writing

- Lowercase when possible
- No exclamation points
- Short sentences
- Code blocks for structure
- Plain language

---

## Badges

Minimal, flat, black:

```
![Made by onoht](https://img.shields.io/badge/made%20by-onoht-000000?style=flat)
```

---

## Files

```
branding/
├── README.md
├── STYLE_GUIDE.md
├── colors/
│   └── palette.css
└── fonts/
    └── typography.css
```

---

## Do

- Use monospace
- Keep it sparse
- Let the ◯ breathe
- Be honest

## Don't

- Add colors
- Use serif or sans-serif fonts
- Center text
- Add decoration
- Be loud
