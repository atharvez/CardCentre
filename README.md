# CardCentre

A full-stack e-commerce platform for trading cards built with Next.js and TypeScript.

## Overview

CardCentre is a modern trading card marketplace where collectors can buy, sell, and discover rare cards from popular TCG sets. Clean, responsive UI with real-time inventory management.

## Tech Stack

| Layer | Technology |
|-------|-----------|
| Frontend | Next.js 15, TypeScript, Tailwind CSS |
| Backend | Next.js API Routes / Server Actions |
| UI Components | shadcn/ui |
| Deployment | Vercel |

## Features

- Product catalogue -- browse cards by set, rarity, and price
- Search and filter -- find specific cards quickly
- Cart and checkout -- smooth purchase flow
- Inventory management -- real-time stock tracking
- Responsive design -- works on all devices

## Getting Started

```bash
git clone https://github.com/atharvez/CardCentre.git
cd CardCentre
npm install
cp .env.example .env.local
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser.

## Project Structure

```
CardCentre/
â”œâ”€â”€ app/                    # Next.js app router pages
â”‚   â”œâ”€â”€ (routes)/          # Route groups
â”‚   â””â”€â”€ api/               # API endpoints
â”œâ”€â”€ components/            # Reusable UI components
â”œâ”€â”€ lib/                   # Utility functions & helpers
â””â”€â”€ public/                # Static assets
```

## License

MIT (c) Atharva Desai