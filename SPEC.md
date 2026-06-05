# BearingTech Redesign — Project Specification

## Overview
Redesign concept for bearingtech.com.au — an Australian industrial bearing supplier. The goal is a modern, professional static site demonstrating what their business could look like with a contemporary web presence.

## Original Site Analysis
- **Platform:** WordPress 5.7.2
- **Theme:** Custom "espresso" theme (2017–2024)
- **Plugins:** Slider Revolution 5.3, Contact Form 7, WooCommerce, All in One SEO, bbPress
- **Design:** Outdated, table-based layouts, old styling

## Content Extracted
Owner: Dwight Williams — 30+ years in bearing industry
Location: Unit 15 – 18/20 Naru Street, Chinderah NSW 2487
Phone: +61 2 6677 1438 / 0437 794 969
Services: Part number interchange, technical advice, SKF authorised supplier
Products: Industrial Equipment + General Equipment (90,000+ bearing types)
Gallery: 14 project categories (gearbox repair, conveyor drives, mining equipment etc.)

## Deliverables

### 1. index.html
- Single-page scrolling site
- Sections: Hero, About, Services, Products, Gallery, Contact, Footer
- Modern dark hero with grid overlay effect
- Scroll animations via IntersectionObserver
- Mobile-responsive hamburger menu

### 2. css/style.css
- ~500 lines, mobile-first responsive
- CSS variables for theming
- Inter font from Google Fonts
- Hover effects, transitions
- Grid-based layouts

### 3. SPEC.md
- This document

## Technical Notes
- Pure HTML/CSS/JS — no build step required
- GitHub Pages hosting (Hodl-Solo/bearingtech-redesign)
- No framework dependencies
- Fonts: Google Fonts (Inter)
- Icons: Emoji-based (lightweight)

## Design Decisions
- **Colour:** Deep navy primary (#1a56db), amber accent, dark backgrounds
- **Typography:** Inter — clean, modern, highly readable
- **Layout:** Section-based scrolling with visual variety (dark hero → light about → alt services → light products → alt gallery → light contact → dark footer)
- **Photos:** Represented as icon cards (actual photos not scraped due to complexity)

## Hosting
- GitHub Pages: https://hodl-solo.github.io/bearingtech-redesign/
- Repository: https://github.com/Hodl-Solo/bearingtech-redesign

## Workflow (This Service Offering)
1. Scrape existing site content
2. Build redesign (this step)
3. Record Loom video walkthrough
4. Pitch to client with live URL
5. Client pays for full implementation on their domain