---
name: Serene Clinical Intelligence
colors:
  surface: '#fbf9f6'
  surface-dim: '#dbdad7'
  surface-bright: '#fbf9f6'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f5f3f0'
  surface-container: '#efeeeb'
  surface-container-high: '#eae8e5'
  surface-container-highest: '#e4e2df'
  on-surface: '#1b1c1a'
  on-surface-variant: '#404945'
  inverse-surface: '#30312f'
  inverse-on-surface: '#f2f0ed'
  outline: '#717975'
  outline-variant: '#c0c8c3'
  surface-tint: '#3a6758'
  primary: '#134235'
  on-primary: '#ffffff'
  primary-container: '#2d5a4c'
  on-primary-container: '#a0cfbe'
  inverse-primary: '#a1d1bf'
  secondary: '#32647c'
  on-secondary: '#ffffff'
  secondary-container: '#b3e4ff'
  on-secondary-container: '#35677e'
  tertiary: '#6b240a'
  on-tertiary: '#ffffff'
  tertiary-container: '#893a1f'
  on-tertiary-container: '#ffb49c'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#bcedda'
  primary-fixed-dim: '#a1d1bf'
  on-primary-fixed: '#002118'
  on-primary-fixed-variant: '#214f41'
  secondary-fixed: '#c1e8ff'
  secondary-fixed-dim: '#9ccde8'
  on-secondary-fixed: '#001e2b'
  on-secondary-fixed-variant: '#154c63'
  tertiary-fixed: '#ffdbd0'
  tertiary-fixed-dim: '#ffb59e'
  on-tertiary-fixed: '#390b00'
  on-tertiary-fixed-variant: '#7a2f15'
  background: '#fbf9f6'
  on-background: '#1b1c1a'
  surface-variant: '#e4e2df'
typography:
  display-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 40px
    fontWeight: '600'
    lineHeight: 48px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 30px
    fontWeight: '600'
    lineHeight: 38px
    letterSpacing: -0.015em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
    letterSpacing: -0.015em
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 22px
    fontWeight: '600'
    lineHeight: 30px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 26px
    letterSpacing: 0em
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 26px
    letterSpacing: 0em
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 22px
    letterSpacing: 0.005em
  body-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 18px
    letterSpacing: 0.01em
  label-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.01em
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.02em
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 11px
    fontWeight: '500'
    lineHeight: 14px
    letterSpacing: 0.03em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  space-xxs: 0.25rem
  space-xs: 0.5rem
  space-sm: 0.75rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2rem
  space-2xl: 3rem
  space-3xl: 4rem
  gutter-mobile: 1rem
  gutter-desktop: 1.5rem
  margin-mobile: 1rem
  margin-tablet: 2rem
  margin-desktop: 3rem
---

## Brand & Style

This design system is crafted specifically for autonomous mental health professionals (psychologists, psychoanalysts, therapists) managing AI conversational agents across messaging and social platforms.

### Personality & Emotional Response
The interface evokes calm assurance, therapeutic warmth, intentional pacing, and ethical rigor. It consciously rejects the cold, hyper-analytical, data-dense sterility typical of enterprise dashboards, as well as the loud, gamified aesthetics of commercial conversational marketing tools. The emotional tone mirrors a peaceful consulting room: welcoming, quiet, safe, and trustworthy.

### Design Movement
**Organic Warm Minimalism with Tactile Softness.** 
The visual language pairs airy, breathable layouts and warm linen-textured undertones with soft, pillowy elevations. Interfaces employ generous whitespace, gentle curved geometries (`rounded-xl` to `rounded-2xl`), and tactile feedback states. Digital components feel calm and physically reassuring rather than synthetic or mechanical.

## Colors

The color palette grounds the user in restorative, natural tones, systematically avoiding high-strain pure blacks or harsh stark-white surfaces.

### Functional Palette Structure
- **Primary (`#2D5A4C` / Sage Deep):** Represents grounded trust and professional equilibrium. Applied to primary CTAs, active states, key navigation indicators, and prominent branding anchors.
- **Secondary (`#23576E` / Teal Haven):** Denotes secondary actions, conversational status metrics, and channel groupings (WhatsApp/Instagram integrations).
- **Tertiary Accent (`#D97757` / Warm Terracotta):** Used selectively for highlights, prompt tips, empathetic callouts, and active conversation milestones.
- **Neutral & Canvas Surfaces:**
  - Base Canvas (`#FAF8F5`): A soft, linen-warmed off-white that mitigates ocular fatigue.
  - Sub-surface / Surface Alt (`#F4EFEA`): Subtle background shading for toolbars, sidebars, and grouped settings.
  - Card Surfaces (`#FFFFFF`): Crisp elevated white keeping readability pristine.
  - Surface Hairline (`#E6E0D8`): Muted border tone preventing harsh visual separation.
  - Text Primary (`#1C2A24`): Very deep sage-slate, providing AAA-level contrast without the harshness of `#000000`.
  - Text Secondary (`#566A63`): Muted botanical grey for metadata, timestamps, and supporting copy.

### Clinical & Ethical Alert Spectrum
- **Critical / Crisis Triage (`#E05A47`):** Reserved exclusively for crisis intervention triggers (e.g., self-harm or safety protocol activation requiring practitioner intervention). It conveys absolute clarity and urgency without inducing visual panic.
- **Attention / Caution (`#E87A3D`):** Warm amber used when the conversational agent pauses or encounters ambiguous language requiring manual review.
- **Ethical Compliance Badge (`#2D5A4C` tinted at 8% opacity with solid text):** Subtle, persistent tone for CFP/LGPD ethical compliance notices.

## Typography

Typography relies entirely on **Plus Jakarta Sans**, chosen for its humanist openness, balanced geometry, and friendly structural terminals that reduce clinical harshness.

### Hierarchy & Typesetting Guidelines
- **Weight Restraint:** Headings favor `SemiBold` (600) rather than heavy `Bold` (700 or 800), delivering presence while maintaining softness.
- **Readability & Tracking:** Body text employs slightly relaxed line-heights (1.55 to 1.625) to provide a meditative reading cadence suited for reviewing patient conversation transcripts.
- **Ethical Notes & Small Text:** No informational text may render smaller than `11px`. Status badges and ethical regulatory tags must maintain `Medium` (500) or `SemiBold` (600) weight to retain absolute legibility across dense transcript views.

## Layout & Spacing

The layout is built on a responsive 12-column fluid grid system on desktop, collapsing to 8 columns on tablet and 4 columns on mobile. 

### Breakpoints & Adaptive Rhythm
- **Mobile (< 640px):** 4 columns, `16px` outer margins, `16px` gutters. Transcripts switch to full-width card presentations; sidebar collapses into a soft-elevated floating bottom bar or slide-out drawer.
- **Tablet (640px - 1024px):** 8 columns, `32px` outer margins, `20px` gutters. Metrics cards transition into 2x2 grids.
- **Desktop (> 1024px):** 12 columns, max-width `1440px` centered canvas, `48px` outer margins, `24px` gutters. Three-pane split layout: 
  1. Primary navigation & Assistant status toggle (left, 260px fixed width),
  2. Main working feed & live message stream (center fluid),
  3. Patient context, AI empathy prompt parameters & CFP safety panel (right, 380px fixed width).

### Layout Philosophy
Density is low to moderate. Components are granted ample breathing space (`space-xl` and `space-2xl`) between functional zones to create psychological calmness and intentionality during administrative reviews.

## Elevation & Depth

Visual depth is achieved through **ambient layered warmth** rather than stark drop-shadows or high-contrast borders. 

### Depth Architecture
1. **Canvas (Base Level):** Solid warm off-white (`#FAF8F5`). Completely non-reflective.
2. **Surface Level 1 (Panels & Cards):** Pure white (`#FFFFFF`) with a micro-stroke border (`1px solid #E6E0D8`) and an ambient tinted shadow:
   `box-shadow: 0 4px 20px -2px rgba(45, 90, 76, 0.05), 0 2px 6px -1px rgba(35, 87, 110, 0.03);`
   The faint green-teal shadow tint removes synthetic digital greyness and feels naturally cast by soft daylit surroundings.
3. **Surface Level 2 (Floating Action Bars, Dialogs, Crisis Modals):**
   Pure white (`#FFFFFF`) backed by a deeper, ultra-diffused atmospheric shadow:
   `box-shadow: 0 16px 40px -6px rgba(28, 42, 36, 0.08), 0 6px 16px -2px rgba(28, 42, 36, 0.04);`
4. **Interactive Focus & Hover:**
   Hover states subtly translate upward (`-1px` to `-2px`) while increasing the soft spread radius, avoiding abrupt jumps or flashing color transitions.

## Shapes

The interface embraces a gentle, approachable curvature that feels warm to the touch and eliminates harsh corners.

### Shape Scales
- **Base Elements (`rounded-lg` / `0.5rem` / 8px):** Checkboxes, small tag chips, table rows, form inputs.
- **Interactive Controls (`rounded-xl` / `1rem` / 16px):** Primary and secondary buttons, dropdown selectors, channel filter badges.
- **Containers & Cards (`rounded-2xl` / `1.5rem` / 24px):** Feed modules, patient conversation cards, analytics containers, safety prompt banners.
- **Special Status & Toggles (`rounded-full` / 9999px):** Master Assistant on/off pills, avatar circles, channel indicators, floating trigger chips.

## Components

### 1. Buttons
- **Primary:** Background `#2D5A4C`, text `#FFFFFF`, border `none`, `rounded-xl`. Hover state deepens to `#24473C`. Generous horizontal padding (`20px`), height `44px`.
- **Secondary:** Background `#FAF8F5`, text `#23576E`, border `1px solid #D8D2C9`, `rounded-xl`. Hover state transitions to pure `#FFFFFF` with border `#23576E`.
- **Tertiary / Ghost:** Background `transparent`, text `#2D5A4C`. Hover background `#FAF8F5` with `rounded-lg`.
- **Crisis Intervention Action:** Background `#E05A47`, text `#FFFFFF`. High visual weight for immediate human takeover of a conversation.

### 2. Status & Mode Toggles (Assistant State)
- **Master Status Switch (Active / Paused):**
  - Segmented tactile pill container (`#F4EFEA` background, `padding: 4px`, `rounded-full`).
  - Active position: Soft sage-green glow (`#2D5A4C` pill, `#FFFFFF` text) accompanied by a pulsating green dot indicator (`#3E7363`).
  - Paused position: Warm sandstone tone (`#D97757` or `#8C827A`), signaling graceful standby without error semantics.

### 3. Cards & Conversation Transcripts
- **Card Container:** Pure white background, `rounded-2xl`, border `1px solid #E6E0D8`.
- **Message Bubbles:**
  - AI Assistant: Light sage-tinted background (`#EDF3F0`), text `#1C2A24`, `rounded-2xl` with bottom-left corner softened to `rounded-sm`.
  - Patient (WhatsApp / Instagram): Pure white with border `1px solid #E6E0D8`, `rounded-2xl` with bottom-right corner softened to `rounded-sm`.
  - Intervention Prompt: Soft Terracotta fill (`#FAF0EC`) with a left border (`3px solid #D97757`).

### 4. Chips & Channel Badges
- **Platform Badges:** Pill-shaped (`rounded-full`), `12px` typography, `padding: 4px 12px`.
  - WhatsApp: Soft jade fill with dark green text.
  - Instagram: Gentle berry-blush fill with deep plum text.
  - TikTok: Muted slate-sky fill with navy text.
- Never use garish, high-saturation third-party brand colors; harmonize all external platform logos with the system's muted natural tones.

### 5. Input Fields & Prompt Editors
- Background `#FFFFFF`, border `1px solid #E6E0D8`, `rounded-xl`, height `44px`, text `#1C2A24`.
- **Focus State:** Border shifts smoothly to `#2D5A4C` with a soft aura ring (`box-shadow: 0 0 0 3px rgba(45, 90, 76, 0.15)`).
- **Helper & Safety Text:** Subordinate text displayed beneath in `#566A63` at `12px`.

### 6. Ethical Regulatory Disclaimer Bar (LGPD / CFP)
- A dedicated, non-dismissible or persistently anchored utility banner.
- Visual style: Subtle sage background (`rgba(45, 90, 76, 0.06)`), border `1px solid rgba(45, 90, 76, 0.15)`, `rounded-xl`.
- Content pattern: Shield icon + *"Assistente ético em conformidade CFP / LGPD: Este agente atua em triagem e acolhimento preliminar, não realiza diagnósticos e não substitui a psicoterapia clínica."*

### 7. Form Controls (Checkboxes & Radios)
- Checkbox: Size `20px`, `rounded-md`, border `1.5px solid #D8D2C9`. Checked state: Background `#2D5A4C` with white checkmark.
- Radio: Size `20px`, `rounded-full`, border `1.5px solid #D8D2C9`. Selected state: Inner dot `#2D5A4C` with `4px` breathing clearance.