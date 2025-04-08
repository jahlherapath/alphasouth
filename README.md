# AlphaSouth

A lightweight front-end site built with [Parcel](https://parceljs.org/) and configured for GitHub Pages deployment.

Live site: [https://jahlherapath.github.io/alphasouth](https://jahlherapath.github.io/alphasouth)

---

## Getting Started

### 1. Install dependencies

```bash
pnpm install
```

### 2. Start local development

```bash
pnpm dev
```

Runs the site in development mode at `http://localhost:1234`.

### 3. Build for production

```bash
pnpm build
```

Outputs static files to the `docs/` folder, ready for deployment.

> GitHub Pages is configured to serve from the `docs/` directory on the `main` branch.

---

## Tech Stack

- [Parcel v2](https://parceljs.org/)
- [pnpm](https://pnpm.io/)
- [gh-pages](https://github.com/tschaub/gh-pages)
- [SVGO](https://github.com/svg/svgo) for SVG optimization

---

## Project Structure

```
src/
├── index.html
├── style.css
└── main.js
```

---

## Hosting

The site is hosted via GitHub Pages from the `docs/` folder in the `main` branch:

[https://jahlherapath.github.io/alphasouth](https://jahlherapath.github.io/alphasouth)

---

## License

MIT — © 2025 Jahl Herapath

---