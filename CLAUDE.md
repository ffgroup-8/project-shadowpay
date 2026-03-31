# PayNearMe — Project Context

## Client Overview
- **Client:** Project: ShadowPay *(working title — update when official name confirmed)*
- **Project Type:** Website / Web App
- **Agency:** Forefathers Group
- **Git Org:** ffgroup-8 | GitHub Pages
- **Tracker:** `index.html` at repo root → deployed via GitHub Pages
- **Status:** Active

## Project Goals
[Add 2–3 sentences describing what this project needs to achieve for PayNearMe]

## Key Docs (load on demand — use @ references, don't paste inline)
- Brand guidelines: @docs/brand-guidelines.pdf
- Content strategy: @docs/content-strategy.md
- Client brief / SOW: @docs/client-brief.md

## Tracker Rules (Non-Negotiable)
These rules come from `_Project Tracker Master` and apply to every tracker build:

1. Never remove progress already marked completed
2. Always include the chart-emoji favicon (SVG data URI)
3. Always include animated progress bar + rings chart script
4. Always update "Last updated" date on any change
5. Never nest content-created-box inside seo-box — they must always be siblings
6. Push automatically after changes — no confirmation needed:
   git add index.html && git commit -m "..." && git push

## Box Hierarchy (Section 3)
  content-section
    purpose paragraph (plain text, outside both boxes)
    seo-box (GREEN) — SEO/AEO metadata only
    content-created-box (BLUE) — all Module copy blocks

seo-box must be fully closed before content-created-box opens. Never nest.

## Status Pill Categories
Design / Dev / SEO / Content / Sanity / Content Created
States: not-started (circle) | in-progress | completed (checkmark)

## SEO Writing Standards
- Titles: pipe separator (never em dashes), max 60 chars
- Meta descriptions: no em dashes, max 155 chars
- Every page needs: SEO Title, Meta Description, Primary Keywords, Schema Type, AEO Targets
- Format as paragraphs with strong labels — never tables

## Content Writing Standard
Content inside content-created-box must be actual page copy — real headlines, body text, CTAs.
Not design annotations or layout specs.

## Pipeline Rule
Any new UI pattern or CSS improvement made here must also be applied to:
~/Desktop/Git Repo/_Project Tracker Master/index.html
And vice versa — always pull latest boilerplate before building.
