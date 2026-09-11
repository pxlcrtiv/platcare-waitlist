# PlantCare — Pre-launch Waitlist & Landing Page

A free, public pre-launch landing page + waitlist for the **PlantCare** plant care app.

## What's here
- `index.html` — single-file landing page (no build step, no dependencies).
- `privacy.html` — privacy policy (Play Data Safety requirement).
- `logo.svg` + `fav/` — Seed of Life brand mark, favicons, Apple touch icon.
- `vercel.json` — clean URLs (`/privacy` instead of `/privacy.html`).

## Deploy on Vercel (recommended — custom domain lives here)

1. Push this repo to GitHub (already at `pxlcrtiv/platcare-waitlist`).
2. Go to [vercel.com/new](https://vercel.com/new) → Import the repo.
3. Framework Preset: **Other**. Build Command: empty. Output Directory: empty (static).
4. Deploy — you get `https://<project>.vercel.app` instantly.

No code changes needed: static HTML deploys as-is from any branch
(`master` is production; other branches get preview URLs).

## Custom domain (buy it on Vercel)

1. In the Vercel project → **Settings → Domains** → buy `plantcare.app`
   (or add it if owned elsewhere — Vercel gives you DNS records).
2. Set as production domain. HTTPS is automatic.
3. Update `og:image` in `index.html` if the domain differs.

GitHub Pages stays as a free fallback mirror (serves from `master` root).

## How the waitlist captures signups
The form is a **Kit inline embed** (`<script data-uid="ca0c0d3185" ...>` in `index.html`).
Every signup lands directly in Kit tagged `waitlist` and triggers the welcome automation.
Edit copy/design in Kit (Poplar form) — changes go live automatically, no deploy needed.

(Formsubmit was the original capture method; retired once the Kit embed went live.)

## Early-adopter incentives (listed on the page)
1. **3 months free Premium** access for every founding member.
2. **Exclusive early-adopter plant care tips** — a members-only monthly guide.
3. **Founding member badge** + grandfathered launch pricing (bonus 3rd perk).
