# 03 — Technical Specs

> Use this file when scaffolding the project, setting up integrations, or making architecture decisions.
> Paste this alongside 00-master-prompt.md at the start of any technical build session.

---

## Platform & Output

- **Platform:** GoHighLevel AI Studio (HighLevel's built-in vibe coder / website builder)
- **CSS approach:** Whatever GoHighLevel AI Studio outputs — inline styles or embedded CSS within the GHL builder
- **Framework note:** This is NOT a Next.js or standalone React project. All code lives inside GoHighLevel's platform.

---

## Hosting & Deployment

- **Hosting:** GoHighLevel (built-in hosting)
- **Domain:** goSystematic.com (connected to GoHighLevel)
- **CI/CD:** Not applicable — GHL handles publishing; changes go live via GHL's publish flow
- **Environment:** Static pages with GoHighLevel dynamic elements (forms, calendar, CRM tracking)

---

## GoHighLevel Integrations

> All integrations are native to GoHighLevel — no third-party accounts needed.

| Integration | Purpose | Notes |
|-------------|---------|-------|
| GHL Calendar | Discovery call booking | Embed GHL calendar widget on Contact page and in hero CTA modal or section |
| GHL Forms | Contact / inquiry forms | Use GHL native forms — all submissions flow into GHL CRM pipeline |
| GHL CRM | Lead management | All form submissions and call bookings tag contacts in GHL automatically |
| GHL Tracking | Analytics / attribution | Use GHL's built-in tracking and attribution for all form/calendar conversions |
| Marketing Audit Tool | Lead qualification / transitional CTA | External app (URL TBD) — link to it as a CTA throughout the site; placeholder for now |

---

## Forms & Data Collection

| Form | Fields | Where Data Goes | Notes |
|------|--------|----------------|-------|
| Discovery call booking | Via GHL calendar | GHL CRM — tagged "Discovery Call" | Calendar embed, not a manual form |
| Contact / general inquiry | Name, Email, Message, Business name | GHL CRM — tagged "Contact Inquiry" | Use GHL native form embed |
| Marketing audit entry | Email (minimum) | GHL CRM — tagged "Audit Lead" | Links to external audit app |

---

## Authentication

- **Auth needed:** No — public marketing site only; no login or protected pages

---

## CMS & Content Management

- **CMS:** GoHighLevel's built-in page editor
- **Who updates content:** Nathan Miller (developer-owner)
- **Blog:** Not in scope for launch — add in Phase 2 if needed
- **Localization:** English only

---

## Performance & SEO

- **SEO priority:** Important — marketing site needs to rank for local/niche terms
- **Core Web Vitals:** Best effort within GHL's platform constraints
- **Lighthouse target:** 80+ where possible
- **Image optimization:** Compress all images before uploading to GHL (use TinyPNG — target < 300kb per image)
- **Sitemap:** Yes — use GoHighLevel's built-in sitemap generation
- **Robots.txt:** Yes — GHL generates automatically
- **Structured data:** Organization schema on homepage, Service schema on services page

**Target SEO keywords (work into copy naturally):**
- "marketing systems for small businesses"
- "fractional CMO for small business"
- "done for you marketing"
- "marketing strategy small business [city if applicable]"
- "marketing consultant for small business"

---

## Browser & Device Support

- **Minimum browser support:** Modern only — last 2 versions of Chrome, Firefox, Safari, Edge
- **Mobile breakpoints:** Follow GoHighLevel's responsive system; ensure all sections look excellent at 375px, 768px, and 1280px+
- **Accessibility target:** WCAG AA best effort — sufficient color contrast (neon green `#B8FF47` on black `#0A0A0A` passes), keyboard navigable CTAs
- **Dark mode:** Dark only — no light mode toggle needed

---

## Known Constraints

- Build entirely within GoHighLevel AI Studio — do not suggest external hosting or deployment pipelines
- Calendar and forms must use GoHighLevel's native embeds — no Calendly, Typeform, or third-party form tools
- No backend server code — everything is handled by GoHighLevel's platform
- The marketing audit tool is external — link to it, do not attempt to rebuild it
- All tracking and analytics should go through GoHighLevel's built-in attribution system
- Keep pages fast — avoid heavy animations or large uncompressed images
