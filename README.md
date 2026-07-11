# Branden Tarot — Staging Site

Dark whimsical faery-trail redesign of brandentarot.com. Phase 1 mockup.

## Preview it
Open `index.html` in any browser. It's a single self-contained file (fonts load from Google Fonts, YouTube pulls Branden's latest uploads).

## Put it on the web for Branden to review (GitHub Pages)
1. Push `index.html` and this README to the `brandentarot` repo:
   ```
   git init
   git add index.html README.md
   git commit -m "Phase 1 faery-trail mockup"
   git branch -M main
   git remote add origin https://github.com/rwolfe1979/brandentarot.git
   git push -u origin main
   ```
2. On GitHub: **Settings → Pages → Source: Deploy from a branch → main / root → Save.**
3. Live preview appears at: `https://rwolfe1979.github.io/brandentarot/`

## Project structure (self-contained — all images local)
```
brandentarot/
├── index.html            the whole site (one file)
├── README.md
├── RECOMMENDATIONS.md    strategy write-up
├── .nojekyll             tells GitHub Pages to serve files as-is
└── assets/
    ├── forest-bg.jpg         misty pine-forest backdrop (generated, fixed behind sections)
    ├── moon.png              the moon (optimized, warm-tinted in CSS)
    ├── branden.jpg           portrait
    ├── fern.png              fern illustration, flipped/reoriented in corners
    ├── mushroom-amanita.png  red fly agaric (hero)
    ├── mushroom-champ1.png   tall inky-caps (about)
    ├── mushroom-champ2.png   honey cluster (readings)
    ├── mushroom-tall.png     bolete pair (offerings)
    └── mushrooms-cluster.png porcini + moss (testimonials)
```
Vintage botanical mushrooms are scattered one-per-section so you pass a different one
as you scroll down the trail. All optimized (~110-170KB each).
No hotlinks — everything renders on GitHub Pages. The only external embed is Branden's
YouTube feed on the Watch section.

## Still placeholder (to wire up after Branden approves)
- **Book / Pay button** — drops in Square Appointments or Acuity once Branden picks one.
- **Send a Message** — connect to a form service (e.g., Formspree) or mailto.
- **Pricing** — confirm the 2017 numbers still hold.

## Faery-forest art added
Framing tree trunks (both