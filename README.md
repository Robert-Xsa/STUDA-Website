# STUDA — Student Academic Data Application

A marketing/landing website for STUDA, a cross-platform, offline-first examination records management system for schools.

## About

STUDA streamlines student academic records management with features like registration, marks entry, automatic grade/rank calculation, PDF report card generation, class summaries, and SMTP-based automated backups — all with an offline-first architecture powered by SQLite.

This repository contains the promotional website. The actual Flutter application is hosted separately.

## Tech Stack

- **HTML5** — Structure
- **CSS3** — Custom styling with variables, gradients, and animations
- **Bootstrap 5.3.3** — UI framework
- **Bootstrap Icons 1.11.3** — Iconography
- **Google Fonts (Inter)** — Typography
- **Vanilla JS** — Dynamic footer year

No build tools or package managers required — purely static.

## Getting Started

Serve the site locally using any static file server:

```bash
# Python 3
python3 -m http.server 8080

# Node.js (via npx)
npx serve .

# PHP
php -S localhost:8080
```

Then open `http://localhost:8080` in your browser. You can also open `index.html` directly.

## Deployment

Push to the `main` branch — the site is served via GitHub Pages from `https://github.com/Robert-Xsa/STUDA-Website`.

## Project Structure

```
STUDA-Website/
├── index.html        # Single-page website (embedded CSS + JS)
├── STUDA-logo.png    # Logo and favicon
└── README.md         # This file
```

## Download Links

The download buttons link to Google Drive where the STUDA application binaries are hosted for Windows, macOS, Linux, and Android.

## Author

**Robert Gembe**

- GitHub: [@Robert-Xsa](https://github.com/Robert-Xsa)
- LinkedIn: [Robert Gembe](https://www.linkedin.com/in/robert-gembe)

## License

All rights reserved.
