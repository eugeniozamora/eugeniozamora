# Eugenio Zamora — Fractional Engineering Manager / Technical Consultant

I help founders and small teams ship production systems when they need senior engineering judgment but not a full-time hire. That covers multi-tenant SaaS platforms, AI-powered backends and cross-platform mobile apps, from the first architecture decision to the release running in production. It also covers the delivery process that gets them there.

## What I do

- **AI-powered backends**: multi-agent LLM systems (Anthropic Claude) with privacy built into the architecture, and cost and latency measured on every AI turn
- **Multi-tenant SaaS**: tenant isolation enforced at the token level, B2B2C product design, one backend serving several products
- **Mobile apps**: Flutter from concept to store release, local-first and encrypted when privacy is the product
- **Legacy migrations**: replacing a live system's foundation incrementally, with tests and a written paper trail instead of a big-bang rewrite
- **Delivery leadership**: epics → user stories with acceptance criteria → squash-merged PRs, CI gates, and Architecture Decision Records so the reasoning outlives the people who made it

## Case studies

| Project | My role | What it shows |
|---|---|---|
| [**Zymsia AI Coach**](https://github.com/eugeniozamora/case-study-ai-nutrition-coach)<br/>Privacy-first multi-agent coaching platform | Solutions Architect & Lead Backend Engineer | Three specialist AI coaches behind an intent router. Health conversations live in a Redis session that deletes itself after 30 minutes and are never stored. One API serves B2C, B2B2C and B2B products, and clinics get analytics without ever seeing message content. |
| [**Zymsia Pro**](https://github.com/eugeniozamora/case-study-nutrition-saas)<br/>Multi-tenant SaaS for nutrition professionals | Architecture & full-stack delivery | Many practices on one codebase and one database, with tenant identity carried in Firebase custom claims instead of request parameters. Patients sign in with magic links instead of passwords. |
| [**Zymsia Mobile**](https://github.com/eugeniozamora/case-study-mobile-migration)<br/>Migrating a live app's backend | Migration lead | A live Flutter app moved from session-based endpoints to a stateless API without a feature freeze. The new client layer shipped first, then ~400 lines of legacy code were removed once proven unused, with 75+ tests passing throughout. |
| [**Byrnit**](https://github.com/eugeniozamora/case-study-vent-journal-app)<br/>Privacy-first "vent it, burn it" journal | Product Owner & Solution Architect | Solo-led from market validation and brand to v1.1 live on Google Play worldwide. There is no backend, so no user content leaves the device, and the database is encrypted with SQLCipher. 70+ automated tests gate each release. |

The three Zymsia studies are one product ecosystem seen from three angles: the AI backend, the professional SaaS platform, and the mobile client that migrated onto the new backend. Byrnit is the counterpoint, a product taken from "is this worth building?" to a live store release.

## How I work

- **Decisions written down.** Key architecture choices are recorded as ADRs next to the code, and a shared glossary keeps metrics meaning the same thing to engineers and stakeholders.
- **Thin vertical slices.** Each feature ships end to end with acceptance criteria written up front, one clean squash commit per user story.
- **CI as the gatekeeper.** Lint, type-check and tests block merges. Staging and production deploy automatically from separate branches.
- **Privacy by architecture, not by policy.** If data should not be kept, the system is built so that it cannot be kept.

## Stack

`TypeScript` `Next.js` `Python` `FastAPI` `Flutter/Dart` `Riverpod` `Firebase` `Redis` `PostgreSQL` `TimescaleDB` `SQLCipher` `Docker` `GitHub Actions` `Codemagic` `Vercel` `Sentry` `Anthropic Claude API`

## Get in touch

Open to fractional and interim engineering management engagements and focused technical consulting.

**[Book a meeting](https://calendar.app.google/5FeUeC4X1VBYt2bU6)** · [eugeniozamora.com](https://eugeniozamora.com) · [LinkedIn](https://www.linkedin.com/in/eugeniozamora/) · [GitHub](https://github.com/eugeniozamora)

<sub>Each case study is a sanitized architectural write-up. Production source code, client data and credentials stay private under IP and confidentiality obligations.</sub>
