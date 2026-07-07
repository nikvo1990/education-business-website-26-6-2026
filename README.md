# VoutsPhysics Website

A clean, professional 4-page website for **VoutsPhysics** — 1-on-1 IB, IGCSE & A-Level Physics
tutoring in Athens and online. Built with [Astro](https://astro.build).

**🔗 Live site: [vouts-physics.netlify.app](https://vouts-physics.netlify.app/)**

Pages: **Home**, **About**, **Services**, **Contact**.

---

## Run it on your computer

You need [Node.js](https://nodejs.org) installed (the "LTS" version is fine — you already have
the installer on your Desktop: `node-v24.16.0-x64.msi`).

Open a terminal **in this folder** and run:

```bash
npm install      # one time only — downloads what the site needs (~1 min)
npm run dev      # starts a live preview
```

Then open **http://localhost:4321** in your browser. Edits you save appear instantly.

To stop the preview, press `Ctrl + C` in the terminal.

---

## Put it online (free)

```bash
npm run build
```

This creates a `dist/` folder. Then either:

- **Easiest:** go to **https://app.netlify.com/drop** and drag the `dist/` folder onto the page.
  Your site is live in ~30 seconds. Sign in to claim it and rename the address.
- Or connect this project to a GitHub repo and Netlify for automatic updates.

After deploying, replace `example.com` with your real address in `public/robots.txt`,
`public/sitemap.xml`, and (optionally) `astro.config.mjs`.

---

## Where to change things

| What | File |
|------|------|
| Tagline & homepage text | `src/pages/index.astro` |
| Your story / About | `src/pages/about.astro` |
| Services list | `src/pages/services.astro` |
| Phone, email, social, booking link | `src/pages/contact.astro` (and `src/components/Footer.astro`, `src/components/Header.astro`) |
| Brand colours | `src/styles/global.css` (top of the file) |
| Logo & images | `public/images/` |

Your booking button points to: `https://calendly.com/voutsphysics/30min`
(search for `calendly` in the files to change it everywhere).
