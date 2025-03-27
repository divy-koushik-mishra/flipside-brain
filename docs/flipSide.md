# Flipside Brain - Project Documentation

## Overview
Flipside Brain is a productivity tool designed to limit distractions and promote deep work. This document tracks the entire development process, from ideation to implementation, scaling, and future enhancements.

## Branding
- **Name:** Flipside Brain
- **Slogan:** The smarter way to stay focused.
- **Domain:** flipside.online
- **Theme:** Calm, bright pastel colors

## Tech Stack
- **Frontend:** Astro (Landing Page & Blog)
- **Backend:** Express.js (Deployed separately)
- **Database:** MongoDB Atlas
- **Desktop App:** Electron.js
- **Browser Extension:** Chrome Extension (Syncs with Electron App)
- **SEO Optimization:** Metadata, Open Graph, Sitemap, etc.
- **Deployment:**
  - Landing Page & Blog: Vercel
  - Backend: TBD (Likely Railway/Render/Fly.io)

## MVP Features
- **Website Blocking**
- **Sync Between Electron App & Extension**
- **Deep Work Mode**
- **Basic User Dashboard (Later Stage)**

## Project Structure
```
flipside-brain/
├── apps/
│   ├── landing-page/      # Astro-based landing page (Vercel)
│   ├── electron-app/      # Electron desktop application
│   ├── browser-extension/ # Chrome extension for website blocking
│   ├── fullstack-app/     # Future full-stack dashboard (Headless CMS TBD)
│   └── backend/           # Express.js backend (API, Sync, DB operations)
│
├── docs/                  # Documentation, blog posts, & feature discussions
│   ├── flipside.md        # This file (Project roadmap & progress tracking)
│   ├── seo-strategy.md    # SEO-related notes & implementation steps
│   ├── future-features.md # Ideas for later versions (Scaling, AI, etc.)
│   └── deployment.md      # Deployment & DevOps notes
│
├── packages/
│   ├── shared-utils/      # Shared utilities (if needed across apps)
│   ├── eslint-config/     # Linting & formatting settings
│   └── ui-components/     # Shared UI components (for reuse)
│
├── .github/               # CI/CD workflows
├── README.md              # General project information
└── package.json           # Project dependencies & scripts
```

## Next Steps
1. **Deploy the Astro landing page on Vercel.**
2. **Set up Express backend for sync between Electron and Extension.**
3. **Develop MVP features for website blocking & deep work mode.**
4. **SEO optimization for landing page.**
5. **Future: Scale the product with authentication & dashboards.**

---
This document will evolve as we develop Flipside Brain. 🚀

