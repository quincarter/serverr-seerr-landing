# ServerSeerr Landing Page

<div align="center">
  <img src="public/icon.png" width="128" height="128" alt="ServerSeerr Icon" />
  <h1>ServerSeerr</h1>
  <p>Request. Sync. Watch. The ultimate mobile companion for your Overseerr or Jellyseerr media server.</p>
</div>

## 🚀 Project Overview

This is the official landing page for **ServerSeerr**, built with [Astro](https://astro.build) using a highly customized version of the Portfolio template. It features a modern, "shiny" aesthetic with glassmorphism effects and native device showcases.

### Key Features:
- **Product Showcase:** Interactive, scroll-aware showcase of mobile, tablet, and desktop versions.
- **Cross-Platform:** Visualizing the app's native experience across iOS, iPadOS, and macOS.
- **Support & FAQ:** A dedicated section for user troubleshooting and common questions.
- **Privacy First:** Transparent privacy policy highlighting local-only data storage.
- **Native Performance:** Optimized for speed and SEO using Astro's static generation.

## 🛠️ Tech Stack

- **Framework:** [Astro](https://astro.build)
- **Styling:** Vanilla CSS with modern Flexbox/Grid and Glassmorphism.
- **Icons:** [Phosphor Icons](https://phosphoricons.com/) integration.
- **Deployment:** Optimized for static hosting (Vercel/Netlify/GitHub Pages).

## 📁 Project Structure

```text
/
├── public/                 # Static assets (favicons, app icons)
│   └── assets/             # Images and device screenshots
├── src/
│   ├── components/         # Reusable Astro components (Nav, Hero, Icons)
│   ├── layouts/            # BaseLayout for consistent page structure
│   ├── pages/              # Site routes (Home, Showcase, Support, Privacy, About)
│   └── styles/             # Global CSS variables and theme configuration
└── astro.config.mjs        # Astro configuration
```

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Installs dependencies                            |
| `npm run dev`             | Starts local dev server at `localhost:4321`      |
| `npm run build`           | Build your static site to `dist/`                |
| `npm run preview`         | Preview your build locally                       |
| `npm run astro ...`       | Run native Astro CLI commands                    |

---

Built with ❤️ for the media server community.
