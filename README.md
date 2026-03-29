# composability-website

The official website for [Composable Consulting](https://composability.co) — strategic advisory and hands-on GTM execution for deep technology companies.

---

## Overview

Single-page static website built in plain HTML and CSS. No frameworks, no build tools, no dependencies. The entire site lives in one file: `index.html`.

Hosted on **Cloudflare Pages** with automatic deployment on every commit to `main`.

---

## Stack

- **HTML / CSS** — single file, no build step required
- **Fonts** — Playfair Display + DM Sans via Google Fonts
- **Hosting** — Cloudflare Pages
- **Domain** — composability.co (DNS managed via Cloudflare)

---

## File Structure

```
composability-website/
├── index.html       # The entire site
└── README.md        # This file
```

---

## Making Changes

### Small text edits (titles, descriptions, tags)
1. Open `index.html` in GitHub
2. Click the pencil (edit) icon
3. Find the text you want to change using `Ctrl+F` / `Cmd+F`
4. Make your edit
5. Click "Commit changes" with a short description of what changed
6. Cloudflare redeploys automatically within ~60 seconds

### Design or content changes
Work with Claude at claude.ai to iterate on the design, then:
1. Download the updated `index.html`
2. Open `index.html` in GitHub, click edit
3. Select all (`Ctrl+A` / `Cmd+A`), paste the new code
4. Commit and Cloudflare redeploys

---

## Deployment

Deployments are automatic. Every commit to `main` triggers a Cloudflare Pages build. No manual steps needed.

To check deployment status, go to the Cloudflare Pages dashboard and click the `composabilitywebsite` project.

---

## Domain

`composability.co` is registered via GoDaddy. DNS is managed through Cloudflare. SSL is handled automatically by Cloudflare — no certificates to manage.

---

## Contact

Nick Marcisz — nick@composability.co
