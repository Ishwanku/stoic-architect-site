# The Stoic Architect — Website

Single-page marketing site for **The Stoic Architect** — dual audience:

- **Users:** plain-language benefits, day-in-the-life, privacy FAQ  
- **Investors / diligence:** market wedge, maturity, defensibility, use of capital, tech stack  

Native Flutter (**Android + Windows**, not iOS) + optional self-hosted Go MILVIS. Offline-first.

Self-contained `index.html` (fonts, logo, styles inlined).

**Live:** https://ishwanku.github.io/stoic-architect-site/

## Status on this site (synced 2026-08)

Reflects **app v2.0 Phase 1** from [StoicArchitect-V2](https://github.com/Ishwanku/StoicArchitect-V2):

| Area | On site as |
|------|------------|
| First-launch onboarding wizard | Shipped |
| Daily OS (protocol, journal, sprints, glass UI) | Shipped |
| CI Android test APK (`stoic-dev-apk`) | Shipped (Phase 1 delivery) |
| Device QA / Play Store / crash reporting | Next (Phase 2) |
| Public cloud MILVIS + TLS | Later (Phase 3) |

Authoritative app docs: `stoic-docs/80-lifecycle/80.4-phase1-launch.md` and `80.5-future-roadmap.md` in the app repo.

## Page map

| Section | Audience | Content |
|---------|----------|---------|
| Hero | Both | Value prop, Phase 1 badge, stats, CTAs |
| Why | Both | Problem / opportunity |
| Product | Users + builders | Benefits, architecture, day journey + onboarding |
| Investor brief | Investors | Market, maturity (Phase 1 honest), moat, capital use |
| Status | Both | Shipped / next / later |
| Product pillars + screens | Both | Dock map + onboarding + Emperor |
| MILVIS / Privacy / Stack | Both | Trust + tech |
| FAQ + CTA | Both | Phase 1, APK how-to, funding |

## Preview

Open `index.html` in a browser. No build step.

## Deploy

Push the site repo branch configured for GitHub Pages.

© 2026 Ishwanku Saini. All rights reserved.
