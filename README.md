# Hazy Sun Foundation

React + TypeScript + Vite + Tailwind CSS. Black-background editorial website.

## Run

`npm run dev` starts the local preview. `npm run build` type-checks and produces `dist/`. `npm run preview` previews that production build.

## Pages

Home, Programs, Films, Impact, and Get involved use hash navigation, supporting direct links and browser history without server rewrite rules. The program disclosures use native keyboard-accessible details elements. The site includes a mobile menu, focus indicators, a skip link, and reduced-motion styles.

## Content source and launch needs

Content is based on the supplied Hazy Sun Foundation 2.pdf. The source describes a proposed organization and program framework; it does not establish tax-exempt approval, operational programs, releases, partnerships, or achieved results. No such claims have been added. Do not enable donations or assert deductibility without verified details.

Before public launch, supply a verified contact address, confirmed participation opportunities, cleared documentary photographs/film materials, and any verified program results. Current calls to action navigate to informational pages; no enrollment or donation backend is connected.

The current illustrative image is downloaded from https://images.unsplash.com/photo-1517486808906-6ca8b3f04846 and is explicitly identified as not foundation programming. Replace it with approved foundation photography when available. Original starter assets remain untouched in src/assets.

## Initial audit

The original App.tsx rendered an empty main element. Tailwind was already configured. The only existing raster asset was a purple framework illustration, unsuitable for the requested visual direction. No working forms, film catalog, payment system, or routes were present to preserve.

## Story-led revision

The opening now uses full-screen, monochrome film imagery and a manual three-story selector, informed by the visual hierarchy of https://knightfoundation.org/. It does not autoplay or copy Knight content.

Behind the Joy is featured based on https://www.behindthejoy.com/ (reviewed October 29, 2026). Its synopsis and Jamal Smart's director credit are sourced there. Screening CTA: https://forms.wix.com/r/7300956545964049380. Film-team activity is not claimed as foundation-funded work. No award counts, medical statistics, or partnership claims are reproduced.

Official still sources:
- https://static.wixstatic.com/media/8f7cf0_355675d64baa4ffbb07dc16481fa4355~mv2.png
- https://static.wixstatic.com/media/8f7cf0_b242f920d5484b1ebbc78c57d803f92d~mv2.png

Optimized WebP copies are served locally. Confirm permission to reuse film promotional imagery before public launch. The earlier stock photo remains in the assets but is no longer displayed. The home page now includes all eight program pillars and the document's four named maternal/family-health formats, clearly marked as proposed.

## Foundation-depth revision

Added eight deep-linked program pages (`#programs/<slug>`), a program directory, Who we are, and Support. Each program describes why it matters, the approach, planned activities, care requirements, and support priorities. The Impact page now explains the public-benefit planning sequence. The Support page includes funding priorities, giving-status FAQs, and a downloadable plain-text support brief.

Knight's Journalism, Community Impact, and Arts pages informed the editorial hierarchy (purpose, approach, priorities, related action); no Knight copy or impact claims were reused. All foundation-specific programming remains grounded in the supplied framework. The user confirmed Stripe is not ready, so online giving is explicitly coming soon. No payments or pledges are collected. Connect a verified donation destination only when provided.
