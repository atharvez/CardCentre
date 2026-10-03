# CardCentre ðŸƒ

A full-stack e-commerce platform for trading cards built with Next.js and TypeScript.

## Overview

CardCentre is a modern trading card marketplace where collectors can buy, sell, and discover rare cards from popular TCG sets. The platform provides a clean, responsive UI with real-time inventory management.

## Tech Stack

| Layer | Technology |
|-------|-----------|
| Frontend | Next.js 15, TypeScript, Tailwind CSS |
| Backend | Next.js API Routes / Server Actions |
| UI Components | shadcn/ui |
| Deployment | Vercel |

## Features

- ðŸ›’ **Product Catalogue** â€” Browse cards by set, rarity, and price
- ðŸ” **Search & Filter** â€” Find specific cards quickly
- ðŸ›ï¸ **Cart & Checkout** â€” Smooth purchase flow
- ðŸ“¦ **Inventory Management** â€” Real-time stock tracking
- ðŸ–¼ï¸ **Card Previews** â€” High-quality card images
- ðŸ“± **Responsive Design** â€” Works on all devices

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

MIT Â© [Atharva Desai](https://github.com/atharvez)