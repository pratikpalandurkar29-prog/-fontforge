# FontForge — Extract Fonts from Any Website

[![Deploy to Production](https://github.com/pratikpalandurkar29-prog/-fontforge/actions/workflows/deploy.yml/badge.svg)](https://github.com/pratikpalandurkar29-prog/-fontforge/actions/workflows/deploy.yml)
[![CI](https://github.com/pratikpalandurkar29-prog/-fontforge/actions/workflows/ci.yml/badge.svg)](https://github.com/pratikpalandurkar29-prog/-fontforge/actions/workflows/ci.yml)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

> **FontForge** is a modern font extraction tool that identifies, analyzes, and lets you download fonts from any webpage instantly. Built for designers, developers, and typography enthusiasts.

## ✨ Features

- **Instant Detection** — AI-powered engine scans any webpage in milliseconds
- **Direct Download** — Get font files in WOFF2, WOFF, TTF, and OTF formats
- **Font Details & Preview** — View foundry, designer, license, supported languages, glyph count
- **CSS Snippets Ready** — Copy `@font-face` declarations and font-family stacks
- **Privacy First** — All analysis happens locally in your browser
- **Team Collaboration** — Share font collections, create style guides, sync across projects
- **Browser Extension** — Analyze fonts with one click (Chrome & Firefox)
- **API Access** — Integrate into your workflow with REST API
- **CLI Tool** — Use from your terminal

## 🚀 Quick Start

### Prerequisites
- Node.js 22.23.4 or higher
- npm (comes with Node.js)

### Installation

```bash
# Clone the repository
git clone https://github.com/pratikpalandurkar29-prog/-fontforge.git
cd -fontforge

# Install dependencies
npm install

# Start development server
npm run dev
```

Visit `http://localhost:4321` to see the site.

### Build for Production

```bash
npm run build
```

Output goes to `./dist` — ready for static hosting.

### Preview Production Build

```bash
npm run preview
```

## 📁 Project Structure

```
src/
├── pages/index.astro          # Main landing page
├── layouts/Layout.astro       # Base HTML layout with SEO
├── styles/global.css          # Tailwind v4 import
└── components/
    ├── Hero.astro             # Landing hero with animations
    ├── Features.astro         # 6 feature cards
    ├── Demo.astro             # Interactive font analyzer demo
    ├── HowItWorks.astro       # 4-step process + advanced features
    ├── Testimonials.astro     # Customer testimonials
    ├── Pricing.astro          # 3-tier pricing with toggle
    ├── CTA.astro              # Call-to-action section
    └── Footer.astro           # Links & social icons
```

## 🛠 Tech Stack

- **[Astro 7](https://astro.build)** — Static site generator
- **[Tailwind CSS v4](https://tailwindcss.com)** — Utility-first CSS
- **TypeScript** — Type-safe component scripts
- **Vanilla JS** — Zero-framework interactivity

## 📦 Deployment

### GitHub Pages (Free)

1. Go to **Settings → Pages**
2. Source: "GitHub Actions"
3. The deploy workflow handles the rest on push to `main`

### Vercel (Recommended)

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2Fpratikpalandurkar29-prog%2F-fontforge)

1. Connect your GitHub repo to Vercel
2. Framework preset: **Astro**
3. Build command: `npm run build`
4. Output directory: `dist`
5. Deploy — auto-deploys on every push

### Netlify

[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/pratikpalandurkar29-prog/-fontforge)

1. Connect repo to Netlify
2. Build command: `npm run build`
3. Publish directory: `dist`

## 🔧 Available Scripts

| Command | Description |
|---------|-------------|
| `npm run dev` | Start dev server at localhost:4321 |
| `npm run build` | Build production site to `./dist` |
| `npm run preview` | Preview production build locally |
| `npm run astro` | Run Astro CLI commands |

## 🧪 CI/CD Pipeline

The repo includes GitHub Actions workflows:

- **CI** (`ci.yml`) — Runs on every PR/push:
  - TypeScript type checking
  - Astro build verification
  - Linting (if configured)

- **Deploy** (`deploy.yml`) — On push to `main`:
  - Builds the site
  - Deploys to GitHub Pages

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch: `git checkout -b feature/amazing-feature`
3. Commit your changes: `git commit -m 'Add amazing feature'`
4. Push to the branch: `git push origin feature/amazing-feature`
5. Open a Pull Request

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.

## 🙏 Acknowledgments

- Built with [Astro](https://astro.build)
- Styled with [Tailwind CSS](https://tailwindcss.com)
- Icons via inline SVG
- Inspired by tools like WhatFont, Fontface Ninja, and CSS Peeper

---

**Made with ❤️ for the web** — Powered by Astro + Tailwind