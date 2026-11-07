# Rumi — Your Home Away from Home

Verified boarding-house marketplace for students, young professionals, and landlords in Cagayan de Oro.

Built by Team Agap (IT3R6).

## What's inside

| Path | What it is |
| --- | --- |
| `/` | Marketing landing page |
| `/app/` | Working mobile-frame prototype — pick Tenant or Landlord |
| `/dashboard/` | Early desktop landlord dashboard (reference) |
| `/prototypes/` | Earlier tenant-only prototype |
| `/assets/` | Logo and mobile screenshots |

## Run locally

Static site, no build step.

```bash
npx serve .
```

Then open http://localhost:3000 (landing) and http://localhost:3000/app/ (app).

## Deploy

```bash
vercel --prod
```

## Prototype scope

Tenant: search/filter, map, listing detail, in-app chat, roommate matching, trust score.
Landlord: overview, listings, inquiries (reply/ignore), settings.

Not built yet: real backend, auth, payments, digital lease contracts, AI matching.
