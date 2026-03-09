# Soma — Media Kit

Brand assets for Soma (σῶμα), an AI coding agent with self-growing memory.

## Logo

The Soma mascot is a blue planet with a small moon companion. They look at each other — a body and its child. The planet smiles.

**Design:** No baked-in background. Works on any surface, light or dark.

## Files

### SVG (source of truth)

| File | Use |
|------|-----|
| `svg/soma-logo.svg` | Full mascot — planet, moon, arms, legs, ground shadow |
| `svg/soma-logo-animated.svg` | Animated version — float, blink, arm nudge. For website hero. Includes `prefers-reduced-motion` fallback. |
| `svg/soma-icon.svg` | Head only — planet + moon, no limbs. For favicon, app icon, small contexts. |

### PNG

| File | Sizes |
|------|-------|
| `png/soma-logo-{size}.png` | 1024, 512, 256, 128, 64, 32 |
| `png/soma-icon-{size}.png` | 512, 256, 128, 64, 32, 16 |

### Favicon

Ready to drop into any website. Copy the `favicon/` directory into your public root.

| File | Purpose |
|------|---------|
| `favicon/favicon.svg` | Modern browsers (scalable) |
| `favicon/favicon.ico` | Legacy browsers (16+32) |
| `favicon/favicon-16x16.png` | 16px fallback |
| `favicon/favicon-32x32.png` | 32px fallback |
| `favicon/apple-touch-icon.png` | iOS home screen (180x180) |
| `favicon/android-chrome-192x192.png` | Android PWA |
| `favicon/android-chrome-512x512.png` | Android PWA splash |
| `favicon/site.webmanifest` | Web app manifest |

**HTML to include:**
```html
<link rel="icon" href="/favicon.svg" type="image/svg+xml">
<link rel="icon" href="/favicon.ico" sizes="32x32">
<link rel="apple-touch-icon" href="/apple-touch-icon.png">
<link rel="manifest" href="/site.webmanifest">
<meta name="theme-color" content="#5282a8">
```

### Social / OG

| File | Size | Use |
|------|------|-----|
| `social/og-dark.png` | 1200×630 | Open Graph / Twitter card (dark bg) |
| `social/og-light.png` | 1200×630 | Open Graph / Twitter card (light bg) |

**HTML:**
```html
<meta property="og:image" content="/og-dark.png">
<meta property="og:image:width" content="1200">
<meta property="og:image:height" content="630">
```

## Color Palette

| Role | Hex | Preview |
|------|-----|---------|
| Body light | `#6898be` | Planet highlight |
| Body mid | `#5282a8` | Planet body |
| Body dark | `#3e6c92` | Planet shadow |
| Moon light | `#7cb2d4` | Moon highlight |
| Moon mid | `#669cc0` | Moon body |
| Moon dark | `#5086aa` | Moon shadow |
| Pupil | `#12202e` | Eye pupils |
| Theme | `#5282a8` | Brand primary / theme-color |
| Dark bg | `#0e1520` | Website dark mode |

## Usage Guidelines

- **Do** use on solid or simple backgrounds
- **Do** maintain aspect ratio when scaling
- **Don't** add drop shadows, borders, or effects — the logo has its own lighting
- **Don't** recolor — the blue palette is the identity
- **Don't** separate the moon from the planet — they're a pair
