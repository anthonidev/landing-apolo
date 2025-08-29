# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is an Astro-based landing page project called "landing-apolo" using TailwindCSS 4.x for styling. The project follows Astro's minimal template structure with modern Vite integration.

## Development Commands

Use pnpm as the package manager:

```bash
# Development server (runs on localhost:4321)
pnpm dev

# Production build
pnpm build

# Preview production build locally
pnpm preview

# Install dependencies
pnpm install
```

## Architecture

- **Framework**: Astro 5.x with TypeScript (strict config)
- **Styling**: TailwindCSS 4.x integrated via Vite plugin
- **Package Manager**: pnpm
- **Build Tool**: Vite (via Astro)

### Key Configuration Files

- `astro.config.mjs`: Astro configuration with TailwindCSS Vite plugin integration
- `src/styles/global.css`: Global stylesheet importing TailwindCSS
- `tsconfig.json`: TypeScript configuration extending Astro's strict preset

### Project Structure

- `src/pages/`: Astro pages (file-based routing)
- `src/styles/`: Global stylesheets
- `public/`: Static assets (favicon, icons, images)
  - `public/icons/`: SVG icons (logo.svg, maps.svg)
  - `public/images/`: Image assets (hero-banner.webp)

The project uses Astro's file-based routing where pages in `src/pages/` automatically become routes based on their filename.
