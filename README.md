# Mrudula Portfolio

Personal portfolio website built with Next.js (App Router), React, and TypeScript.

## Tech Stack

- Next.js 15
- React 19
- TypeScript
- CSS (single global stylesheet)

## Features

- Responsive landing page with mobile-friendly layout
- Sticky top navigation with hamburger menu on small screens
- Hero, About, Education, Experience, Projects, Skills, and Contact sections
- Smooth reveal/scroll effects and themed visual styling
- Content-driven structure from a single data source

## Project Structure

- `app/page.tsx` main page composition
- `app/layout.tsx` root layout and fonts
- `app/globals.css` full site styling and responsive breakpoints
- `components/` UI and section components
- `data/portfolio.ts` all editable portfolio content
- `types/portfolio.ts` shared content types

## Prerequisites

- Node.js `>=20 <23` (recommended: Node `22`)
- npm

Use the included `.nvmrc`:

```bash
nvm use
```

## Run Locally

```bash
npm install
npm run dev
```

Open `http://localhost:3000`.

## Build and Start

```bash
npm run build
npm run start
```

## Lint

```bash
npm run lint
```

If this is the first lint run, Next.js may ask to initialize ESLint config.

## Customize Content

Update portfolio details in:

- `data/portfolio.ts`

This file controls nav items, hero text, experience, projects, skills, contact links, and footer content.

## Deploy

Deploy easily on Vercel:

1. Push this repo to GitHub
2. Import the repo in Vercel
3. Keep default build settings (`next build`)

## GitHub Push (Quick Steps)

```bash
git init
git add .
git commit -m "Initial portfolio"
git branch -M main
git remote add origin https://github.com/<your-username>/<repo-name>.git
git push -u origin main
```
