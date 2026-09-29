# CrowdSense brand tokens

The canonical values live in the marketing site (`crowdsense-events`, `src/styles`). This sheet mirrors them so any repo in the org can style a README, a badge or a one-off page without opening that repo. When the two disagree, the marketing site wins — fix this file.

**Temperament:** friendly-precise. Light-first, white and band rhythm, hairlines, 15px radius, one ambient gradient glow at most. Counts, not credentials — the design never implies it knows *who*.

## Colour

| Token | Value | Use |
| :-- | :-- | :-- |
| `--color-primary` | `#0000ee` | The CrowdSense blue. CTAs, active states, links on white, the mark. |
| `--color-secondary` / `--cs-live` | `#3898ec` | Live indicators, secondary accents. |
| `--color-link` | `#1070ff` | Links in body copy, the outer bars of the mark. |
| mark accent | `#ffa266` | The centre bar of the mark only. Never a UI colour. |
| `--color-focus` | `#f26a1c` | Focus rings. |
| `--cs-amber` | `#f0a202` | Warning. |
| `--cs-alert` / `--color-danger` | `#dc2626` | Alert, danger. |
| `--color-dark` | `#101010` | Dark sections, the og card ground. |
| `--color-ink` | `#3f3f3f` | Body text. |
| `--color-muted` | `#6a6a75` | Muted text. |
| `--color-subtle` | `#727280` | Subtle text, eyebrows. |
| `--color-hairline` | `#d8d8e2` | 1px rules. |
| `--color-band` | `#ececf3` | Alternating band background. |
| `--color-accent` | `#e9e9f3` | Tinted fills. |
| `--color-surface` | `#f3f3f3` | Cards on white. |
| `--color-background` | `#ffffff` | Page. |

Badge recipe (shields.io): `style=for-the-badge`, primary `0000ee` with white text, live `3898ec`, white badges with `logoColor=0000ee`.

## Type

| Role | Family | Weight |
| :-- | :-- | :-- |
| Headings, display, stat values | **Bricolage Grotesque** | 600 heading, 700 display and hero |
| Body, UI | **Karla** | 400 to 600 |

Bricolage Grotesque is shared with AdmitMe. It is the "product sibling" signal across the family.

## Shape and motion

- `--radius-brand: 15px`. Pills for eyebrows and chips.
- 1px hairlines only. Shadows on hover-elevated cards and the nav dropdown, nowhere else.
- Motion tokens: quick `.18s`, standard `.32s`, slow `.48s`, ease `cubic-bezier(.4,0,.2,1)`, entrance `cubic-bezier(.16,1,.3,1)`, reveal distance `24px`, stagger `80ms`. Everything decorative collapses under `prefers-reduced-motion`.

## Files

| File | What it is |
| :-- | :-- |
| `crowdsense-logo.svg` | Horizontal lockup, mark plus wordmark. Dark-on-transparent, viewBox 139.5 x 36. Paint on white or light bands. |
| `crowdsense-mark.svg` | The three-bar mark alone, centred on a white square. Source of the org avatar. |
| `crowdsense-avatar.png` | 1024 x 1024 render of the mark. The org avatar. |

The og card for social is served live at `https://crowdsense.events/og/index.png` (1200 x 630).

## The family

| Brand | Accent | Ground | Display face |
| :-- | :-- | :-- | :-- |
| [Artefact Group](https://github.com/artefactgroup) | coral `#FF5757` | warm near-black `#171710` | Syncopate, Space Mono labels |
| **CrowdSense** | blue `#0000ee` | white | Bricolage Grotesque + Karla |
| [AdmitMe](https://github.com/AdmitMe-io) | orange `#ff6431` | `#171710` on dark, white on light | Bricolage Grotesque + Inter |

In ecosystem diagrams, CrowdSense is always the blue layer and AdmitMe is always the orange layer.
