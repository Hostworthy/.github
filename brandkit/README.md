# Host39 brand kit

v1.0, November 2026. Start with **Host39-Brand-Guidelines.pdf**.

## What's inside

- `logo/svg` and `logo/png`: the logo in three forms, each in a dark and a white version.
  - `host39-lockup`: badge plus wordmark. Use this wherever there is room.
  - `host39-badge`: the "39" mark on its own, for avatars and icons.
  - `host39-wordmark`: "Host39" text only.
  - Files ending in `-white` / `-light` are for dark backgrounds.
- `icons`: app icon PNGs from 16 to 1024 px, plus `favicon.ico`, `favicon.svg`, `apple-touch-icon-180.png` and `android-chrome-192.png`.
- `social`: `github-avatar-500` (org picture) and `banner-1280x640` (repo social preview, README header).
- `colors`: `palette.css` (CSS variables), `tokens.json` and `palette.png`.

## Quick use

GitHub org picture: upload `social/github-avatar-500.png`.
Repo social preview: Settings, General, Social preview, upload `social/banner-1280x640.png`.

Website `<head>`:

```html
<link rel="icon" href="/favicon.ico" sizes="any">
<link rel="icon" href="/favicon.svg" type="image/svg+xml">
<link rel="apple-touch-icon" href="/apple-touch-icon-180.png">
```

## Fonts

Outfit (headings, wordmark) and Inter (body), both free on Google Fonts. The logo SVGs have the text converted to outlines, so they need no fonts installed.

## Colors

| Name | Hex | Use |
|---|---|---|
| Ink | #23303A | Logo, headings, body text |
| Paper | #F7F5F0 | Background |
| Ember | #E07A5F | Accent shapes, the power dot |
| Ember Text | #B4573A | Ember for words on light backgrounds |
| Sage | #6FA287 | Status: online, success |
| Mist | #DCE3E8 | Fills, dividers |
