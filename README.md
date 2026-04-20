# Mall of America — Interactive Sales Deck

A cinematic, full-screen interactive sales deck built for Mall of America's commercial team. Designed in the Digideck format — slide-by-slide presentation, not a scrolling website.

## Live Demo
Deployed on Vercel: [your-vercel-url.vercel.app]

## Features
- 16 full-screen presentation slides
- Chapter navigation menu
- Slide thumbnail strip with click-to-jump
- Keyboard arrow navigation (← →)
- Touch/swipe support
- Animated data bars per slide
- Inquiry modal (Leasing, Events, Sponsorship, F&B, Pop-Up)
- Custom animated cursor
- Cinematic YouTube video background on hero slide
- Gold progress bar

## Chapters
1. Opening — Hero with live video background
2. The Property — Location, demographics, reach
3. Stats Snapshot — Key numbers at a glance
4. Retail Overview — Environment & positioning
5. Tenant Grid — 20+ named brands
6. Luxury — Wing positioning & brands
7. Dining & Lifestyle — F&B ecosystem
8. Entertainment — 6 attractions overview
9. Nickelodeon Universe — Feature slide
10. Events Overview — Venues & annual portfolio
11. Past Activations — Notable event highlights
12. Sponsorship Tiers — 3-tier partnership cards
13. Audience Intelligence — Demographic data bars
14. Leasing Paths — 4 leasing categories
15. Leasing Process — 5-step onboarding
16. Closing CTA — Contact & action

## Tech Stack
- Pure HTML / CSS / JavaScript — zero frameworks, zero dependencies
- Google Fonts: Cormorant Garamond + Barlow + Barlow Condensed
- YouTube IFrame API for hero video background
- Single file: `index.html`

## Deploy on Vercel
1. Push this repo to GitHub
2. Go to [vercel.com](https://vercel.com) → New Project
3. Import your GitHub repo
4. Framework Preset: **Other**
5. Click **Deploy** — done

## Deploy on GitHub Pages
1. Go to repo Settings → Pages
2. Source: **Deploy from a branch**
3. Branch: `main` / `root`
4. Save — live at `https://yourusername.github.io/moa-deck`

## AI Tools Used
- Claude (Anthropic) — full code generation, slide architecture, copywriting
- Design references: Digideck, Apple.com, Tesla.com, Hermès

## Local Development
No build step required. Just open `index.html` in any browser:
```bash
open index.html
# or
npx serve .
```

## Navigation
| Action | Control |
|---|---|
| Next slide | → Arrow / Space |
| Previous slide | ← Arrow |
| Jump to slide | Click thumbnail strip |
| Jump to chapter | ☰ menu (bottom left) |
| Swipe | Touch left/right |

---
Built for the Liat.ai interview assignment — Mall of America Commercial Sales Deck.
