# Welcome to my AI lab! 

This is where I stay hands-on with **how AI is changing software delivery**. I act as Program Manager, and Claude Code acts as the product, UX, engineering and infrastructure team. Every project below was built that way, following a method I've published as an open-source Claude Code skill: **[idea-to-launch](https://github.com/eugeniozamora/idea-to-launch)**.

## Projects

| Project | What it shows |
|---|---|
| [**Byrnit**](https://github.com/eugeniozamora/case-study-vent-journal-app)<br/>Privacy-first "vent it, burn it" journal | My first native Flutter app: led from market validation and brand to v1.1 live on Google Play worldwide, with iOS coming soon. There is no backend, so no user content leaves the device, and the database is encrypted with SQLCipher. 70+ automated tests gate each release. |
| [**Zymsia AI Coach**](https://github.com/eugeniozamora/case-study-ai-nutrition-coach)<br/>Privacy-first multi-agent coaching backend | Three specialist AI coaches behind an intent router. Health conversations live in a Redis session that deletes itself after 30 minutes and are never stored. One API is designed to serve B2C, B2B2C and B2B products, and analytics never include message content. |
| [**Zymsia Pro**](https://github.com/eugeniozamora/case-study-nutrition-saas)<br/>Multi-tenant SaaS for nutrition professionals | Many practices on one codebase and one database, with tenant identity carried in Firebase custom claims instead of request parameters. Patients sign in with magic links instead of passwords. |
| [**Zymsia Mobile**](https://github.com/eugeniozamora/case-study-mobile-migration)<br/>Migrating a shipped app's backend | A shipped Flutter PWA (web, not native) moved from session-based endpoints to a stateless API without a feature freeze. The new client layer shipped first, then ~400 lines of legacy code were removed once proven unused, with 75+ tests passing throughout. |

The three Zymsia studies are one product ecosystem seen from three angles: the AI backend, the professional SaaS platform, and the mobile client that migrated onto the new backend. Byrnit is the counterpoint, a product taken from "is this worth building?" to a live store release.

## How I work

- **Decisions written down.** Key architecture choices are recorded as ADRs next to the code, and a shared glossary keeps metrics meaning the same thing to engineers and stakeholders.
- **Thin vertical slices.** Each feature ships end to end with acceptance criteria written up front, one clean squash commit per user story.
- **CI as the gatekeeper.** Lint, type-check and tests block merges. Staging and production deploy automatically from separate branches.
- **Privacy by architecture, not by policy.** If data should not be kept, the system is built so that it cannot be kept.

## Get in touch

Open to senior permanent roles and to interim or fractional engagements.

**[Book a meeting](https://calendar.app.google/5FeUeC4X1VBYt2bU6)** · [eugeniozamora.com](https://eugeniozamora.com) · [LinkedIn](https://www.linkedin.com/in/eugeniozamora/) · [GitHub](https://github.com/eugeniozamora)

<sub>Each case study is a sanitized architectural write-up. Production source code and credentials stay private under IP and confidentiality obligations.</sub>
