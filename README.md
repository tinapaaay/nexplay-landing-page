# NEXPLAY — landing page (concept redesign)

**Live site:** https://tinapaaay.github.io/nexplay-landing-page/

A concept redesign of the [NEXPLAY](https://www.nexplayglobal.com/) live-commerce landing page by Christine Joy Espiritu. It is not the official NEXPLAY website. Brand names, logos, figures and partner content belong to NEXPLAY and their respective owners.

## What's inside

- `index.html` is the whole page. Icons, the hero star field and the brand logos are drawn inline.
- `styles.css` holds every token from DESIGN.md as a CSS custom property at the top. The rest of the file only uses those.
- `DESIGN.md` is the **Night Signal** design system: a near-black gradient canvas, one broadcast green from the NEXPLAY logo, liquid-glass surfaces, and DM Sans + Inter.
- `images/` holds the page photos, and `logos/strip/` holds the 8 white logos in the "Trusted by" strip.
- `BACKLOG.md` lists open items: missing photos, remaining brand logos, and details to confirm.

Live-room video clips and two partner logos load from nexplayglobal.com.

## Design system

Lint DESIGN.md with Google's DESIGN.md linter:

```bash
npx -y @google/design.md@0.4.0 lint --format json DESIGN.md
```

## Run locally

```bash
python3 -m http.server 8765
```

Then open http://localhost:8765.
