# AutoRepHero — R.A.P.I.D. Hero Business Building System™
## Business Plan & System Overview
### Version 1.0 — March 16, 2026

---

## 🎯 Mission
Empower local businesses to get more customers through automated reputation management, smart marketing tools, and a complete digital presence system — without expensive agencies or complex software.

## 🧭 Anti-Positioning
"We're not GoHighLevel. We're not another guru funnel. We're tools that actually work, priced so real businesses can afford them."

---

## 📦 THE RAPID PRODUCT SUITE

### R — Response
### A — AI & Automation  
### P — Protection & Integrity
### I — Integration
### D — Deployment

---

## PRODUCT MAP

### 1. RBC — Rapid Business Card Hero (FREE)
**Subdomain:** rbc.autorephero.com
**Status:** ✅ Prototype live at tap.autorephero.com
**What:** Digital business card — share via NFC, QR, text, link
**Revenue:** Free (lead magnet → introduces users to AutoRepHero ecosystem)
**Viral loop:** Every shared card = ad for AutoRepHero
**TODO:**
- [ ] Move from tap.autorephero.com to rbc.autorephero.com (or keep both)
- [ ] Add "Rate AutoRepHero" prompt for users who love the app
- [ ] Backend: save cards to database (currently client-side only)
- [ ] User accounts so people can edit their cards
**Timeline:** 1-2 weeks for backend + accounts

---

### 2. RBO — Rapid Business Offer Hero (FREE trial → Low-cost entry)
**Subdomain:** rbo.autorephero.com  
**Status:** ❌ Not started
**What:** Digital offer/coupon creator + landing page builder
**Features:**
- AI-assisted offer creation ("What's your best offer that won't break you?")
- QR code for the offer
- Landing page to collect customer data (name, email, phone)
- Integrates with RBC (add offers to business card)
- Business directory of offers (future)
**Revenue:** Free trial → $19/mo for premium features (custom branding, analytics)
**TODO:**
- [ ] Design offer creator UI
- [ ] Build landing page generator
- [ ] Lead capture form → email to business owner
- [ ] AI offer prompt ("Help me figure out my best offer")
- [ ] Integration with RBC
**Build with:** Lovable (UI) + Me (integration)
**Timeline:** 2-3 weeks

---

### 3. RRDS — Rapid Review Deployment System (CORE)
**Subdomain:** app.autorephero.com (existing)
**Status:** ✅ Live — needs tweaks
**What:** Review hub with smart routing, AI review prompts, NFC/QR sharing
**Revenue:** $49/mo (Core Plan)
**Physical:** RRDS Deployment Kit ($149-199 one-time) — NFC cards, table tent, QR placard
**TODO:**
- [ ] Lock trial to Facebook + Yelp only (protect from Google suspension)
- [ ] Add "make it your own" guidance on review starters
- [ ] Platform limits: 3 trial / 5 core / unlimited pro
- [ ] Stripe integration (finish connecting tiers)
- [ ] Staff training checklist (Google TOS compliance)
**Build with:** Manus (already owns codebase)
**Timeline:** 1 week for tweaks

---

### 4. RBA — Reputation Business Automation (PRO)
**Subdomain:** rba.autorephero.com
**Status:** ❌ Not started — HIGHEST PRIORITY BUILD
**What:** Automated SMS/email follow-up, feedback collection, review requests, AI review responses
**Revenue:** $197/mo (Automation Pro)

**SMS Flow:**
```
Service completed → Wait X hours
  → SMS: "How was your experience? Reply 1-5"
    → 4-5 stars: "Leave us a review! [link]" → Review Hub
    → 1-3 stars: "What can we improve?" → Private feedback
      → 3 days, no response: Gentle reminder
        → Log everything
```

**AI Review Responses:**
- Monitor Google/Yelp/Facebook for new reviews
- AI generates personalized response
- Auto-post or send for owner approval

**Tech Stack:**
| Component | Tool | Cost |
|-----------|------|------|
| SMS | Twilio | $0.0079/text |
| Phone numbers | Twilio | $1.15/mo each |
| AI responses | OpenAI API | ~$0.002/response |
| 10DLC registration | Twilio | $15 one-time/client |
| Database | Neon Postgres | Free tier |
| Hosting | Vercel | Free tier |

**Cost per client:** ~$4-5/mo
**You charge:** $197/mo
**Margin:** 97%

**Requires client onboarding form:**
- Legal business name
- EIN / Tax ID
- Business address
- Website
- Contact info
- SMS use case description

**TODO:**
- [ ] Sign up for Twilio ✅ (Chuck has account)
- [ ] Register brand for 10DLC
- [ ] Build SMS automation engine
- [ ] Build AI review monitor + responder
- [ ] Client onboarding form (collects 10DLC-required data)
- [ ] Dashboard: SMS stats, review stats, response history
**Build with:** Manus (backend) + Me (Twilio integration + AI)
**Timeline:** 3-4 weeks

---

### 5. RCC — Rapid Content Creator Hero
**Subdomain:** rcc.autorephero.com
**Status:** ✅ v5 built (Content Creator Pro)
**What:** Photo-to-video creator, coupon graphics, blog content
**Revenue:** Included in Core ($49/mo) or standalone $29/mo
**TODO:**
- [ ] Final UI tweaks (banner slider, etc.)
- [ ] AI blog content generator (answer customer questions)
- [ ] Output widget for embedding on client websites
- [ ] Coupon/graphic template generator
**Build with:** Me + Lovable
**Timeline:** 2 weeks for AI content features

---

### 6. RCS — Rapid Content Share Hero
**Subdomain:** rcs.autorephero.com
**Status:** ❌ Research phase
**What:** Social media scheduling + posting across platforms
**Options:**
| Option | Cost | Pros | Cons |
|--------|------|------|------|
| Build custom (Meta/Google APIs) | Dev time only | Full control, no fees | Complex, maintenance |
| White-label Publer/SocialBee | $15-30/mo | Fast, reliable | Monthly cost per client |
| Buffer API | $6/mo per channel | Simple, proven | Limited white-label |
**Revenue:** $39-79/mo add-on or included in higher tiers
**TODO:**
- [ ] Research white-label social posting options
- [ ] Evaluate Meta Business API for direct posting
- [ ] Decide: build vs buy vs white-label
**Timeline:** Month 2-3

---

### 7. RBL — Reputation Business Listing/Citation Hero
**Subdomain:** rbl.autorephero.com
**Status:** ❌ Ready to implement
**What:** Citation building, monitoring, NAP consistency
**Fulfillment:**
1. Data Aggregators (free/cheap): Data Axle, Foursquare, Neustar
2. BrightLocal manual submissions: $2/site for top 20 directories
3. BrightLocal Citation Tracker: $8/mo per location

**Revenue:**
- Citation Boost: $299 one-time (your cost: ~$70)
- Citation Guard: $49/mo (your cost: ~$8/mo)
**Margin:** 77% on setup, 84% on monthly

**TODO:**
- [ ] Sign up for BrightLocal
- [ ] Create onboarding checklist for citation clients
- [ ] White-label BrightLocal reports as AutoRepHero
- [ ] Build citation health dashboard (or use BrightLocal's)
**Timeline:** Can start selling THIS WEEK

---

## 💰 PRICING LADDER

| Tier | Products Included | Price | Your Cost | Margin |
|------|-------------------|-------|-----------|--------|
| **Free** | RBC + RBO trial + RRDS trial (14 days) | $0 | $0 | — |
| **Deployment Kit** | RRDS Kit (NFC + placard + setup) | $149-199 one-time | ~$15 | 90%+ |
| **Core** | RRDS full + RCC + dashboard | $49/mo | ~$5 | 90% |
| **Pro** | Everything + RBA automation (SMS + AI) | $197/mo | ~$10 | 95% |
| **Citation Boost** | RBL one-time setup (60+ directories) | $299 one-time | ~$70 | 77% |
| **Citation Guard** | RBL ongoing monitoring | $49/mo add-on | ~$8 | 84% |
| **Premium** | Everything + website + hosting + email | $347/mo | ~$30 | 91% |

---

## 🏗️ CLIENT PORTAL

**URL:** portal.autorephero.com (or app.autorephero.com expanded)

**Client view:**
- Dashboard (reviews, SMS stats, citation health)
- Review Hub management
- Business card (RBC)
- Offers (RBO)
- Content creator (RCC)
- Settings (business info, team members)

**Admin view (you):**
- All clients overview
- Revenue dashboard
- Onboarding pipeline
- SMS usage / billing
- One-click client setup (clone template)
- White-label settings

**White-label view (resellers):**
- Their branding
- Their clients underneath
- They never see AutoRepHero

---

## 📅 BUILD TIMELINE

### PHASE 1 — WEEKS 1-2 (Revenue Ready)
| Task | Who | Status |
|------|-----|--------|
| Fix autorephero.com Vercel deployment | Chuck | 🔄 In progress |
| Swap www redirect (www → autorephero.com) | Chuck | TODO |
| RRDS tweaks (lock trial platforms, Stripe) | Manus | TODO |
| Set up subdomains (rbc, rbo, rba, etc.) | Chuck + Vercel | TODO |
| Sign up BrightLocal | Chuck | TODO |
| Start selling citations | Chuck | READY |
| Register 10DLC brand on Twilio | Chuck | TODO |
| Citation onboarding checklist | Me | TODO |
| Staff training checklist (Google TOS) | Me | TODO |

### PHASE 2 — WEEKS 3-6 (Core Product Build)
| Task | Who | Timeline |
|------|-----|----------|
| Client portal + admin dashboard | Manus | 2-3 weeks |
| Onboarding form (collects all client data) | Manus | Part of portal |
| Twilio SMS automation engine | Manus + Me | 1 week |
| AI review monitor + auto-responder | Me | 1 week |
| RBO offer/coupon creator | Lovable + Me | 2 weeks |
| RBC backend (save cards to DB, user accounts) | Manus | 1 week |

### PHASE 3 — MONTHS 2-3 (Scale & Polish)
| Task | Who | Timeline |
|------|-----|----------|
| White-label system for resellers | Manus | 2 weeks |
| RCS social sharing (research + build/buy) | TBD | 2-3 weeks |
| AI content/blog generator (RCC expansion) | Me | 2 weeks |
| Reporting/ROI dashboard per client | Manus | 1 week |
| Referral program | Manus | 1 week |
| Skool group setup + course creation | Chuck | Ongoing |
| Business website builder offering | Lovable + Manus | 2-3 weeks |

### PHASE 4 — MONTH 4+ (Growth)
| Task | Who |
|------|-----|
| AI chat widget for client websites | Manus |
| Advanced analytics + competitor tracking | Manus + Me |
| Mobile app (PWA already, native wrapper) | Manus |
| Reseller/agency program launch | Chuck |
| Course content for Skool | Chuck |

---

## 🗺️ SUBDOMAIN MAP

| Subdomain | Product | Status |
|-----------|---------|--------|
| autorephero.com | Marketing site | ✅ Live (needs www fix) |
| app.autorephero.com | RRDS Review Hub | ✅ Live |
| tap.autorephero.com | TapHero / RBC | ✅ Live |
| rbc.autorephero.com | Rapid Business Card | 🔜 Alias for tap |
| rbo.autorephero.com | Rapid Business Offer | ❌ Not built |
| rba.autorephero.com | Reputation Automation | ❌ Not built |
| rcc.autorephero.com | Content Creator | ❌ Not hosted yet |
| rcs.autorephero.com | Content Share | ❌ Not built |
| rbl.autorephero.com | Citation/Listings | ❌ Not built |
| portal.autorephero.com | Client Portal | ❌ Not built |
| ai.autorephero.com | Merchynt AI | ✅ Live (external) |

---

## 🔑 ACCOUNTS & ACCESS

| Service | Account | Status |
|---------|---------|--------|
| GitHub | AutoRepHero | ✅ |
| Vercel | Connected to GitHub | ✅ |
| Twilio | Chuck's account | ✅ (needs 10DLC) |
| Domain (Namecheap) | autorephero.com | ✅ (NS → Vercel) |
| Google Workspace | chuck@autorephero.com | ✅ |
| Stripe | Connected to app | 🔄 In progress |
| BrightLocal | Not yet | ❌ TODO |
| Merchynt | Active | ✅ |
| Neon Postgres | TBD | ❌ (for portal DB) |

---

## 🏆 COMPETITIVE ADVANTAGES

1. **Physical deployment** (NFC cards) — nobody else does this
2. **Free viral lead magnet** (RBC) — zero cost customer acquisition
3. **Anti-GHL positioning** — independent, affordable, no lock-in
4. **Complete system** — not just reviews, the whole visibility cycle
5. **White-label ready** — resellers can brand it as their own
6. **AI-powered but human-guided** — compliance training included
7. **Founder-led sales** — Chuck knows the local business world

---

## 💡 REVENUE PROJECTIONS (Conservative)

| Clients | Core ($49) | Pro ($197) | Citations ($49) | Monthly Revenue |
|---------|-----------|-----------|----------------|-----------------|
| 10 | 6 × $49 | 3 × $197 | 4 × $49 | **$1,081/mo** |
| 25 | 15 × $49 | 8 × $197 | 10 × $49 | **$2,801/mo** |
| 50 | 30 × $49 | 15 × $197 | 20 × $49 | **$5,405/mo** |
| 100 | 60 × $49 | 30 × $197 | 40 × $49 | **$10,810/mo** |

Plus one-time revenue: Deployment Kits ($149-199) + Citation Boosts ($299)

---

*Document created by Neo for Chuck Zaagsma / AutoRepHero*
*Last updated: March 16, 2026*
