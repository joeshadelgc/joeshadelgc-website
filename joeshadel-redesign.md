# Joe Shadel General Contracting — Website Redesign

**Site:** joeshadelgeneralcontracting.com  
**Service Area:** Morris County, NJ  
**Aesthetic Direction:** Refined Craftsman Dark — navy/charcoal base, warm gold accents, Playfair Display typography  

---

## Current Site Audit

### 🚨 Critical Issues

| Issue | Detail |
|-------|--------|
| Google+ footer link | Google+ shut down in 2019. Signals an untouched site to any visitor. |
| Footer keyword stuffing | Wall of comma-separated SEO terms at page bottom. 2008-era black-hat tactic now penalized by Google. |
| Geographic mismatch | Footer references St. Petersburg, FL and Treasure Island — business is in Morris County, NJ. Appears copy/pasted from another site. |

### 🎨 Design & Visual Hierarchy

- H1 on every page reads "HOME IMPROVEMENT CONTRACTORS" — brand name should lead
- No hero section with headline + CTA — homepage drops directly into a photo grid with user instructions ("click on a shaded photo")
- Typography is flat and generic with no visual personality
- Nav slugs are SEO-stuffed (`/about-joe-shadel-general-contracting`) — look amateurish in browser tabs and when shared

### 📋 Content & Trust Signals

- License number and insurance status buried in an image alt tag — invisible to users
- Project photos are small and crammed into a table layout — work appears more impressive than the presentation suggests
- Most projects are dated 1988–2014 — recent work needs to be front and center
- "Make a Payment" competes visually in the primary nav with Services and Contact

### 📱 Mobile & Performance

- Table-based photo grid renders poorly on mobile
- Older Wix page structure is not mobile-first

### ✅ What to Keep

- Personal storytelling on the Services page is a genuine strength — Joe's candid voice should be amplified, not buried
- Project breadth is impressive: 7,000 sq ft oceanfront home, 10,000 sq ft custom build, beach house that survived Sandy
- 35 years of experience is headline-worthy — needs to be front and center

---

## Redesign Structure

### Sections

1. [Nav](#nav)
2. [Hero](#hero)
3. [Trust Bar](#trust-bar)
4. [About](#about)
5. [Services](#services)
6. [Projects](#projects)
7. [Testimonials](#testimonials)
8. [Contact](#contact)
9. [Footer](#footer)

---

### Nav

- Fixed/sticky with backdrop blur
- Logo: `Joe Shadel GC` — brand name first, always
- Links: About · Services · Projects · Reviews
- Primary CTA: **Free Estimate** (gold button, right-aligned)
- TODO: Add hamburger menu for mobile

---

### Hero

**Headline:** `35 Years. Zero Shortcuts.`

**Subhead:**  
> Custom homes, major renovations, and structural builds done right — the first time. Licensed & fully insured since 1988.

**CTAs:**
- Primary: `Get a Free Estimate` → #contact
- Secondary: `View Our Work` → #projects

**Stat callouts (right column):**
- `35+` Years in Business
- `10k` Sq Ft Custom Build Capacity
- `100%` Licensed & Fully Insured

**TODO:**
- [ ] Replace background gradient with full-bleed hero photo of flagship project
- [ ] Update stat numbers with verified figures

---

### Trust Bar

Tight horizontal strip directly below the hero. One line, four signals:

| Signal | Content |
|--------|---------|
| 🔒 NJ License | `#XXXXX` — **replace with real license number** |
| ✅ Fully Insured | Confirmed coverage |
| ⭐ Google Rating | 5-Star — **pull live from Google Business** |
| 🏠 Family-Owned | Since 1988 |

---

### About

**Layout:** Two-column — photo left, copy right

**Headline:** `Built Different Since Day One.`

**Copy direction:**
- Lead with Joe's personal origin story (the "disgruntled teenager" framing from the existing site — keep that voice)
- Anchor to two flagship credential moments: 7,000 sq ft oceanfront + Sandy survivor
- Close with the trust statement: *Joe shows up, Joe delivers.*

**Credential strip (below copy):**
- Founded: `1988`
- Primary Service Area: `Morris County, NJ`
- License: `NJ Lic. #XXXXX · Fully Insured`

**TODO:**
- [ ] Add job-site photo of Joe (candid preferred over posed)
- [ ] Fill in real license number

---

### Services

**Headline:** `No Job Too Complex.`

**Layout:** 3-column grid, 6 cards, numbered

| # | Service | Notes |
|---|---------|-------|
| 01 | Custom Home Construction | Ground-up, 1,500–10,000+ sq ft |
| 02 | Major Renovations | Whole-home guts, additions, structural |
| 03 | Kitchen & Bath | Full remodels |
| 04 | Roofing & Siding | Storm repair + new construction |
| 05 | Decks & Outdoor Structures | Pressure-treated, composite, hardwood |
| 06 | Storm & Flood Repair | Post-Sandy experience as a differentiator |

**TODO:**
- [ ] Confirm service list matches current offerings
- [ ] Add service-specific photos to each card (optional enhancement)

---

### Projects

**Headline:** `The Portfolio Speaks Louder.`

**Layout:** 12-column asymmetric grid

| Card | Size | Project |
|------|------|---------|
| Featured | Large (7 col × 2 row) | 7,000 Sq Ft Oceanfront Residence — Ocean County |
| Medium | 5 col | Full Gut Renovation, Colonial — Morris County |
| Medium | 5 col | 10,000 Sq Ft Custom Estate — Morris County |
| Small | 4 col | Chef's Kitchen Remodel — Chatham NJ |
| Small | 4 col | Walk-In Shower & Soaking Tub — Morris Plains |
| Small | 4 col | Multi-Level Composite Deck — Rockaway NJ |

**TODO:**
- [ ] Replace all placeholder divs with real project photos
- [ ] Add actual project metadata (year, sq ft, scope summary)
- [ ] Prioritize recent work (2018+) in the first 3 slots
- [ ] Consider a "View All Projects" page for full portfolio

---

### Testimonials

**Headline:** `35 Years of Happy Homeowners.`

**Layout:** Two-column — rating/score left, review cards right

**Star rating display:**
- ⭐⭐⭐⭐⭐ `5.0`
- `XX Reviews` — **pull real count from Google Business**

**Review cards (3 displayed):**
Each card includes: quote, client name/town, project type

**TODO:**
- [ ] Pull real reviews from Google Business Profile or existing site
- [ ] Add reviewer first name + town (full last names not required)
- [ ] Link to full Google reviews page

---

### Contact

**Headline:** `Ready to Build Something That Lasts?`

**Layout:** Two-column — contact info left, estimate form right

**Contact info fields:**
- Phone: `TODO: (xxx) xxx-xxxx`
- Email: `TODO: joe@joeshadel.com`
- Service Area: `Morris County, NJ & Surrounding`

**Estimate form fields:**
- First Name / Last Name
- Phone / Email
- Project Type
- Project Description (textarea)
- Submit: `Send Message — Get Your Free Estimate`

**TODO:**
- [ ] Wire form to email (Formspree, Netlify Forms, or direct mailto fallback)
- [ ] Add phone number and email address
- [ ] Optional: add "Preferred contact method" field

---

### Footer

**Elements:**
- Logo: `Joe Shadel General Contracting`
- Nav links: About · Services · Projects · Reviews · Contact
- Copyright + license: `© 2024 Joe Shadel General Contracting · NJ License #XXXXX · Morris County, NJ`

**Explicitly removed:**
- ❌ Google+ link
- ❌ Keyword-stuffed footer text
- ❌ St. Petersburg / Florida geographic references
- ❌ "Make a Payment" link (handle separately via direct invoice)

---

## Design Tokens

```css
--navy:    #0f1923
--charcoal:#1e2b35
--slate:   #2e3f4f
--gold:    #c9a84c
--gold-lt: #e8c97a
--cream:   #f5f0e8
--muted:   #8a9baa

--f-display: 'Playfair Display', Georgia, serif
--f-body:    'DM Sans', sans-serif
```

---

## Content TODO Checklist

- [ ] Real NJ contractor license number
- [ ] Phone number
- [ ] Email address
- [ ] Hero photo — flagship project, full-bleed
- [ ] Job-site photo of Joe (About section)
- [ ] 6 project photos with accurate metadata
- [ ] Real Google reviews (minimum 3, ideally 5)
- [ ] Live Google review count and rating
- [ ] Confirm and finalize services list
- [ ] Form backend (Formspree / Netlify / mailto)
- [ ] Mobile hamburger nav
- [ ] Google Analytics 4 tag
- [ ] Google Business Profile linked/verified
- [ ] favicon + Open Graph social preview image

---

## SEO Notes

- Title tag: `Joe Shadel General Contracting | Morris County NJ Custom Builder`
- Meta description: `35+ years building custom homes and major renovations across Morris County, NJ. Licensed, fully insured. Zero shortcuts.`
- Primary keyword targets: `general contractor Morris County NJ`, `custom home builder NJ`, `home renovation Morris County`
- Remove all keyword-stuffed content from footer
- Ensure all images have descriptive alt text (project type + location format)
- Add LocalBusiness structured data (schema.org) with correct NJ address and service area
