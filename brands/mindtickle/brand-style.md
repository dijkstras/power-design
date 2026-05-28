---
brand: Mindtickle
slug: mindtickle
website: https://www.mindtickle.com
extracted_via: manual
---

---
version: alpha
name: Mindtickle
description: "A high-energy enterprise SaaS canvas that runs two distinct modes: a light white surface for product sections and a deep dark-to-vivid-purple gradient hero for top-of-page drama. The primary CTA is a warm orange→yellow gradient pill (#FE5000 → #F1B434) that reads as kinetic and optimistic. Headlines are Montserrat Light (300) at 64–80px for hero display — thin strokes on a dark field create visual tension — while section-level headings snap to Montserrat SemiBold (600). Body copy lives in Inter. Border radii lean heavily pill-shaped: CTAs are fully pill-rounded, cards use 16–24px corners. The system reads as: enterprise-grade ambition communicated with bold colour, metric-driven proof, and an empowering motivational voice."

colors:
  orange: "#FE5000"
  orange-light: "#F1B434"
  purple: "#5600F1"
  night: "#16003F"
  white: "#FFFFFF"
  ink: "#15191F"
  ink-muted: "#4B5563"
  ink-subtle: "#6B7280"
  canvas: "#FFFFFF"
  surface-1: "#FFFFFF"
  surface-2: "#F5F4FB"
  dark-canvas: "#16003F"
  dark-surface-1: "#1F0A52"
  dark-surface-2: "#2B1269"
  dark-ink: "#FFFFFF"
  dark-ink-muted: "#9D8EC8"
  dark-ink-subtle: "#6B5EA8"
  hairline: "#E3E1EE"
  hairline-dark: "#3D1E7A"
  semantic-error: "#CE0F69"
  semantic-info: "#0093B2"
  semantic-warning: "#F1B434"
  semantic-success: "#0093B2"

gradients:
  hero-bg: "linear-gradient(135deg, #16003F 0%, #5600F1 100%)"
  cta-button: "linear-gradient(90deg, #FE5000 0%, #F1B434 100%)"
  cta-button-hover: "linear-gradient(90deg, #E54600 0%, #D9A020 100%)"
  section-dark: "linear-gradient(180deg, #16003F 0%, #5600F1 100%)"

typography:
  display-xl:
    fontFamily: Montserrat
    fontSize: 80px
    fontWeight: 300
    lineHeight: 1.05
    letterSpacing: -2.5px
  display-lg:
    fontFamily: Montserrat
    fontSize: 64px
    fontWeight: 300
    lineHeight: 1.08
    letterSpacing: -1.8px
  display-md:
    fontFamily: Montserrat
    fontSize: 48px
    fontWeight: 600
    lineHeight: 1.15
    letterSpacing: -0.8px
  headline:
    fontFamily: Montserrat
    fontSize: 32px
    fontWeight: 600
    lineHeight: 1.20
    letterSpacing: -0.4px
  card-title:
    fontFamily: Montserrat
    fontSize: 24px
    fontWeight: 600
    lineHeight: 1.25
    letterSpacing: -0.2px
  subhead:
    fontFamily: Inter
    fontSize: 20px
    fontWeight: 400
    lineHeight: 1.40
    letterSpacing: 0
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: 400
    lineHeight: 1.55
    letterSpacing: 0
  body:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: 400
    lineHeight: 1.60
    letterSpacing: 0
  body-sm:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: 400
    lineHeight: 1.55
    letterSpacing: 0
  caption:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: 400
    lineHeight: 1.40
    letterSpacing: 0
  button:
    fontFamily: Inter
    fontSize: 15px
    fontWeight: 600
    lineHeight: 1.20
    letterSpacing: 0
  eyebrow:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: 600
    lineHeight: 1.30
    letterSpacing: 0.8px
  label:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: 500
    lineHeight: 1.30
    letterSpacing: 0

rounded:
  xs: 4px
  sm: 8px
  md: 12px
  lg: 16px
  xl: 24px
  xxl: 32px
  pill: 9999px
  full: 9999px

spacing:
  xxs: 4px
  xs: 8px
  sm: 12px
  md: 16px
  lg: 24px
  xl: 32px
  xxl: 48px
  section: 96px

shadows:
  card: "0 2px 16px 0 rgba(22, 0, 63, 0.08)"
  card-hover: "0 6px 32px 0 rgba(22, 0, 63, 0.14)"
  modal: "0 16px 64px 0 rgba(22, 0, 63, 0.20)"

components:
  button-primary:
    background: "{gradients.cta-button}"
    textColor: "{colors.white}"
    typography: "{typography.button}"
    rounded: "{rounded.pill}"
    padding: 12px 28px
  button-primary-hover:
    background: "{gradients.cta-button-hover}"
    textColor: "{colors.white}"
    typography: "{typography.button}"
    rounded: "{rounded.pill}"
    padding: 12px 28px
  button-secondary:
    backgroundColor: "transparent"
    border: "1.5px solid {colors.orange}"
    textColor: "{colors.orange}"
    typography: "{typography.button}"
    rounded: "{rounded.pill}"
    padding: 12px 28px
  button-secondary-dark:
    backgroundColor: "transparent"
    border: "1.5px solid {colors.white}"
    textColor: "{colors.white}"
    typography: "{typography.button}"
    rounded: "{rounded.pill}"
    padding: 12px 28px
  button-ghost:
    backgroundColor: "transparent"
    textColor: "{colors.ink}"
    typography: "{typography.button}"
    rounded: "{rounded.pill}"
    padding: 12px 28px
  button-ghost-dark:
    backgroundColor: "transparent"
    textColor: "{colors.dark-ink}"
    typography: "{typography.button}"
    rounded: "{rounded.pill}"
    padding: 12px 28px
  card-light:
    backgroundColor: "{colors.surface-1}"
    textColor: "{colors.ink}"
    border: "1px solid {colors.hairline}"
    typography: "{typography.body}"
    rounded: "{rounded.lg}"
    padding: 24px
    shadow: "{shadows.card}"
  card-dark:
    backgroundColor: "{colors.dark-surface-1}"
    textColor: "{colors.dark-ink}"
    border: "1px solid {colors.hairline-dark}"
    typography: "{typography.body}"
    rounded: "{rounded.lg}"
    padding: 24px
  feature-card:
    backgroundColor: "{colors.surface-2}"
    textColor: "{colors.ink}"
    border: "1px solid {colors.hairline}"
    typography: "{typography.body}"
    rounded: "{rounded.xl}"
    padding: 32px
  feature-card-dark:
    backgroundColor: "{colors.dark-surface-1}"
    textColor: "{colors.dark-ink}"
    border: "1px solid {colors.hairline-dark}"
    typography: "{typography.body}"
    rounded: "{rounded.xl}"
    padding: 32px
  testimonial-card:
    backgroundColor: "{colors.surface-2}"
    textColor: "{colors.ink}"
    border: "1px solid {colors.hairline}"
    typography: "{typography.body-lg}"
    rounded: "{rounded.xl}"
    padding: 32px
  stat-card:
    backgroundColor: "{colors.dark-surface-1}"
    textColor: "{colors.dark-ink}"
    border: "1px solid {colors.hairline-dark}"
    typography: "{typography.body}"
    rounded: "{rounded.xl}"
    padding: 32px
  pricing-card:
    backgroundColor: "{colors.surface-1}"
    textColor: "{colors.ink}"
    border: "1px solid {colors.hairline}"
    typography: "{typography.body}"
    rounded: "{rounded.xl}"
    padding: 32px
    shadow: "{shadows.card}"
  pricing-card-featured:
    background: "{gradients.hero-bg}"
    textColor: "{colors.dark-ink}"
    border: "none"
    typography: "{typography.body}"
    rounded: "{rounded.xl}"
    padding: 32px
    shadow: "{shadows.modal}"
  cta-banner-dark:
    background: "{gradients.hero-bg}"
    textColor: "{colors.dark-ink}"
    border: "none"
    typography: "{typography.headline}"
    rounded: "{rounded.xxl}"
    padding: 64px 48px
  cta-banner-light:
    backgroundColor: "{colors.surface-2}"
    textColor: "{colors.ink}"
    border: "1px solid {colors.hairline}"
    typography: "{typography.headline}"
    rounded: "{rounded.xxl}"
    padding: 64px 48px
  badge:
    backgroundColor: "rgba(86, 0, 241, 0.10)"
    textColor: "{colors.purple}"
    typography: "{typography.label}"
    rounded: "{rounded.pill}"
    padding: 4px 12px
  badge-orange:
    backgroundColor: "rgba(254, 80, 0, 0.10)"
    textColor: "{colors.orange}"
    typography: "{typography.label}"
    rounded: "{rounded.pill}"
    padding: 4px 12px
  badge-dark:
    backgroundColor: "rgba(255, 255, 255, 0.12)"
    textColor: "{colors.dark-ink}"
    typography: "{typography.label}"
    rounded: "{rounded.pill}"
    padding: 4px 12px
  customer-logo-tile:
    backgroundColor: "{colors.surface-2}"
    textColor: "{colors.ink-muted}"
    typography: "{typography.caption}"
    rounded: "{rounded.md}"
    padding: 16px 24px
  text-input:
    backgroundColor: "{colors.surface-1}"
    textColor: "{colors.ink}"
    border: "1.5px solid {colors.hairline}"
    typography: "{typography.body}"
    rounded: "{rounded.md}"
    padding: 12px 16px
  text-input-focused:
    backgroundColor: "{colors.surface-1}"
    textColor: "{colors.ink}"
    border: "1.5px solid {colors.purple}"
    typography: "{typography.body}"
    rounded: "{rounded.md}"
    padding: 12px 16px
  text-input-dark:
    backgroundColor: "{colors.dark-surface-1}"
    textColor: "{colors.dark-ink}"
    border: "1.5px solid {colors.hairline-dark}"
    typography: "{typography.body}"
    rounded: "{rounded.md}"
    padding: 12px 16px
  top-nav-light:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    typography: "{typography.body-sm}"
    borderBottom: "1px solid {colors.hairline}"
    height: 64px
  top-nav-dark:
    backgroundColor: "transparent"
    textColor: "{colors.dark-ink}"
    typography: "{typography.body-sm}"
    height: 64px
  hero-section:
    background: "{gradients.hero-bg}"
    textColor: "{colors.dark-ink}"
    padding: 96px 0 80px
  footer:
    backgroundColor: "{colors.night}"
    textColor: "{colors.dark-ink-muted}"
    typography: "{typography.body-sm}"
    padding: 64px 32px
---

## Overview

Mindtickle is a sales enablement and revenue productivity platform targeting enterprise B2B buyers. Its marketing canvas alternates between two chromatic registers: a **light white register** for feature and product sections, and a **vivid dark register** — a deep dark-purple-to-electric-purple gradient (`#16003F → #5600F1`) — for hero sections, CTA banners, and featured pricing cards.

The system's energy comes from its orange. The primary CTA is a **warm gradient pill** (`#FE5000 → #F1B434`) — kinetic, optimistic, impossible to miss. Every page anchors around one of these pills; the gradient direction runs left-to-right on horizontal elements, reinforcing forward motion. All CTAs and interactive controls are fully pill-rounded (`{rounded.pill}` 9999px).

Headlines run **Montserrat Light (300)** at 64–80px for hero display — the light weight on a dark gradient field creates dramatic visual tension. Section-level headings switch to **Montserrat SemiBold (600)** for authority and scanability. Body copy is **Inter** at weight 400. Eyebrows are Inter at 600 with modest letter-spacing, rendered in ALL CAPS sparingly or sentence case.

The mood is: **enterprise ambition delivered with coach energy**. Copy leads with metrics ("3× faster ramp", "47% more quota attainment") then follows with empowering language ("unlock", "accelerate", "transform"). It talks to Revenue Leaders and Sales Enablement Directors, not developers.

**Key Characteristics:**
- **Orange gradient pill** (`{gradients.cta-button}`) is the single primary CTA treatment — never flat solid orange alone.
- **Hero/dark sections** use the dark-to-purple gradient (`{gradients.hero-bg}`) as the canvas, not solid dark purple.
- **Montserrat Light (300)** at display sizes — thin strokes on dark ground create premium editorial tension.
- **Montserrat SemiBold (600)** for section headlines — authority, scanability.
- **Inter** for all body, captions, buttons, eyebrows.
- Pill radius on all interactive elements; `{rounded.lg}` 16px and `{rounded.xl}` 24px on cards.
- Shadows are ambient only (`{shadows.card}`); no hard drop shadows.
- The purple accent (`{colors.purple}` #5600F1) appears on badges, focus rings, and secondary decorative elements — never as a CTA background.

## Colors

### Brand Primaries
- **Orange** (`{colors.orange}` #FE5000): The brand's defining primary — the gradient start point for all CTAs, active states, and key data callouts.
- **Orange Light / Gradient End** (`{colors.orange-light}` #F1B434): The warm amber terminus of the CTA gradient; also the semantic warning color.
- **Purple** (`{colors.purple}` #5600F1): Vivid electric purple — used as the hero gradient terminus, featured card accent, focus ring, and badge/tag highlight. Not used as a CTA background.
- **Night** (`{colors.night}` #16003F): The deepest brand dark — hero gradient start, footer background.

### Light-Mode Surfaces
- **Canvas** (`{colors.canvas}` #FFFFFF): Default page background — pure white.
- **Surface 1** (`{colors.surface-1}` #FFFFFF): Card background on white canvas.
- **Surface 2** (`{colors.surface-2}` #F5F4FB): Very subtly purple-tinted off-white — alt section rows, feature card backgrounds, testimonial cards, light CTA banners.
- **Hairline** (`{colors.hairline}` #E3E1EE): 1px card borders on light backgrounds — faint purple-gray.

### Dark-Mode Surfaces
- **Dark Canvas** (`{colors.dark-canvas}` #16003F): The hero section background (also the gradient start).
- **Dark Surface 1** (`{colors.dark-surface-1}` #1F0A52): Lifted dark card surface — dark feature cards, stat cards, dark pricing cards.
- **Dark Surface 2** (`{colors.dark-surface-2}` #2B1269): Even lighter dark surface — hover states, secondary dark cards.
- **Hairline Dark** (`{colors.hairline-dark}` #3D1E7A): 1px borders on dark surfaces.

### Text
- **Ink** (`{colors.ink}` #15191F): All headlines and body type on light backgrounds.
- **Ink Muted** (`{colors.ink-muted}` #4B5563): Secondary descriptors, meta info, card body on light.
- **Ink Subtle** (`{colors.ink-subtle}` #6B7280): Tertiary text — captions, helper text, footer links.
- **Dark Ink** (`{colors.dark-ink}` #FFFFFF): All type on dark/hero backgrounds.
- **Dark Ink Muted** (`{colors.dark-ink-muted}` #9D8EC8): Secondary type on dark surfaces — descriptions, card body in hero sections.
- **Dark Ink Subtle** (`{colors.dark-ink-subtle}` #6B5EA8): Tertiary text on dark — captions on hero sections.

### Semantic
- **Semantic Error / Hot Pink** (`{colors.semantic-error}` #CE0F69): Validation errors, destructive states, alert badges.
- **Semantic Info / Teal** (`{colors.semantic-info}` #0093B2): Informational states, info badges, hyperlinks.
- **Semantic Warning / Amber** (`{colors.semantic-warning}` #F1B434): Warning states — doubles as the CTA gradient terminus.

### Gradients
- **Hero Background** (`{gradients.hero-bg}`): `linear-gradient(135deg, #16003F 0%, #5600F1 100%)` — the defining visual of every dark section. Applied at 135° for maximum diagonal dynamism.
- **CTA Button** (`{gradients.cta-button}`): `linear-gradient(90deg, #FE5000 0%, #F1B434 100%)` — left-to-right, reinforces forward motion. Used on all primary action pills.
- **Section Dark** (`{gradients.section-dark}`): `linear-gradient(180deg, #16003F 0%, #5600F1 100%)` — a top-to-bottom variation for full dark sections that fade in from the page top.

## Typography

### Font Families

- **Montserrat** — Headings at all sizes. Available on Google Fonts. Uses Light (300) for hero display and SemiBold (600) for section headings and card titles. Fallback: `Montserrat, ui-sans-serif, system-ui`.
- **Inter** — Body, captions, buttons, eyebrows, labels. Available on Google Fonts. Uses Regular (400) for body, SemiBold (600) for buttons and eyebrows. Fallback: `Inter, ui-sans-serif, system-ui`.

### Hierarchy

| Token | Size | Family | Weight | Line Height | Letter Spacing | Use |
|---|---|---|---|---|---|---|
| `{typography.display-xl}` | 80px | Montserrat | 300 | 1.05 | -2.5px | Hero headline (dark gradient) |
| `{typography.display-lg}` | 64px | Montserrat | 300 | 1.08 | -1.8px | Hero sub-headline, large feature headlines |
| `{typography.display-md}` | 48px | Montserrat | 600 | 1.15 | -0.8px | Section opener headlines (light sections) |
| `{typography.headline}` | 32px | Montserrat | 600 | 1.20 | -0.4px | Card section titles, CTA banner headlines |
| `{typography.card-title}` | 24px | Montserrat | 600 | 1.25 | -0.2px | Pricing tier names, feature card headers |
| `{typography.subhead}` | 20px | Inter | 400 | 1.40 | 0 | Hero body copy, lead intro paragraphs |
| `{typography.body-lg}` | 18px | Inter | 400 | 1.55 | 0 | Section body, testimonial quotes |
| `{typography.body}` | 16px | Inter | 400 | 1.60 | 0 | Default body copy |
| `{typography.body-sm}` | 14px | Inter | 400 | 1.55 | 0 | Card body, nav links, form labels |
| `{typography.caption}` | 12px | Inter | 400 | 1.40 | 0 | Captions, meta, customer logo labels |
| `{typography.button}` | 15px | Inter | 600 | 1.20 | 0 | All button labels |
| `{typography.eyebrow}` | 13px | Inter | 600 | 1.30 | 0.8px | Section eyebrows (sentence case) |
| `{typography.label}` | 13px | Inter | 500 | 1.30 | 0 | Badge text, tag labels |

### Principles

- **Display uses Montserrat Light (300).** Thin strokes on the dark gradient field create editorial, premium tension. Do not use Regular (400) or Medium (500) for display sizes.
- **Section headings use Montserrat SemiBold (600).** The weight shift from Light to SemiBold defines the boundary between hero drama and content authority.
- **Negative tracking scales with size.** -2.5px at 80px (≈3%), tapering to 0 on body. Never apply negative tracking below `{typography.headline}`.
- **Line-heights tighten on display, open on body.** 1.05 at display-xl → 1.60 at body.
- **Inter carries everything below headline level.** Buttons, eyebrows, labels — all Inter.
- **Eyebrows use sentence case** with `letter-spacing: 0.8px` for air — not ALL-CAPS all-through tracking.

## Layout

### Spacing System

- **Base unit**: 8px.
- **Tokens**: `{spacing.xxs}` 4px · `{spacing.xs}` 8px · `{spacing.sm}` 12px · `{spacing.md}` 16px · `{spacing.lg}` 24px · `{spacing.xl}` 32px · `{spacing.xxl}` 48px · `{spacing.section}` 96px.
- Hero vertical padding: `{spacing.section}` 96px top, 80px bottom.
- Card interior padding: `{spacing.lg}` 24px for standard cards; `{spacing.xl}` 32px for feature/testimonial/stat cards; `{spacing.xxl}` 48px + `{spacing.xl}` horizontal for CTA banners.
- Pill button padding: 12px vertical · 28px horizontal (wider pill for visual weight).

### Grid & Container

- Max content width: 1280px.
- Feature card grids: 3-up at desktop, 2-up at tablet, 1-up at mobile.
- Stat callout rows: 3–4 metrics inline at desktop.
- Testimonial / customer logo rows: 3–4-up at desktop.
- CTA banners span full container width with padded interior.

### Whitespace Philosophy

Sections breathe with `{spacing.section}` 96px vertical separation. The alternation between light and dark sections replaces the need for heavy horizontal rules — the gradient surface change IS the divider.

## Elevation & Depth

| Level | Treatment | Use |
|---|---|---|
| 0 (flat) | No shadow, no border | Hero text, body copy, eyebrows |
| 1 (hairline lift) | `{colors.surface-1}` + `{colors.hairline}` border | Standard cards on white canvas |
| 2 (ambient shadow) | `{shadows.card}` | Cards requiring extra lift (pricing, testimonial) |
| 3 (hover lift) | `{shadows.card-hover}` | Cards on hover, interactive lift |
| 4 (modal / overlay) | `{shadows.modal}` | Featured pricing card, modals, overlays |

Mindtickle avoids hard drop shadows. All shadows use the Night purple `rgba(22, 0, 63, …)` as the shadow base color to stay tonally on-brand — never generic black-based shadows.

## Shapes

### Border Radius Scale

| Token | Value | Use |
|---|---|---|
| `{rounded.xs}` | 4px | Tiny inline badges, form error indicators |
| `{rounded.sm}` | 8px | Small chips, code blocks |
| `{rounded.md}` | 12px | Form inputs, text areas |
| `{rounded.lg}` | 16px | Standard cards, dropdowns |
| `{rounded.xl}` | 24px | Feature cards, testimonial cards, pricing cards |
| `{rounded.xxl}` | 32px | CTA banners, large hero cards |
| `{rounded.pill}` | 9999px | **All buttons without exception**, toggle pills, tag pills |
| `{rounded.full}` | 9999px | Avatars, step-number circles |

**The pill is the brand's kinetic signature.** Every interactive control — primary button, secondary button, ghost button, search field pill — uses `{rounded.pill}`. This distinguishes Mindtickle from squared-off enterprise peers and reinforces the "forward motion" message.

## Components

### Buttons

**`button-primary`** — The brand's defining CTA. Orange gradient pill — use for every primary action.
- Background `{gradients.cta-button}`, text `{colors.white}`, type `{typography.button}`, padding 12px 28px, rounded `{rounded.pill}`.

**`button-secondary`** — Outlined orange pill. Secondary action on light backgrounds.
- Background transparent, border `1.5px solid {colors.orange}`, text `{colors.orange}`, type `{typography.button}`, rounded `{rounded.pill}`.

**`button-secondary-dark`** — Outlined white pill. Secondary action on dark/hero backgrounds.
- Background transparent, border `1.5px solid {colors.white}`, text `{colors.white}`, type `{typography.button}`, rounded `{rounded.pill}`.

**`button-ghost`** / **`button-ghost-dark`** — Transparent text-only action. Tertiary navigation links.

### Badges & Labels

**`badge`** — Purple tinted. Default for feature labels, "New", category tags on light backgrounds.
- Background `rgba(86, 0, 241, 0.10)`, text `{colors.purple}`, rounded `{rounded.pill}`, padding 4px 12px.

**`badge-orange`** — Orange tinted. Promotional or highlight tags.
- Background `rgba(254, 80, 0, 0.10)`, text `{colors.orange}`, rounded `{rounded.pill}`.

**`badge-dark`** — Frosted white. Tags on hero/dark-gradient backgrounds.
- Background `rgba(255, 255, 255, 0.12)`, text `{colors.dark-ink}`, rounded `{rounded.pill}`.

### Cards

**`card-light`** — Standard card on the white canvas.
- Background `{colors.surface-1}`, border `{colors.hairline}`, shadow `{shadows.card}`, rounded `{rounded.lg}`, padding 24px.

**`feature-card`** — Feature highlight on subtly tinted surface.
- Background `{colors.surface-2}`, border `{colors.hairline}`, rounded `{rounded.xl}`, padding 32px.

**`feature-card-dark`** — Feature highlight inside dark/hero sections.
- Background `{colors.dark-surface-1}`, border `{colors.hairline-dark}`, rounded `{rounded.xl}`, padding 32px.

**`testimonial-card`** — Customer quote on light surface.
- Background `{colors.surface-2}`, border `{colors.hairline}`, type `{typography.body-lg}`, rounded `{rounded.xl}`, padding 32px.

**`stat-card`** — Big metric callout. Lives in dark sections.
- Background `{colors.dark-surface-1}`, border `{colors.hairline-dark}`, rounded `{rounded.xl}`, padding 32px. Metric value uses `{typography.display-md}` in `{colors.orange}`.

**`pricing-card`** — Default tier on pricing page.
- Background `{colors.surface-1}`, border `{colors.hairline}`, shadow `{shadows.card}`, rounded `{rounded.xl}`, padding 32px.

**`pricing-card-featured`** — Recommended/highlighted tier.
- Background `{gradients.hero-bg}`, no border, shadow `{shadows.modal}`, rounded `{rounded.xl}`, padding 32px. CTA button uses `{gradients.cta-button}`.

### Inputs

**`text-input`** — Standard form field.
- Background `{colors.surface-1}`, border `{colors.hairline}`, type `{typography.body}`, rounded `{rounded.md}`, padding 12px 16px.

**`text-input-focused`** — Focus ring uses brand purple.
- Border switches to `1.5px solid {colors.purple}`.

**`text-input-dark`** — Input on dark backgrounds.
- Background `{colors.dark-surface-1}`, border `{colors.hairline-dark}`, text `{colors.dark-ink}`, rounded `{rounded.md}`.

### Sections

**`hero-section`** — Top-of-page section.
- Background `{gradients.hero-bg}`, text `{colors.dark-ink}`, padding 96px 0 80px.
- Headline: `{typography.display-xl}`, eyebrow: `{typography.eyebrow}` in `{badge-dark}` pill, subhead: `{typography.subhead}` at `{colors.dark-ink-muted}`.
- CTA pair: `{button-primary}` + `{button-secondary-dark}`.

**`cta-banner-dark`** — Closing CTA panel in dark register.
- Background `{gradients.hero-bg}`, rounded `{rounded.xxl}`, padding 64px 48px. Centered headline + `{button-primary}`.

**`cta-banner-light`** — Closing CTA panel in light register.
- Background `{colors.surface-2}`, border `{colors.hairline}`, rounded `{rounded.xxl}`, padding 64px 48px.

### Navigation

**`top-nav-light`** — Sticky nav bar on light-background pages.
- Background `{colors.canvas}`, border-bottom `{colors.hairline}`, text `{colors.ink}`, height 64px.
- Nav links in `{typography.body-sm}` weight 500; primary CTA in `{button-primary}`.

**`top-nav-dark`** — Transparent nav over hero gradient.
- Background transparent, text `{colors.dark-ink}`, height 64px.
- CTA uses `{button-primary}`.

### Footer

**`footer`** — Dense link grid on deep Night background.
- Background `{colors.night}` (#16003F), text `{colors.dark-ink-muted}`, type `{typography.body-sm}`, padding 64px 32px.
- Logo and copyright in `{colors.dark-ink}`.

## Voice & Personality

**Tone:** Empowering, outcome-focused, metric-driven. Sentences start with the result, not the process.

**Energy:** High. Urgency is implicit in every headline.

**Audience:** VP of Sales, Head of Revenue Operations, Sales Enablement Directors at mid-market and enterprise B2B companies.

**Copy patterns:**
- Lead with a number: "3× faster ramp", "47% more quota attainment", "200+ enterprise teams"
- Follow with aspiration: "Unlock your team's full potential", "Accelerate revenue growth", "Transform your sales force"
- CTA is outcome-not-action: "See Mindtickle in Action", "Get Your Personalized Demo", "Start Winning More Deals"
- Short punchy clauses: "Ramp faster. Coach smarter. Win more."

## Do's and Don'ts

### Do

- Apply `{gradients.cta-button}` to ALL primary action pills — never flat solid `{colors.orange}` alone.
- Use `{gradients.hero-bg}` for hero sections, featured pricing cards, and closing CTA banners.
- Use `{rounded.pill}` on all buttons without exception.
- Set `{typography.display-xl}` and `{typography.display-lg}` at Montserrat weight 300 — the Light weight is the headline signature.
- Switch to Montserrat SemiBold (600) at `{typography.display-md}` and below.
- Use `{colors.purple}` on badges, focus rings, and subtle gradient work — never as a standalone CTA background.
- Use purple-tinted shadow `rgba(22, 0, 63, …)` as the shadow base color — never generic black.
- Lead stat callouts with `{typography.display-md}` in `{colors.orange}` on dark cards.
- Place an eyebrow badge (`{badge}` or `{badge-dark}`) above hero headlines for category context.

### Don't

- Don't use flat solid `{colors.orange}` as a button background — the gradient IS the button.
- Don't use `{colors.purple}` as the sole button background color.
- Don't square-off buttons with `{rounded.lg}` or smaller — all CTAs need `{rounded.pill}`.
- Don't set hero headlines at weight 400, 500, or 600 — display requires weight 300.
- Don't apply hard black drop shadows — keep shadows purple-base and ambient only.
- Don't put two competing orange CTAs side-by-side — pair `{button-primary}` with `{button-secondary-dark}` or `{button-ghost-dark}` on dark sections.
- Don't use `{colors.semantic-error}` hot pink for decorative purposes — it is strictly for error states.
- Don't swap the hero gradient direction; 135° diagonal is the standard treatment.
- Don't write body copy in Montserrat — Montserrat is headings only.

## Responsive Behavior

### Breakpoints

| Name | Width | Key Changes |
|---|---|---|
| Desktop XL | 1440px | Default — max content 1280px centered |
| Desktop | 1280px | 3-up card grids maintained |
| Tablet | 1024px | Card grids 3-up → 2-up; nav may compress |
| Mobile Lg | 768px | Single-column; nav collapses to hamburger |
| Mobile | 480px | `{typography.display-xl}` 80px → ~36px |

### Collapsing Strategy

- **Display type**: `{typography.display-xl}` 80px scales toward ~36px on mobile. Maintain weight 300.
- **Card grids**: 3-up → 2-up at 1024px → 1-up below 768px.
- **CTA buttons**: Stay pill — padding can tighten to 10px 20px below 480px.
- **Top nav**: Links collapse to hamburger below 768px; `{button-primary}` CTA stays visible.
- **Stat row**: 4 stats → 2×2 grid at tablet → 2×2 or 1-column at mobile.

### Touch Targets

- All pill CTAs hold ≥44px tap height.
- Form inputs hold ≥44px tap target on touch.
- Nav links hold ≥40px tap area.

## Quick Reference (for Claude)

```css
:root {
  /* Brand primaries */
  --orange: #FE5000;
  --orange-light: #F1B434;
  --purple: #5600F1;
  --night: #16003F;

  /* Light canvas */
  --canvas: #FFFFFF;
  --surface-2: #F5F4FB;
  --ink: #15191F;
  --ink-muted: #4B5563;
  --hairline: #E3E1EE;

  /* Dark canvas */
  --dark-surface-1: #1F0A52;
  --dark-ink: #FFFFFF;
  --dark-ink-muted: #9D8EC8;
  --hairline-dark: #3D1E7A;

  /* Gradients */
  --gradient-hero: linear-gradient(135deg, #16003F 0%, #5600F1 100%);
  --gradient-cta: linear-gradient(90deg, #FE5000 0%, #F1B434 100%);

  /* Semantic */
  --error: #CE0F69;
  --info: #0093B2;
  --warning: #F1B434;

  /* Shape */
  --radius-pill: 9999px;
  --radius-card: 16px;
  --radius-card-lg: 24px;

  /* Shadows (purple-base) */
  --shadow-card: 0 2px 16px 0 rgba(22, 0, 63, 0.08);
  --shadow-card-hover: 0 6px 32px 0 rgba(22, 0, 63, 0.14);
  --shadow-modal: 0 16px 64px 0 rgba(22, 0, 63, 0.20);
}
```

---

## Reference

**Website:** [https://www.mindtickle.com](https://www.mindtickle.com)

To extract a fresher version of this brand's design system, run the Power Design Firecrawl extractor against `https://www.mindtickle.com` and replace this file with the output.
