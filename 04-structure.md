# 04 — Site Structure & Layout

> Use this file when building navigation, page layouts, or any structural scaffolding.
> Paste this alongside 00-master-prompt.md when starting a new page or layout session.

---

## Site Map

| Page | Route | Priority | Notes |
|------|-------|----------|-------|
| Home | `/` | P1 | Main landing page — hero, problem, services overview, social proof, dual CTA |
| Services | `/services` | P1 | Detail all three service offerings with process overview |
| About | `/about` | P1 | Nathan's story, credibility, philosophy |
| Work | `/work` | P1 | Case studies placeholder — structure now, populate post-launch |
| Contact | `/contact` | P1 | GHL calendar embed + contact form fallback |
| Privacy Policy | `/privacy` | P1 | Legal — simple, standard text |
| Terms of Service | `/terms` | P1 | Legal — simple, standard text |
| Blog | `/blog` | P3 | Not at launch — add when content strategy is ready |

---

## Navigation

**Header nav:**
- **Style:** Sticky top bar — solid dark background `#0A0A0A` with subtle bottom border `1px solid #2A2A2A`
- **Logo position:** Left — wordmark "Systematic Marketing" in Syne Bold
- **Nav links:** Services | About | Work | Contact
- **CTA in nav:** Yes — "Book a Call" button in neon green `#B8FF47` text on dark surface, or filled neon green with black text
- **Mobile nav:** Full-screen overlay — hamburger icon opens a centered link list on dark background
- **Transparent on hero?** No — always solid; avoids contrast issues on dark hero backgrounds

**Footer nav:**
- **Columns:** 3 columns
- **Column 1 — Navigate:** Services, About, Work, Contact
- **Column 2 — Work Together:** Book a Discovery Call, Get Your Free Marketing Audit
- **Column 3 — Legal:** Privacy Policy, Terms of Service
- **Social icons:** LinkedIn (primary) — add others when accounts are active
- **Newsletter in footer:** No
- **Footer bottom bar:** "© 2025 Systematic Marketing. All rights reserved." + wordmark left, legal links right

---

## Homepage Section Order

> Every section listed in order. Build these one at a time.

1. **Header / Nav**
   - Layout: Sticky top bar, logo left, links center-right, "Book a Call" CTA button far right
   - Goal: Persistent navigation and conversion point throughout the page

2. **Hero**
   - Layout: Full-width, dark background, left-aligned headline (large, multi-line), subheadline below, two CTA buttons side by side (primary: filled neon green; secondary: outlined/ghost). No image — typography is the visual.
   - Goal: State the problem, the positioning, and drive to both CTAs within 5 seconds of landing

3. **Problem Bar / Credibility Statement**
   - Layout: Full-width dark band with a bold centered statement — e.g., "Most small business marketing fails for the same reason: there's no system behind it." — with a subtle divider above and below
   - Goal: Agitate the pain point and create a moment of recognition before explaining the solution

4. **Services Overview**
   - Layout: 3-column card grid on desktop (single column mobile). Each card: service name, 1-line hook, 2-sentence description, and a ghost "Learn more →" link. Cards on dark surface `#141414` with `1px solid #2A2A2A` border.
   - Goal: Communicate the three offerings clearly and help visitors self-identify

5. **How It Works**
   - Layout: 3-step horizontal row on desktop (stacked on mobile). Each step: number in neon green, title, short description. Clean and minimal.
   - Goal: Reduce friction — show the process is simple: Audit → Strategy → Execution

6. **Transitional CTA — Marketing Audit**
   - Layout: Full-width section, centered. Headline: "Not Ready to Book Yet?" Subtext, then the audit CTA button.
   - Goal: Capture visitors who aren't ready to commit to a call — route them to the audit for qualification

7. **Social Proof / Results**
   - Layout: Stats bar (3 numbers with labels) above testimonial cards. 3 testimonial cards on desktop (single column mobile). Cards on dark surface with a subtle green left border accent.
   - Goal: Build trust with specific results and real client voices

8. **About / Nathan Teaser**
   - Layout: 2-column on desktop — left: bold headline + 2–3 sentences about Nathan + "Meet Nathan →" link. Right: photo or typographic element.
   - Goal: Put a name and face behind the business; build personal trust

9. **Primary CTA Section**
   - Layout: Full-width band, large centered headline ("Ready to Build a Marketing System That Works?"), one-sentence subtext, single neon green CTA button. Minimal — no distractions.
   - Goal: Final conversion push before the footer

10. **Footer**
    - Layout: 3-column nav links, bottom bar with copyright
    - Goal: Navigation, legal, and final brand impression

---

## Services Page Section Order

1. **Page Hero** — Short hero: "What We Do" eyebrow label, bold headline, 2-sentence intro
2. **Service 1: Business & Marketing Strategy** — Full section with detail, what's included, who it's for
3. **Service 2: Custom Marketing Systems Design** — Full section with detail, what's included, who it's for
4. **Service 3: Ongoing Marketing Services** — Full section with detail, what's included, who it's for
5. **How Engagements Work** — Simple 3-step process (Discovery Call → Proposal → Kickoff)
6. **CTA Section** — "Ready to get started?" → Book a Discovery Call

---

## About Page Section Order

1. **Page Hero** — Short hero: "Meet Nathan Miller" or "Why Systematic Marketing Exists"
2. **The Problem Nathan Kept Seeing** — Narrative section: what he observed across small businesses, agencies, and in-house teams
3. **Nathan's Background** — Credentials, experience, what makes his perspective unique
4. **The Systematic Approach** — The philosophy: systems over campaigns, strategy before tactics
5. **CTA** — Book a discovery call or take the marketing audit

---

## Work Page Section Order

1. **Page Hero** — "Our Work" with honest subtext that case studies are being added
2. **Case Study Cards (placeholder structure)** — Build 3 card slots; each: industry, challenge, result. Mark clearly as placeholders.
3. **CTA** — Book a call to discuss your specific situation

---

## Component Library

**Navigation:**
- [x] Top navigation bar (desktop) — sticky, dark, wordmark + links + CTA button
- [x] Mobile hamburger menu — full-screen overlay
- [x] Footer — 3-column + bottom bar

**Content:**
- [x] Hero section — typographic, no image, dual CTA
- [x] Problem statement band — full-width callout
- [x] Service card — dark surface, border, title, hook, description, link
- [x] How it works — 3-step numbered row
- [x] Stats bar — 3 numbers with labels
- [x] Testimonial card — dark surface, green left border, quote, name, context
- [x] About teaser — 2-column text + visual
- [x] Case study card — industry, challenge, result
- [x] CTA section / band — full-width, centered, single button

**Form & Booking:**
- [x] GHL calendar embed (primary booking CTA)
- [x] GHL contact form embed
- [x] Marketing audit CTA button (external link)

**UI Primitives:**
- [x] Primary button — filled `#B8FF47` with black text, 4px radius, 500ms hover glow
- [x] Secondary button — outlined (white border, white text), same sizing
- [x] Ghost/text button — no border, neon green text with arrow
- [x] Section eyebrow label — all-caps, `#B8FF47`, Syne or Plus Jakarta Sans, 11–13px, tracked wide
- [x] Divider — `1px solid #2A2A2A`

**Page-specific:**
- [x] 404 page — on-brand, dark, with link back to home
- [ ] Blog post card — Phase 2
- [ ] Blog post layout — Phase 2

---

## Responsive Behavior

| Section | Mobile (< 768px) | Tablet (768–1024px) | Desktop (> 1024px) |
|---------|------------------|---------------------|---------------------|
| Hero | Stacked, full width, headline 48px | Stacked or left-aligned, headline 60px | Left-aligned, headline 80–96px |
| Services | 1 column, cards stacked | 2 columns | 3 columns |
| How It Works | Stacked steps, numbered vertically | 3-column row | 3-column row |
| Social Proof | Stats stacked, 1 testimonial | Stats row, 2 testimonials | Stats row, 3 testimonials |
| About Teaser | 1 column, text then visual | 2 columns | 2 columns |
| Footer | Stacked links, 1 column | 2 columns | 3 columns + bottom bar |
| Nav | Hamburger → full-screen overlay | Hamburger or compressed links | Full nav bar |

---

## Interaction Patterns

- **Scroll behavior:** Smooth scroll
- **Sticky elements:** Nav only
- **Modal triggers:** Optional — "Book a Call" CTA can open a GHL calendar modal overlay instead of navigating to /contact
- **Carousel/slider:** Testimonials — manual swipe on mobile, static grid on desktop
- **Accordion behavior:** Not used at launch
- **Back to top button:** No — not needed on a well-structured single-page scroll
- **CTA hover:** Primary button — scale(1.02) + subtle neon green box-shadow glow (200ms ease)

---

## Whitespace & Density

- **Section vertical padding:** Generous — 120px desktop, 80px tablet, 64px mobile
- **Card internal padding:** Standard — 28–32px
- **Line height (body):** Open — 1.65
- **Overall feel:** Balanced — sections have room to breathe, but nothing feels like it's hiding emptiness
