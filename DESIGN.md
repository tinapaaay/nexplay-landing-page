---
version: alpha
name: Night Signal
description: >-
  A calm, near-silent black interface where one broadcast green marks what is
  live and what to press. Structure adapted from the Reflect Notes style
  reference, recolored to the NEXPLAY logo's black and green.
colors:
  primary: "#17e524"
  primary-hover: "#4ff05a"
  on-primary: "#000000"
  secondary: "#0b8a14"
  neutral: "#0a0d0b"
  neutral-mid: "#050706"
  neutral-deep: "#000000"
  surface: "#111412"
  surface-raised: "#191c1a"
  glass-edge: "#202321"
  on-surface: "#f2fff3"
  on-surface-strong: "#ffffff"
  on-surface-secondary: "#a6b0a7"
  on-surface-muted: "#8f9a90"
  outline: "#707a71"
  gradient-start: "#b6ff5c"
  gradient-end: "#19d3a2"
typography:
  display:
    fontFamily: DM Sans
    fontSize: 72px
    fontWeight: 500
    lineHeight: 1.11
    letterSpacing: -0.5px
  headline-lg:
    fontFamily: DM Sans
    fontSize: 56px
    fontWeight: 500
    lineHeight: 1.14
    letterSpacing: -0.4px
  headline-md:
    fontFamily: DM Sans
    fontSize: 48px
    fontWeight: 500
    lineHeight: 1.17
    letterSpacing: -0.3px
  headline-sm:
    fontFamily: DM Sans
    fontSize: 32px
    fontWeight: 500
    lineHeight: 1.25
    letterSpacing: -0.2px
  subheading:
    fontFamily: DM Sans
    fontSize: 24px
    fontWeight: 500
    lineHeight: 1.33
  title:
    fontFamily: DM Sans
    fontSize: 20px
    fontWeight: 500
    lineHeight: 1.3
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: 400
    lineHeight: 1.56
    fontFeature: '"calt" 0, "cv10", "liga" 0, "ss01"'
  body:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: 400
    lineHeight: 1.5
  body-ui:
    fontFamily: Inter
    fontSize: 15px
    fontWeight: 400
    lineHeight: 1.5
  label:
    fontFamily: Inter
    fontSize: 15px
    fontWeight: 500
    lineHeight: 1.2
  body-sm:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: 400
    lineHeight: 1.43
  badge:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: 500
    lineHeight: 1.2
  caption:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: 400
    lineHeight: 1.33
rounded:
  control: 5px
  card: 16px
  block: 24px
  badge: 32px
  full: 999px
spacing:
  unit: 4px
  s1: 4px
  s2: 8px
  s3: 12px
  s4: 16px
  s5: 20px
  s6: 24px
  s7: 28px
  s8: 32px
  s9: 36px
  s12: 48px
  s14: 56px
  s16: 64px
  s18: 72px
  page-max-width: 1200px
  page-padding-min: 24px
  page-padding-max: 48px
  section-gap-min: 96px
  section-gap-max: 120px
  card-padding-min: 24px
  card-padding-max: 32px
components:
  button-primary:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.on-primary}"
    typography: "{typography.label}"
    rounded: "{rounded.control}"
    padding: 12px
    height: 44px
  button-primary-hover:
    backgroundColor: "{colors.primary-hover}"
    textColor: "{colors.on-primary}"
  button-ghost:
    backgroundColor: "{colors.neutral}"
    textColor: "{colors.on-surface-muted}"
    typography: "{typography.body-ui}"
    rounded: "{rounded.control}"
  button-ghost-hover:
    backgroundColor: "{colors.neutral}"
    textColor: "{colors.on-surface}"
  nav-pill:
    backgroundColor: "{colors.surface}"
    textColor: "{colors.on-surface}"
    typography: "{typography.body-ui}"
    rounded: "{rounded.full}"
    height: 56px
  badge:
    backgroundColor: "{colors.surface}"
    textColor: "{colors.on-surface}"
    typography: "{typography.badge}"
    rounded: "{rounded.badge}"
    padding: 6px
  card:
    backgroundColor: "{colors.surface}"
    textColor: "{colors.on-surface-secondary}"
    rounded: "{rounded.card}"
    padding: 24px
  card-hover:
    backgroundColor: "{colors.surface-raised}"
    textColor: "{colors.on-surface}"
  feature-block:
    backgroundColor: "{colors.surface}"
    textColor: "{colors.on-surface-strong}"
    rounded: "{rounded.block}"
    padding: 32px
  feature-item:
    backgroundColor: "{colors.neutral}"
    textColor: "{colors.on-surface-muted}"
    typography: "{typography.body-ui}"
    padding: 16px
  text-link:
    backgroundColor: "{colors.neutral}"
    textColor: "{colors.primary}"
    typography: "{typography.label}"
  text-link-hover:
    backgroundColor: "{colors.neutral}"
    textColor: "{colors.on-surface}"
  product-frame:
    backgroundColor: "{colors.surface}"
    textColor: "{colors.on-surface}"
    rounded: "{rounded.card}"
  testimonial-result:
    backgroundColor: "{colors.surface}"
    textColor: "{colors.on-surface-strong}"
    typography: "{typography.headline-md}"
  photo-placeholder:
    backgroundColor: "{colors.surface}"
    textColor: "{colors.on-surface-muted}"
    typography: "{typography.body-sm}"
    rounded: "{rounded.card}"
  photo:
    backgroundColor: "{colors.surface}"
    rounded: "{rounded.card}"
  photo-thumb:
    backgroundColor: "{colors.surface}"
    rounded: "{rounded.control}"
  brand-index-name:
    backgroundColor: "{colors.surface}"
    textColor: "{colors.on-surface-secondary}"
    typography: "{typography.title}"
  brand-index-category:
    backgroundColor: "{colors.surface}"
    textColor: "{colors.on-surface}"
    typography: "{typography.body-sm}"
  capability-card:
    backgroundColor: "{colors.neutral}"
    textColor: "{colors.on-surface-muted}"
    typography: "{typography.body-ui}"
    rounded: "{rounded.card}"
    padding: 20px
  capability-card-hover:
    backgroundColor: "{colors.surface}"
    textColor: "{colors.on-surface}"
  phone-frame:
    backgroundColor: "{colors.neutral-deep}"
    rounded: "{rounded.badge}"
    padding: 8px
  room-clip:
    backgroundColor: "{colors.surface}"
    rounded: "{rounded.card}"
  room-tag:
    backgroundColor: "{colors.neutral}"
    textColor: "{colors.on-surface}"
    typography: "{typography.badge}"
    rounded: "{rounded.badge}"
  outline-rule:
    backgroundColor: "{colors.outline}"
    height: 1px
  page-canvas-top:
    backgroundColor: "{colors.neutral}"
    textColor: "{colors.on-surface}"
  page-canvas-mid:
    backgroundColor: "{colors.neutral-mid}"
    textColor: "{colors.on-surface}"
  page-canvas-bottom:
    backgroundColor: "{colors.neutral-deep}"
    textColor: "{colors.on-surface}"
  glass-edge-rule:
    backgroundColor: "{colors.glass-edge}"
    height: 1px
  chart-fill:
    backgroundColor: "{colors.secondary}"
  accent-gradient-start:
    backgroundColor: "{colors.gradient-start}"
  accent-gradient-end:
    backgroundColor: "{colors.gradient-end}"
---

# Night Signal

## Overview

A calm control room after dark. The page is a near-black gradient from top to bottom, with only a faint green hint at the top; text is a faintly green-tinted white, and a single broadcast green — sampled from the NEXPLAY logo's play triangle — marks what is live and what to press. Nothing shouts. Headlines are set in a medium weight (500), never bold, so the voice is confident rather than salesy. Surfaces are see-through liquid glass with a bright top edge, floating over the gradient.

The structure comes from the Reflect Notes style reference: a floating pill navigation, centered sections, a wide product view under the hero, a four-column feature grid and three-column testimonials. The violet palette is replaced with black and green to match the brand.

Imagery is product-first. The hero shows a dashboard view built from real operating figures. Below it are real live-room video clips and partner logos. Still photos follow one look: clean, minimal Apple-style product photography. Each has a deep near-black background, one clear subject, lots of negative space, soft single-side studio light with a gentle rim, neutral low-saturation color and at most one small green accent light. Generated images are allowed only if they pass as real photos. Reject any that show duplicated or mirrored people, garbled text or screens, waxy skin or over-glossy lighting. Slots without an approved photo keep a labeled placeholder at the final size. Photos are never tinted or filtered on the page. Feature icons are outlined 1.5px strokes in white. A faint star field (tiny white dots at low opacity) sits behind the hero only.

## Colors

- **Broadcast Green (#17e524) — `primary`:** the logo green. Used for the main button, links, active states, focus rings, "live" dots and small icons. It's punctuation, not paint — never a section background.
- **Green Wash (#4ff05a) — `primary-hover`:** the hover state of the main button.
- **Deep Green (#0b8a14) — `secondary`:** decorative only — chart fills and low-emphasis details. Never a button.
- **Canvas gradient — `neutral` (#0a0d0b) → `neutral-mid` (#050706) → `neutral-deep` (#000000):** the page background is one smooth vertical gradient running from the top of the page to the bottom, from a near-black with only a faint green hint to pure black. It's not flat black, and there are no glows, beams or light effects on it. The logo blends into it with `mix-blend-mode: lighten`, so its black box disappears.
- **Glass — `surface` and `surface-raised`:** see-through panels for cards, the nav pill, badges and the product frame. In CSS they're built as white at 3% and 6%, so the canvas gradient shows through them. The token values (#111412, #191c1a) are what those tints look like at the top of the page, which is also what the linter's contrast check needs. Raised is used for hover.
- **Glass edge — `glass-edge`:** the 1px border on every glass panel. In CSS it's white at 9%.
- **Text:** `on-surface` (#f2fff3) for headings and primary text — white with a faint green cast; `on-surface-secondary` (#a6b0a7) for body copy in cards; `on-surface-muted` (#8f9a90) for descriptions, metadata and ghost buttons. Pure white (`on-surface-strong`) is reserved for numbers in feature blocks.
- **Outline (#707a71):** used at 20–30% opacity for hairlines and frame edges.
- **Signal gradient (#b6ff5c → #17e524 → #19d3a2):** lime to green to teal. Only on one accent phrase of text per page and on thin decorative lines — never as a fill or button.

## Typography

- **Headings: DM Sans 500.** The reference's AeonikPro isn't freely available; DM Sans is its listed substitute. Medium weight at 48–72px is the signature — do not go to 600 or 700.
- **Body and UI: Inter 400/500**, with the stylistic set `ss01` and alternate `cv10` on, and contextual ligatures off, for a cleaner, more technical texture. Body 16px, UI text 15px, small text 14px, captions 12px.
- Headings scale down on phones with `clamp()`. Token sizes are the maximum.
- Sentence case everywhere. Uppercase is not used for labels or buttons.

## Layout

A centered 1200px column with 24–48px side padding. Sections sit 96–120px apart on one continuous dark canvas that fades slightly darker down the page — no alternating background bands. Section headers are centered: an optional badge, a 48–56px heading, then an 18px muted subtitle. Feature sections use a 4-column grid (2 columns on tablets, 1 on phones). Testimonials use 3 columns on desktop and become a sideways swipe row on phones and tablets, with the next card peeking in at 85% width. Headings use balanced line wrapping (`text-wrap: balance`), so no word is left alone on the last line. Card padding is 24–32px, and gaps inside are 8–16px on a 4px base unit.

## Elevation & Depth

Liquid glass on the gradient canvas. There are no drop shadows and no glows on the background. Every raised surface (cards, nav, badges, product frame, closing panel) uses the same four-part recipe:

1. **Top-lit fill:** a vertical gradient from white at 6% to 1.5%.
2. **Hairline edge:** a 1px `glass-edge` border.
3. **Bright top lip:** `inset 0 1px 0 rgba(255,255,255,0.12)`.
4. **Blur behind:** `backdrop-filter: blur(20px) saturate(150%)`.

**Hover:** the fill brightens to white at 9% → 3%, and the inner rim-light rises from `inset 0 0 24px rgba(255,255,255,0.04)` to `0.06`. Badges add the green under-glow (`inset 0 -7px 11px rgba(23,229,36,0.12)`). The nav adds a 55% black tint under its glass so links stay readable over content.

Don't add decorative glows, beams, grids or light spikes to the background. The canvas gradient alone carries the mood.

## Shapes

- Buttons and inputs: 5px (`control`).
- Cards and the product frame: 16px (`card`).
- Large feature blocks: 24px (`block`).
- Badges: 32px (`badge`).
- The nav pill and avatars: fully round (`full`).

Avoid in-between values like 8px or 12px.

## Components

- **Nav pill:** a floating, centered pill 56px tall on `surface` with the rim-light. It holds the logo on the left, links in 15px `on-surface`, and the primary button on the right. Links collapse below 900px.
- **Primary button:** green fill, black text, 15px/500, 5px radius, 44px minimum height. Hover changes it to Green Wash.
- **Ghost button:** no fill, `on-surface-muted` text, which changes to `on-surface` on hover. Use it for secondary actions.
- **Badge:** a pill on `surface` with a 1px green-tinted edge, 13px/500 text and the green under-glow. Use it above a few section headings, not all of them.
- **Feature item:** no card behind it. It has a 24px outlined icon (1.5px stroke, white), a 20px DM Sans title and 15px muted description, and floats on the canvas.
- **Card:** `surface`, 16px radius, 24px padding, with the rim-light. Hover changes it to `surface-raised`.
- **Feature block:** a large 24px-radius card for headline numbers. Numbers are in DM Sans and pure white.
- **Testimonial card:** ordered result first, then quote, then person, because buyers skim for outcomes before reading who said them.
  - **Logo:** the partner's logo at the top, in flat white at 60% opacity. Heights are tuned per logo so the logos look the same size.
  - **Result:** a 48px DM Sans number in pure white (for example, "+1,150%"), with a green trend icon and the timeframe in 14px secondary text below it. A hairline separates the result from the quote.
  - **Quote:** 15px text, trimmed to 2–3 complete sentences. Never cut a sentence mid-way or reword it.
  - **Person:** full name in 15px/500 and role in muted 14px.
  - Use no avatars or initials. Under the row, place the ratings source caption and a green text link to the booking section.
- **Text link:** green, 15px/500, followed by a chevron. It turns `on-surface` on hover.
- **Product frame:** a 16px-radius `surface` frame with a 1px outline at 25% and the rim-light. It holds the dashboard view.
- **Photo placeholder:** a `surface` box with a 1px dashed outline at 25%, a muted image icon and a short label naming the shot that belongs there (for example, "Live operations floor — wide shot of the pods"). It keeps the final photo's size: 21:9 wide, 16:10 standard, 9:19 phone, and a 5px radius for thumbnails. Replace the placeholder with an approved photo in the same slot. Wide photos use a 21:9 crop on desktop, anchored toward the people (`object-position: center 70%`), and the full 16:9 frame on phones with a 16px radius, and thumbnails use 16:10 with a 5px radius, both with a 1px solid outline. Photos sit beside text, never under it.

- **Phone frame:** a simple device outline (9:19, 32px radius, 8px bezel in `neutral-deep`, 1px glass edge and top lip) holding a muted, looping live clip with a 24px-radius screen. A small "Live" tag with a pulsing dot sits at the top left. Use it to show vertical live-selling video.
- **Brand index:** the full brand portfolio in one glass card, with one row per category (Beauty, Fashion, Tech, Food, Lifestyle) separated by hairlines. The brand list comes from `logos/manifest.json`.
  - **Logo first, text as fallback:** every brand with a reference-matched logo shows that logo. Brands without one yet show their name in DM Sans 20px `on-surface-secondary`, and they swap to logos automatically when added. Each row ends with a muted "+ more".
  - **Logos are inline SVG, not image files,** so logos built from typed text render in their real fonts. Each logo is painted with `currentColor` (`on-surface` at 70% opacity) through a mask, so details that were knocked out of a box (Hanford, Fibisco, Café Puro, Prestone) stay readable as cut-outs.
  - **Image-file logos:** brands that only have a raster image (`logos/raster/`, 15 logos) are converted to white PNGs with transparent backgrounds. Each image's background color is detected from its border, anything that differs from it becomes white (`#f2fff3`), and shapes in the background color (Hanes' lettering, Human Nature's heart) stay cut out. They're cropped tight and capped at 200px tall. Watermarked or stock images are never used.
  - **Sizing:** each logo's height (18–40px) is set so all of them cover about the same area, and they shrink to 85% on phones using `zoom`.
  - **Logo fonts** load from Google Fonts subset to only the letters the logos use, which keeps them to a few kilobytes. Inter weights 700 and 900 join the main Inter link instead, so the page's body text is never overridden by a subset.
  - **Category label:** 14px/500 in `on-surface`. On phones the label stacks above the logos.
  - **No hover state,** because the brands aren't links.
- **Capability card:** the 8 services in a 4×2 grid (2 columns on tablets, 1 on phones), with all content visible: a 24px outlined icon, a 20px title, a one-line description in 15px muted text, and the three sub-services as a small list (14px, green 4px dot, hairline separators). Nothing is hidden behind a click or hover. At rest the card has no surface. On hover it gets the glass recipe and its icon turns green. It's a highlight only, with no pointer cursor, because the cards aren't links. Sub-service lists sit at the bottom of each card, so they line up across a row. On phones, cards drop their padding and are separated by hairlines.
- **Live room clip:** 9:16 muted, looping videos with a 16px radius, each with a small dark "Live" pill naming the category. There are four in a row under the capability grid on desktop, and they swipe sideways on phones. Clips start 1s in (`#t=1`) to skip the white first frame.
- **Closing CTA:** a glass panel with the heading, one line of copy, the primary button ("Book a discovery call") and a ghost button ("Send an inquiry"). Right under the buttons sit two 14px lines: a reassurance line with the email as a green text link, and a proof line with a green dot ("Trusted by 100+ brands · ₱580M+ monthly GMV"). Each phrase is kept from breaking mid-way, so lines wrap only after the separator. No logo mark, since the nav and footer already carry the brand.
- **Contact links:** every "Book" action opens NEXPLAY's Google Calendar booking page in a new tab, with screen-reader text "(opens Google Calendar in a new tab)". Every "inquiry" action is a `mailto:` link to partnership@nexplayglobal.com with a pre-filled subject. Never link a call-to-action to the section it's already in.
- **Footer:** three columns on desktop (brand, page links, "Get in touch"), stacking on phones. The contact column lists the email, the booking link, the location and a row of social links (LinkedIn, Facebook, Instagram). These are 20px outlined icons in muted text inside 44px tap areas. On hover the icon turns green on a `surface` background. Each opens in a new tab and has a screen-reader label such as "NEXPLAY on LinkedIn (opens in a new tab)".
- **Partner logos:** clean vector logos only, shown in flat white at 60% opacity, so no brand's own colors compete with the green. Brand colors are not used: several (Casio navy, Philips blue) nearly disappear on black, and eight different colors would outshout the single green accent.
  - **Trusted-by strip:** 8 logos in `logos/strip/` (Xiaomi, Philips, Casio, Honor, SanDisk, Ajinomoto, Pocky, Funko), with white baked into each file. They sit in an even grid, 8 across on desktop and 4×2 below 1000px. Heights are tuned per logo (16–34px) so wide wordmarks and compact marks look equally weighted.
  - **Only logos drawn entirely as shapes.** A logo SVG that uses typed text with a web font renders in the wrong font when loaded as an image, so those can't be used.
  - **Never use logos traced from screenshots.** Traced edges smear, and small text turns into blobs. A text wordmark is better than a blurry logo.
  - **Keep cut-outs as cut-outs.** If a logo has letters knocked out of a shape (Xiaomi's "mi"), use an SVG mask so the letters stay see-through once the logo is white.
  - **Avoid logos inside a solid filled box** (Fibisco, Café Puro, Prestone, Clorox, Handyman, Pop Mart, Ricoa). In flat white they become blank blocks.
- **Live dot:** an 8px green circle that marks live status.
- **Signal divider:** a 1px line with the gradient fading to transparent at both ends, used before the closing CTA.

## Do's and Don'ts

- Do keep green to buttons, links, live states, focus rings and small icons.
- Do set headings in DM Sans 500 and body text in Inter 400.
- Do use the inner rim-light for depth instead of drop shadows.
- Do write in sentence case and keep section labels rare.
- Do show real figures in product visuals, and label them as illustrative where needed.
- Do use real live-room clips and, later, real photos of NEXPLAY's team and spaces. Real footage is the strongest proof that the operation exists.
- Do keep a labeled placeholder in any photo slot that doesn't have a real photo yet.
- Don't use bold (600+) anywhere.
- Don't fill large areas or backgrounds with green or the gradient.
- Don't add other accent hues, or red/yellow status colors. Show state with green versus muted gray.
- Don't use corner radii outside 5, 16, 24, 32 and full.
- Don't use images that look AI-generated or stock: no mirrored or cloned people, no garbled text on screens, no hyper-glossy "8K" lighting.
- Don't claim more than the evidence shows. Badges and subtitles must match the actual reviews, for example "5.0 from 3 partner reviews".
- Don't put text on photos, and don't tint photos green.
- Don't use bracketed uppercase labels, numbered lists for decoration or fake terminal text.
