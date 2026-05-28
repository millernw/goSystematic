# 02 — Design Direction

> Use this file when building any UI component, page layout, or visual element.
> Paste this alongside 00-master-prompt.md when starting a design-heavy build.

---

## Aesthetic Direction

- **Vibe keywords:** Bold, confident, editorial, systematic, anti-corporate
- **Overall tone:** Commanding and direct — this site should feel like it was built by the best marketer in the room, not a template agency
- **Light or dark theme:** Dark — near-black backgrounds throughout
- **Density:** Balanced — generous whitespace on desktop, purposeful on mobile; sections breathe but nothing feels empty

---

## Color Palette

| Role | Hex | Usage |
|------|-----|-------|
| Background | `#0A0A0A` | Main page background |
| Surface | `#141414` | Cards, panels, nav background |
| Surface elevated | `#1E1E1E` | Hover states, nested cards |
| Primary accent | `#B8FF47` | CTAs, highlights, active states, key callouts |
| Text primary | `#FFFFFF` | Headings, body |
| Text secondary | `#888888` | Captions, labels, secondary info |
| Border | `#2A2A2A` | Dividers, card outlines |
| Success | `#B8FF47` | Confirmations, positive states |
| Error | `#FF4444` | Warnings, error states |

> The neon green (`#B8FF47`) should be used sparingly — it's a signal color. Reserve it for:
> primary CTA buttons, key stat callouts, hover underlines on links, and section labels/eyebrows.

---

## Typography

- **Heading font:** Syne
  - Source: Google Fonts (`https://fonts.google.com/specimen/Syne`)
  - Weight: 800 for h1, 700 for h2, 600 for h3
  - Letter spacing: Tight (-0.02em to -0.03em on large sizes)
- **Body font:** Plus Jakarta Sans
  - Source: Google Fonts (`https://fonts.google.com/specimen/Plus+Jakarta+Sans`)
  - Weight: 400 regular, 500 medium, 600 semibold for labels/buttons
- **Mono font:** IBM Plex Mono (optional — for stats, labels, or code-like callouts)
  - Source: Google Fonts

**Type scale — large and dramatic:**

| Element | Desktop | Mobile |
|---------|---------|--------|
| H1 (hero) | 80–96px | 48px |
| H2 (section) | 56px | 36px |
| H3 (card/sub) | 32px | 24px |
| Body large | 20px | 18px |
| Body | 17px | 16px |
| Label/caption | 13px | 12px |

- **Line height:** 1.1 for headings / 1.65 for body
- **Uppercase use:** Section eyebrow labels (e.g. "OUR SERVICES", "THE PROBLEM") in Syne, 11–13px, letter-spacing: 0.15em

---

## Reference Direction

**What this site should feel like:**
A bold, dark-themed marketing/consulting site. Think editorial design meets performance marketing. Large type dominates the hero. The neon green accent creates energy without being garish — used only on CTAs and key callouts. The overall impression is: "this person knows exactly what they're doing." Not flashy — systematic.

**Inspiration sites:**

1. URL: https://www.furoweb.eu/
   What I like: Dramatic hero section. Contrasting font colors. Subtle entrance animations — text sliding in from the side. Parallax image effects. Animated background (but note: ours should be more restrained — theirs is too busy and distracting). Interesting use of color and image effects throughout.

2. URL: https://juanmora.co/
   What I like: Dramatic hero. Contrasting font colors. Text sliding in from the side on scroll/load. Parallax image effects. Same energy as furoweb.eu — bold and kinetic without being cluttered.

3. URL: https://www.fromanother.love/
   What I like: Animated background with interesting color use and image effects. Note: like furoweb.eu, the animation is a bit too busy — use this as inspiration for the *type* of effect, but dial it back significantly so it doesn't compete with the message.

4. URL: https://www.studioapply.com/
   What I like: Clean and focused on content. Well-organized hierarchy — the message never gets lost in the design. A strong example of restraint: the design serves the content, not the other way around.

5. URL: https://outfit.hellohello.is/
   What I like: Dramatic header with high contrast. Focused and clear. The design doesn't distract from the message or the calls to action — everything leads your eye where it should go.

6. URL: https://weareyellow.com/
   What I like: High contrast and clear messaging. Strong example of how bold design and readable communication can coexist.

**What to absolutely avoid:**
- Typical blue/purple gradient SaaS look
- Light gray backgrounds with colorful cards
- Generic stock photography
- Cluttered layouts with too many competing elements
- Any site that looks like it was built with a drag-and-drop template

---

## Layout & Spacing

- **Border radius:** Small-to-medium — 6px for cards, 4px for buttons, sharp on decorative elements
- **Shadow style:** No traditional box shadows — use subtle border (`1px solid #2A2A2A`) instead; occasional green glow (`0 0 20px rgba(184, 255, 71, 0.15)`) on primary CTAs
- **Grid system:** 12-column, max-width 1280px centered with 24px edge padding on mobile
- **Section padding:** Generous — 120px top/bottom on desktop, 80px on mobile
- **Max content width:** 1280px centered; text content capped at 680px for readability

---

## Animation & Motion

- **Animation level:** Subtle — purposeful, not decorative
- **Preferred animation style:** Fade up on scroll (elements enter from 20px below, opacity 0→1, duration 0.5s)
- **Hover states:** CTA buttons get a slight scale (1.02) + green glow; nav links get a neon green underline that slides in from left
- **Page load animation:** Logo/wordmark fades in, then hero text staggered in line by line (fast, ~100ms stagger)
- **Transition speed:** Standard 200–250ms ease-out for most; 400ms for page-level transitions

---

## Imagery & Media

- **Photography style:** No lifestyle photography. If photography is used, it must be high-contrast, editorial, or abstract. Preferred: product/work screenshots, abstract textures, or pure typographic compositions.
- **Illustration style:** None — rely on typography and color for visual impact
- **Icon set:** Lucide icons — minimal, consistent stroke weight; use sparingly
- **Video usage:** None at launch

---

## Section Eyebrow Labels

> Every major section should open with a small uppercase label in neon green above the headline. Examples:

- `THE PROBLEM`
- `WHAT WE DO`
- `HOW IT WORKS`
- `OUR WORK`
- `MEET NATHAN`
- `GET STARTED`

These set context and create visual rhythm across the page.

---

## What to Absolutely Avoid

- NO purple or blue gradients as backgrounds
- NO stock photos of people smiling at laptops
- NO Lorem Ipsum or placeholder text
- NO Inter, Roboto, or Arial fonts
- NO generic agency template look — this should feel designed and intentional
- NO white backgrounds — dark only throughout
- NO more than 2–3 uses of the neon green per section — it loses power if overused
