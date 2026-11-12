# Supahub — Style Reference
> Soft daylight on a violet ridge. A mostly white, airy canvas lit by a single bright violet sun, with decorative gradient orbs spilling color into negative space and generous rounded geometry giving every surface a friendly, tactile weight.

**Theme:** light

Source measurements are normalized; roles and recommendations are interpreted. Font summary lists are independent, not paired by position. HTML examples are reconstructions, not source components.

Supahub is a sunlit feedback platform rendered in soft white space punctuated by violet confidence. The system favors a quiet, mostly achromatic canvas where a single vivid violet (#862fe7) carries all primary action weight, then lets decorative lavender, pink, and amber gradient orbs burst through hero and feature sections to dramatize product surfaces. Typography is a Bricolage Grotesque / Inter pairing: the geometric variable display face does the emotional heavy lifting at 48–56px with tight -0.025em tracking, while Inter handles dense UI, captions, and supporting copy in compact 14–16px weights. Components sit on a generous spacing rhythm with two dominant radii — 12px for buttons and small surfaces, and 9999px (pill) for avatars, tags, and decorative badges — producing a friendly, rounded, approachable product surface rather than an enterprise grid. The overall feeling is a modern SaaS product page that borrows energy from the consumer-app playbook: floating product mockups, gradient atmospheres, and testimonial walls treated as content wallpaper, never as filler.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Voltage Violet | `#862fe7` | `--color-voltage-violet` | Primary filled action buttons, active nav state, key accent text — the single saturated brand anchor against the white canvas |
| Ultra Violet | `#5f259e` | `--color-ultra-violet` | Deeper violet for gradient stop, hover state, or emphasis text where Voltage Violet feels too bright |
| Lavender Mist | `#ad6df4` | `--color-lavender-mist` | Soft decorative violet for card backgrounds, icon tints, and gradient mid-stops |
| Orchid Wash | `#bd8ff0` | `--color-orchid-wash` | Lightest decorative violet wash for large surface fills behind product cards and feature bands |
| Magenta Spark | `#ff5fe4` | `--color-magenta-spark` | Pink wash for highlight backgrounds, decorative bands, and soft emphasis behind content. Do not promote it to the primary CTA color |
| Hot Pink Ray | `#e22ba4` | `--color-hot-pink-ray` | Saturated pink gradient stop paired with violet in atmospheric gradient orbs |
| Amber Pulse | `#dc5f05` | `--color-amber-pulse` | Warm orange accent in gradient orbs providing chromatic counterpoint to the violet/pink palette |
| Midnight Ink | `#111827` | `--color-midnight-ink` | Primary heading and body text, primary border, and filled dark action background (the dark CTA variant) |
| Graphite | `#3f4654` | `--color-graphite` | Secondary text, nav borders, muted UI text on white surfaces |
| Slate | `#6b7589` | `--color-slate` | Tertiary text, icon fills, helper copy, and supporting metadata |
| Pure White | `#ffffff` | `--color-pure-white` | Primary card and surface background, button text on filled violet actions, inverted text |
| Fog | `#f1f5f9` | `--color-fog` | Alternate section background, subtle surface lift above white |
| Mist | `#d8e0ea` | `--color-mist` | Hairline borders, input borders, button focus rings, subtle dividers |
| Mint Wash | `#d6fcf4` | `--color-mint-wash` | Soft mint tint for highlighted feature panels and tag/badge backgrounds — appears as a chromatic counterpoint to violet |
| Lavender Field | `#ebdafd` | `--color-lavender-field` | Violet wash for highlight backgrounds, decorative bands, and soft emphasis behind content. Do not promote it to the primary CTA color |

## Tokens — Typography

### Bricolage Grotesque — Display and heading face. Variable custom sans with subtle character (slightly condensed, soft terminals) used for hero headlines at 48–56px, section headlines at 32px, and emphasized subheadings. The tight -0.025em tracking at large sizes is signature — it pulls the wide geometric forms into a dense, confident block. Weights stay conservative: 400 for body-class copy in display contexts, 600 only when emphasis is needed. · `--font-bricolage-grotesque`
- **Substitute:** Space Grotesk
- **Weights:** 400, 600
- **Sizes:** 16px, 20px, 22px, 24px, 32px, 48px, 56px
- **Line height:** 1.20 – 1.75
- **Letter spacing:** -0.025em

### Inter — Workhorse UI and body face. Used for nav, buttons, body copy, captions, and all dense interface text. Letter-spacing opens to +0.1em at 12px for uppercase labels (eyebrows like 'TESTIMONIAL', 'CUSTOMER FEEDBACK'). Carries the readability weight of the system; Bricolage never appears below 20px. · `--font-inter`
- **Substitute:** Inter (native)
- **Weights:** 400, 500, 600, 700
- **Sizes:** 12px, 14px, 16px, 18px, 20px
- **Line height:** 1.33 – 1.80
- **Letter spacing:** 0.1000em

### Type Scale

| Role | Family | Weight | Size | Line Height | Letter Spacing | Token |
|------|--------|--------|------|-------------|----------------|-------|
| caption | — | — | 12px | 1.5 | 1.2px | `--text-caption` |
| body-sm | — | — | 14px | 1.6 | — | `--text-body-sm` |
| body | — | — | 16px | 1.75 | — | `--text-body` |
| subheading | — | — | 20px | 1.5 | — | `--text-subheading` |
| heading-sm | — | — | 24px | 1.3 | -0.6px | `--text-heading-sm` |
| heading | — | — | 32px | 1.2 | -0.8px | `--text-heading` |
| display | — | — | 56px | 1 | -1.4px | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 4px
**Density:** comfortable

### Border Radius

| Element | Value |
|---------|-------|
| nav | 8px |
| cards | 24px |
| pills | 9999px |
| images | 16px |
| buttons | 12px |
| featured-card | 40px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| subtle | `rgba(11, 61, 121, 0.16) 0px 0px 0px 1px inset` | `--shadow-subtle` |

### Layout

- **Page max-width:** 1200px
- **Section gap:** 80px
- **Card padding:** 24px
- **Element gap:** 16px
