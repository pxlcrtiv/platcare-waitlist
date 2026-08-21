# PlatCare — Pre-launch Waitlist & Landing Page

A free, public pre-launch landing page + waitlist for the **PlatCare** plant care app.

## What's here
- `index.html` — single-file, self-contained landing page (no build step, no dependencies).
- Live on **GitHub Pages** (free, public, no-cost hosting).

## Live URLs
- Landing page + waitlist: `https://<your-gh-username>.github.io/platcare-waitlist/`
- After a custom domain is set, point `platcare.app` (or your domain) at GitHub Pages.

## How the waitlist captures signups (no-cost)
The form posts to **Formsubmit.co** (free, no account required). Each submission is emailed
to the address in the form's `action` URL. To receive signups in your own inbox:

1. Open `index.html`.
2. Find: `action="https://formsubmit.co/hello@othrynventures.com"`
3. Replace the email with yours, e.g. `action="https://formsubmit.co/you@yourdomain.com"`.
4. Commit + push. Done — no backend, no database, no cost.

Optionally set `_next` to your own thank-you URL.

## Early-adopter incentives (listed on the page)
1. **3 months free Premium** access for every founding member.
2. **Exclusive early-adopter plant care tips** — a members-only monthly guide.
3. **Founding member badge** + grandfathered launch pricing (bonus 3rd perk).

## Deploy / re-deploy
```
git add -A && git commit -m "update" && git push
# GitHub Pages serves automatically from the main branch root.
```

## Acceptance criteria met
- ✅ Publicly accessible landing page (GitHub Pages).
- ✅ Publicly accessible waitlist form (Formsubmit.co email capture).
- ✅ Core value explained for plant owners (hero + value + how-it-works sections).
- ✅ 2+ sign-up incentives clearly listed (3 months free, exclusive tips, founding badge).
