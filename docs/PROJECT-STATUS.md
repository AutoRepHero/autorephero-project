# AutoRepHero — Project Status
## Updated: March 27, 2026

---

## LIVE PRODUCTS

### 1. RRDS — Rapid Review Deployment System
- **URL:** app.autorephero.com
- **Status:** ✅ LIVE — signup, login, admin panel working
- **Stack:** Vercel Edge Functions + Neon Postgres + tRPC
- **Features:**
  - Multi-tenant review hubs (app.autorephero.com/review/SLUG)
  - AI review helper (tag bubbles → generated reviews → edit → copy & go)
  - Business owner dashboard (manage platforms, staff, settings)
  - Admin panel (Chuck) — manage all businesses, change plans, create accounts
  - Plans: Trial (FB/Yelp/BBB only), Kit $149, Core $47/mo, Automation $197/mo
  - Stripe billing connected (pay.chuckzonline.com)
- **DB Tables:** arh_users, arh_businesses, arh_platforms, arh_staff, arh_leads
- **Admin:** chuck@autorephero.com (role: admin)
- **Repo:** AutoRepHero/autorephero-app

### 2. RBC — Rapid Business Contact (PAUSED)
- **URL:** rbc.autorephero.com
- **Status:** ⏸ v1 built, paused for polish later
- **Features:**
  - Progressive unlock builder (Card → Offer → Follow → Reviews → Text Club)
  - Google Places business search auto-fill
  - AI offer suggestions by business type
  - Card type selector (Business/Personal/Church/Org/Realtor)
  - Examples overlay (Chuck, Zeal Church, BrawnPro, King's Best)
  - ⚡ bolt watermark on contact photos
  - PWA install support
  - Offer claim form with deal codes + expiry + exemptions
- **Repo:** AutoRepHero/tapcard

### 3. AutoRepHero Marketing Site
- **URL:** autorephero.com
- **Status:** ✅ LIVE
- **Stack:** Vite + React + Vercel
- **Repo:** AutoRepHero/autorephero-site

### 4. King's Best™ Wellness
- **URL:** thekingsbest.com
- **Status:** ✅ LIVE
- **Products:** Apex Crown Sentry™, Rise & Move™, Rest & Restore™
- **Labels:** Print-ready at thekingsbest.com/labels-print-ready.html
- **Repo:** AutoRepHero/kings-best

### 5. Webbook — Taking Authority in Your Life
- **URL:** webbook-brown.vercel.app (pending: read.chuckz.online)
- **Status:** ✅ LIVE — 14 chapters + bonus
- **Features:**
  - Landing page with real book cover
  - Chapter 1 free, share-to-unlock, pay $7 for full book
  - Stripe checkout connected
  - Access codes (?code=king2026 for full access)
  - Table of contents with free/locked indicators
  - Bonus: "Word Planet" — Chuck's first ever writing
  - Reading progress bar, font size controls
- **Book:** "Taking Authority in Your Life: The Power of the Spoken Word" by Charles Zaagsma
- **ISBN paperback:** 978-1-63844-534-0
- **ISBN digital:** 978-1-63844-535-7
- **Repo:** AutoRepHero/webbook

---

## BRAND

- **H.E.R.O.** = Honest Engagement, Real Outcomes
- **R.A.P.I.D.** = Response, AI & Automation, Protection, Integrity, Deployment
- **⚡ Rapid Business Contact** — the unified one-link product
- **Crown:** Thin modern outline (Style C) — used on book + King's Best

---

## ACCOUNTS & INFRA

- **GitHub:** AutoRepHero (github.com/AutoRepHero)
- **Vercel:** neoai943@gmail.com
- **Neon Postgres:** Same instance for BrawnPro + AutoRepHero (arh_ prefixed tables)
- **Stripe:** pay.chuckzonline.com
- **Google Workspace:** chuck@autorephero.com
- **Domains:** autorephero.com, thekingsbest.com, chuckz.online (Namecheap)

---

## TODO / NEXT

- [ ] Wire AI review helper into RBC Reviews section
- [ ] RBC: save/persist created cards to database
- [ ] RBC: short URLs for sharing
- [ ] Webbook: add audio narration (ElevenLabs)
- [ ] Webbook: workbook exercises after chapters
- [ ] Webbook: account system for multi-device access
- [ ] Webbook platform: open to other authors
- [ ] King's Best: order printed labels
- [ ] King's Best: new cover design for book (AI generated)
- [ ] AutoRepHero: RBA (automation — SMS follow-up, smart routing)
- [ ] Any.do style task app (Chuck exploring)
- [ ] Next book: research + AI-assisted writing in Chuck's style
