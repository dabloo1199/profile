# Aditi Tiwari — portfolio (static site)

Plain static files. No build step, no dependencies.

## Deploy

**Netlify (drag & drop)** — netlify.com/drop, drop this whole folder.
**Vercel** — `npx vercel` inside this folder, or import the repo and set framework "Other".
**GitHub Pages** — push the folder contents to a repo, Settings → Pages → deploy from branch (root).
**Any host / cPanel** — upload the contents to the web root.

Serve it locally with `npx serve` (opening index.html via file:// works too).

## Files
- index.html — main portfolio page
- case-study.html — case study template, driven by ?id=
  (zenfire, aimate, clara, goal-dashboard, invictus, onedigital, aif-calculator, zentrades-ds)
- support.js — runtime
- _ds/ — Organic design system (stylesheet + bundle)
- img/ — case study imagery

## Custom domain
Point an A/CNAME record at your host and add the domain in its dashboard. `aditi.design` or similar reads better on a resume than a subdomain.

## Before going live
- Four Centricity case studies show a "screens pending" panel — swap in real exports.
- Add a resume PDF and link it from the nav if you want recruiters to grab it in one click.
