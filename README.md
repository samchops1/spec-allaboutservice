# All About Service LLC — spec-site preview

- **Suggested slug:** `allaboutservice`
- **Target host (not live, do not claim it is):** allaboutservice.capitalreconsulting.com
- **Current public site:** https://allaboutservicellc.godaddysites.com/
- **Site path:** `/workspace/previews/allaboutservice/index.html`
- **One-line note (Outreach):** Replaced the GoDaddy Website Builder — stock hero, cookie bar, “Powered by GoDaddy” — with a Denver/Boulder family-ledger site: 35+ years, licensed & insured, we guarantee our work, click-to-call (720) 755-6656.

This folder is a static preview only. Do not deploy. Do not treat the target host as live.

## What changed vs their current site

Stripped the GoDaddy Website Builder chrome, cookie banner, reCAPTCHA quote form, and stock isteam photos (99235 / 5919 / 96451). Rebuilt a mobile-first four-page shop as a family ledger: cobalt `#003ca8` and flame `#f0480c` from their live orange-blue logo, ruled cream paper, Syne + Newsreader + IBM Plex Mono, a sticky call/email dock on phones, and type+SVG instead of stock photography.

## Facts used (with sources)

| Fact | Source |
| --- | --- |
| Brand **ALL ABOUT SERVICE LLC** / **All About Service LLC** | Homepage title, footer, contact block |
| **ALL ABOUT SERVICE Residential Remodeling Commercial Construction Services** | Homepage H1 (repeated) |
| Phone **(720) 755-6656** | Homepage hero and contact |
| **DENVER, BOULDER, & SURROUNDING AREAS** | Homepage hero |
| **Bathroom, Kitchen, Flooring, Tile, Sprinklers, Interior Paint & Finishing** | Homepage hero |
| **Family-owned & operated for 35+ years** | Homepage welcome block |
| Welcome: family-owned GC, 35+ years, construction / residential and commercial remodeling; approachable and dependable; remodel, new build, or renovation; “Let us be your trusted partner in construction!” | Homepage “DEPENDABLE SERVICE” |
| **~Licensed & Insured~** | Homepage |
| **COMMITMENT TO QUALITY** — “we guarantee our work” so the project is in good hands | Homepage |
| FAQ contact line: text, call or email **(720) 755-6656** or **AllAboutServiceColorado@gmail.com** | Homepage FAQ intro |
| Service list (FAQ): general building / general construction; home additional construction; renovations & remodeling; home repairs; basement, bathroom, kitchen remodeling; commercial projects; deck; erosion control; exterior structural repairs; fan install & repair; water fixture repair & install; flooring install and repair; interior finishing; interior structural repairs; paint indoors; plumbing fixture repair & install; irrigation & sprinkler install & maintenance; tile install and replacement; porch; refurbishment; remodeling; TV mounting; waterproofing | FAQ “What types of construction services…” |
| Areas: Louisville, Broomfield, Thornton, Westminster, Englewood, Highlands Ranch, Fort Collins, Northglenn, Brighton, Lakewood, Golden, Littleton, Aurora, Superior — plus Denver & Boulder | FAQ “What geographic areas do you service?” |
| Licensed and insured “to ensure compliance and protect my clients” — preview uses we/us: protect our clients | FAQ “Are you licensed and insured?” |
| Contact: “Tell us about your project!” Free quote; email, call or text to arrange a visit | Contact block |
| Email **AllAboutServiceColorado@gmail.com** (visible text + mailto) | FAQ and Contact |
| Copyright © **2024** ALL ABOUT SERVICE LLC | Footer |
| Logo orange **#f0480c** / blue **#003ca8** (theme-color `#0047AB`) | `AllAboutServiceLogo-OrangeBlue` on the live site |

## Facts deliberately omitted

- **Owner name** — not printed on the live page. Not invented. No founder in JSON-LD.
- **Street address** — not on the live page. City/region only (Denver, CO).
- **Hours** — the GoDaddy widget showed “Hours / Today Closed” with no published weekly schedule. Preview does not invent hours.
- **Stock photography** — isteam stock 99235 (hero), 5919, 96451. Not kept. Type+SVG ledger mark instead.
- **GoDaddy cookie banner**, “Powered by GoDaddy”, reCAPTCHA / Google Privacy Policy chrome.
- **CDOS / OpenGov extras** (registered agent, Northglenn street, entity dates) — not printed on the live site.
- **Any claim this preview is live** at allaboutservice.capitalreconsulting.com.

## Pages

- `index.html` — family-ledger hero, six published trades, guarantee, city list, click-to-call
- `services.html` — hero trades plus the full FAQ menu, three-step free-quote path
- `about.html` — 35+ years, dependable service, licensed & insured, we guarantee our work
- `contact.html` — tel, mailto, estimate form (mailto draft)

Forms open a mail draft to AllAboutServiceColorado@gmail.com. They do not post to GoDaddy.

## Images

No live-site job photo. Hero uses `assets/ledger.svg` (custom type+SVG ledger, bathroom/kitchen line art, 35+ stamp). Logo is a fresh SVG shop-ledger mark in their cobalt and flame, plus tiny favicon / apple-touch PNGs. No file over 200KB.

## JSON-LD

`GeneralContractor` on the homepage only, verified fields: name, telephone, email, live URL, Denver CO, areaServed (published cities), description, the SVG mark. No founder, no openingHours, no aggregateRating, no street, no invented geo.

## Blockers

- No owner name on the live page.
- No street address or published weekly hours.
- No reviews on the live page.
- Live images are GoDaddy stock, not documented job photos.
