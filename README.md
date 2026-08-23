# Pee Skin & MedSpa — client preview build

Static site. No build step, no dependencies.

## Deploy to Netlify (drag and drop)
1. Go to app.netlify.com > Sites > "Add new site" > "Deploy manually".
2. Drag the **contents of this folder** (not the folder itself) onto the drop zone.
3. Netlify gives you a live URL like `peeskin-preview.netlify.app`. Rename it under
   Site configuration > Change site name.

Entry page is `index.html`.

## Before you share the link publicly
- Set a password: Site configuration > Access control > Visitor access > Password protection.
  Recommended for a client review link.
- Search engines are currently allowed in `robots.txt`. If this is a private preview,
  change it to `Disallow: /`.
- Replace `REPLACE-WITH-YOUR-DOMAIN` in `robots.txt` and `sitemap.xml` once a real
  domain is attached.

## Pages
- about.html
- bridal.html
- concerns.html
- contact.html
- gift-vouchers.html
- index.html (home)
- ingrown-hairs.html
- injectables.html
- journal.html
- laser-hair-removal.html
- mens.html
- pricing.html
- privacy.html
- refunds.html
- results.html
- salon.html
- spa-treatments.html
- terms.html
- treatments.html

`SiteNav.dc.html` and `SiteFooter.dc.html` are shared fragments loaded by every page.
Keep their filenames exactly as they are.

## Still needs client sign-off before this goes live
Every price and session count, the practitioner's name and credentials, the Nd:YAG
device claim, all review quotes and attributions, the 4.9-star / 127-reviews figure,
years-in-business and client-count stats, and the membership/package structure.

All photography is licensed stock (Unsplash / Pexels), used as a stand-in for the
client's own shoot. Replace before launch.
