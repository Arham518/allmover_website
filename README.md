# All Mover

Marketing landing page for **All Mover**, a Vermont agri-tourism app. Static **HTML / CSS with Bootstrap 5.3**: hero, feature cards, App Store / Play Store badges, QR codes and social links.

> **Status:** static marketing page only. Store badges and QR codes are presentational — they are not wired to live store listings from this repo.
> `README.txt` and `OFL.txt` belong to the bundled **Baloo Bhaijaan 2** font license, not the project docs.

## Features

- Hero with Vermont agri-tourism pitch
- Feature / card sections with local SVG artwork
- App Store and Play Store badge images + QR placeholders
- Social icon links
- Custom Baloo Bhaijaan 2 font (SIL OFL — see `OFL.txt`)

## Setup

Open `index.html` in a browser, or serve the folder:

```bash
npx serve .
```

No `npm install` required.

## Project structure

```
index.html                 main landing page
allmoverstyle.css          custom styles
bootstrap-5.3.3-dist/      Bootstrap 5.3 assets
font/  static/             Baloo Bhaijaan 2 font files
*.svg  *.png               logos, badges, QR, card art
OFL.txt  README.txt        font license (not app docs)
```

## Known limitations

- No JavaScript app logic — marketing shell only.
- Download / store links are images; confirm URLs before a public launch.
- Page title in `index.html` is still the short `all mover` label.

## Roadmap

1. Point store badges at real App Store / Play Store URLs
2. Tighten meta title / description for SEO
3. Optional lightweight analytics

## Security

No secrets needed. Static assets only.

## Author

Muhammad Arham · [GitHub Arham518](https://github.com/Arham518)
