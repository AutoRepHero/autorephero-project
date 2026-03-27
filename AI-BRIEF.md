# AI BRIEF — Chuck Zaagsma Projects
## Quick reference for any AI assistant. Updated: March 27, 2026

## WHO
- **Chuck Zaagsma** — entrepreneur, Spokane WA
- **Businesses:** AutoRepHero (review SaaS), King's Best™ (wellness products), Webbook (book publishing)
- **Brand thread:** H.E.R.O. = Honest Engagement, Real Outcomes
- **Email:** chuck@autorephero.com
- **Stripe:** pay.chuckzonline.com
- **GitHub:** github.com/AutoRepHero

## WHAT'S LIVE

| Product | URL | What it does |
|---------|-----|-------------|
| RRDS Review App | app.autorephero.com | Multi-tenant review collection SaaS with AI review helper |
| Marketing Site | autorephero.com | AutoRepHero landing page |
| King's Best | thekingsbest.com | Premium wellness products (3 products) |
| Webbook | webbook-brown.vercel.app | "Taking Authority" book — 14 chapters + bonus, $7 |
| RBC (paused) | rbc.autorephero.com | Digital business card builder with progressive unlock |

## TECH STACK
- **Hosting:** Vercel (all projects)
- **Database:** Neon Postgres (arh_ tables for AutoRepHero, bp_ tables for BrawnPro)
- **API:** tRPC + Vercel Node runtime (NOT Edge — bcryptjs needs Node crypto)
- **Frontend:** React/Vite for RRDS app, static HTML for everything else
- **Payments:** Stripe via pay.chuckzonline.com
- **Domains:** Namecheap (autorephero.com, thekingsbest.com, chuckz.online)

## KEY DECISIONS
- No Express on Vercel — use tRPC fetch adapter with Node runtime
- No superjson — ESM-only, breaks Vercel CJS
- No pnpm — removed, using npm with --force
- Review AI helper: tag bubbles → natural phrase mapping → 3 generated reviews → edit → copy & go
- Crown icon: thin modern outline (Style C)
- Book price: ~~$14.95~~ $7.00 launch price
- All products use same Neon Postgres instance

## REPOS
- `AutoRepHero/autorephero-app` — RRDS review app
- `AutoRepHero/autorephero-site` — marketing site
- `AutoRepHero/kings-best` — thekingsbest.com
- `AutoRepHero/tapcard` — RBC (Rapid Business Contact)
- `AutoRepHero/webbook` — book platform
- `AutoRepHero/autorephero-project` — docs, branding, AI brain files

## KING'S BEST PRODUCTS
- **Apex Crown Sentry™** — daily moisturizer w/ mineral sun protection ($29.99)
- **Rise & Move™** — energizing muscle rub ($27.99)
- **Rest & Restore™** — nighttime recovery rub ($27.99)
- Base ingredients (all): Coconut Oil, Shea Butter, Beeswax, Olive Oil, Aloe Vera
- Print-ready labels: thekingsbest.com/labels-print-ready.html

## CHUCK'S BOOK
- **Title:** Taking Authority in Your Life — The Power of the Spoken Word
- **Author:** Charles Zaagsma
- **ISBN:** 978-1-63844-534-0 (paper) / 978-1-63844-535-7 (digital)
- **Access code:** ?code=king2026 (unlocks full book)
- **Bonus:** "Word Planet" — Chuck's first ever writing
