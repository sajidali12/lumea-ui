# Lumea — Project Progress

## What this project is
HTML website for **Lumea**, a UK LED light therapy mask brand. Pure HTML/CSS/JS — no framework, no build tools. Eventually moving to Shopify (Dawn theme). Client wants a luxury skincare aesthetic.

---

## Files

| File | Status | Notes |
|---|---|---|
| `index.html` | **FINAL — DO NOT TOUCH** | Main homepage, fully aligned with moodboard |
| `index-v2.html` | **In progress** | Silk'n-inspired redesign (see below) |
| `product.html` | Exists | Product detail page |
| `collection.html` | Exists | Shop/collection page |
| `lumea moodboard design.pdf` | Reference | Brand guidelines — fonts, colours, mood |
| `G11 LED Face Mask Main Information.pdf` | Reference | Product specs |

---

## Brand identity (from moodboard PDF)

**Logo:** "Lumea" italic serif + "LIGHT THERAPY" spaced caps below

**Colours (exact hex):**
- `#CB9C2C` — primary gold
- `#CDA032` — secondary gold
- `#25211E` — warm dark (text/backgrounds)
- `#FCEA66` — bright accent
- `#F1F2F2` — cream/near-white

**Fonts:**
- Cormorant Garamond (Google Fonts) — primary serif, display headings
- Montserrat (Google Fonts) — sans-serif, body, nav, UI

**Certifications (verified, safe to use):** CE, UKCA, RoHS, FCC, IEC 60601, ISO 13485, SGS
**Certifications removed (unverified):** FDA 510(k), EU-MDR — do NOT add these back

**Claims removed (not verifiable):** "clinically proven", "dermatologist approved", "FDA cleared" — do NOT add back

---

## Product: Lumea G11 (£249)
- 147 LED chips (90 face + 57 neck)
- 4 wavelengths: 415nm blue (acne), 590nm yellow (glow/redness), 633nm red (collagen), 850/1072nm NIR (deep repair)
- 6 modes: Repairing, Rejuvenation, Anti-Aging, Morning Skincare, Anti-Acne, Bedtime
- 5000mAh battery, Type-C USB, LCD controller
- Medical-grade silicone, 4D curved face + neck coverage
- 10Hz pulse, 3 brightness levels (50/75/100%)
- Free UK delivery, 30-day money-back, 1-year warranty

---

## index.html — what was done (complete, locked)

1. Hero text updated — shorter, clearer
2. Medical claims removed (FDA, "clinically proven", "dermatologist approved")
3. Wavelength benefits rewritten — clear, non-medical language
4. Copy shortened throughout
5. CTAs improved — "Buy Now — £249" primary
6. Trust signals added above buy button
7. Disclaimer made more visible
8. Mobile spacing fixed
9. Fake dermatologist review replaced with real customer testimonials
10. Moodboard alignment: Cormorant Garamond + Montserrat fonts, exact hex colours from PDF
11. Logo updated to "Lumea" + "LIGHT THERAPY" (not "Luxury Light Therapy")
12. Mood statement in footer

---

## index-v2.html — current state (in progress)

**Goal:** Exact structural copy of [silkn.eu](https://www.silkn.eu/be/en/) applied to Lumea brand — minimal text, graphics-first, clean white.

**Current structure (as of last session):**
1. Announcement bar — 3 items, cream background
2. Sticky white nav — logo left, links center, icons right
3. Full-width hero — left-aligned text, right image, one "Discover" CTA, stat chips at bottom
4. 4 wavelength product cards — Silk'n card format (image → colour dot → name → tagline → "Discover" link)
5. Dual banner tiles — Design / Results, side by side with image + 3 words + button
6. Full-width promo banner — minimal copy, buy CTA
7. Instagram/social strip — 5-photo grid
8. Newsletter — email input only
9. Dark footer — 4-column

**Design rules for v2 (Silk'n DNA):**
- White/off-white backgrounds everywhere except hero and footer
- Montserrat as primary reading font; Cormorant only for display moments
- Minimal text — graphics do the work
- "Discover" as the primary CTA text (like Silk'n)
- No long paragraphs, no spec tables, no tab systems on the homepage
- Gold (#CB9C2C) as accent only — not dominant

---

## What's next / possible next tasks

- [ ] Replace placeholder product images with actual Lumea product photography when available
- [ ] Finalise `product.html` — full product detail page with buy box, specs, reviews
- [ ] Finalise `collection.html` — shop grid
- [ ] Shopify migration — Dawn theme customisation
- [ ] Add real before/after photos to both pages when available

---

## Rules / preferences established

- `index.html` is locked — never edit it
- No medical claims without verification source
- No FDA 510(k) reference — it is not certified
- Keep copy short — client prefers graphics over text
- Reference silkn.eu for design inspiration on v2
- HTML validation: run `python3 -c "from html.parser import HTMLParser; ..."` after edits
