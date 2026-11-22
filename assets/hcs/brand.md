# HyperColorSignal — Brand Guidelines (for LLMs and humans)

Use this file as the source of truth when writing copy, building UI, or generating assets for HyperColorSignal (HCS). Follow it over generic style defaults.

Items marked **(proposed)** are starting points that have not been confirmed by the HCS team. Use them when nothing else is specified, and don't present them as fixed rules.

## 1. Who we are

- HyperColorSignal is a collective in Fortaleza, Ceará, building open-source software that puts control back in people's hands, away from Big Tech and corporate lock-in.
- We build in the open and are community-first. Our community includes LGBTQ+ people.
- Web: hypercolorsignal.dev · Email: hey@hypercolorsignal.dev · GitHub: github.com/hypercolorsignal
- Name: the wordmark is always lowercase (**hypercolorsignal**). In running text write **HyperColorSignal**; short form **HCS**. (proposed, confirm the official casing)

## 2. Voice and tone

Friendly, a little hip, always one of us. We sound like a friend who happens to build open-source tools. (The voice traits below are proposed from "friendly and hip, community-first".)

- **Warm.** Use "we" and "you". Welcome people in. Say thanks. Make invitations feel real.
- **Hip, not hype.** Relaxed and a bit playful; lowercase moments are fine on social. Don't chase slang or buzzwords.
- **Inclusive.** Use people's own names and pronouns. Avoid assumptions about gender, family, or background. Keep jokes kind.
- **Plain-spoken.** Short sentences. No jargon walls. Explain technical terms for newcomers.

Say (from the GitHub profile): "We build in the open." / "Share an idea, or lend a hand." / "We'd love to hear from you!"

Don't say: corporate filler ("leverage our cutting-edge synergies"), cold rule-speak ("Users must comply"), or shouty hype ("BEST. TOOL. EVER.").

Tone by context:
- Docs and READMEs: clear and calm. Friendly intro, then straight to steps.
- Social and community: most playful.
- Errors and moderation: gentle and direct. Say what happened and what to do next. No jokes.

## 3. Logo

Marks (all built on the same orbit: italic lettering, tapered spectrum orbit, gold four-point flare):
- **Primary wordmark** — [`brand/wordmark.svg`](brand/wordmark.svg) (optimized: [`brand/wordmark.min.svg`](brand/wordmark.min.svg)). White lettering; use on dark grounds.
- **HCS monogram** — [`brand/hcs-monogram-dark.png`](brand/hcs-monogram-dark.png) and [`brand/hcs-monogram-light.png`](brand/hcs-monogram-light.png). Square and tight spaces: avatars, social profiles, stickers.
- **Circular symbol** — [`brand/circular-icon.svg`](brand/circular-icon.svg) (optimized: [`brand/circular-icon.min.svg`](brand/circular-icon.min.svg)); app/store icon: [`brand/app-icon-512.png`](brand/app-icon-512.png); favicon: [`brand/favicon-32.png`](brand/favicon-32.png).

Rules:
- Clear space (proposed): on every side, at least the height of the lowercase "h" in the wordmark.
- Minimum size (proposed): wordmark 120px wide on screen; monogram 32px.
- Don't stretch, recolor, re-tilt, retype in another font, remove the orbit or flare, or put the white wordmark on a light or busy background.

## 4. Color

| Name | Hex | Role |
|---|---|---|
| Signal pink | `#F532DC` | Start of spectrum |
| Signal coral | `#F8647B` | 32% along spectrum |
| Signal orange | `#FB846C` | 64% along spectrum |
| Signal gold | `#FDC563` | End of spectrum, the flare, focus ring |
| Ink | `#050505` | Page ground |
| Panel | `#090909` | Cards and panels |
| White | `#FFFFFF` | Wordmark, headlines |
| Body gray | `#C4C4C4` | Body text on ink |
| Muted | `#AAAAAA` | Labels, captions |
| Line | white at 15% | Borders |

Spectrum gradient: `linear-gradient(100deg, #f532dc 0%, #f8647b 32%, #fb846c 64%, #fdc563 100%)`.

Use the gradient for the orbit, thin rules, primary buttons and one accent word. Never for body text or full-page backgrounds. Color stays in small, deliberate places.

Contrast on ink: pink 6.2:1, coral 6.9:1, orange 8.4:1, gold 13.0:1, white 20.4:1. All pass for text on dark. On white, signal colors are only 1.6–3.3:1 and fail for body text (pink and coral reach 3:1 for large text only); use ink (20.4:1) for type on light grounds.

## 5. Typography

System: **A · Product**. This is the official pairing. (Alternatives explored and not selected: Gabarito + Newsreader + Inter; Gabarito + DM Sans + DM Mono; Gabarito + Inter + Fraunces italic accent. Don't mix them in.)

| Role | Font | Weights |
|---|---|---|
| Headlines, display, wordmark | Gabarito | Bold 700 for headlines; ExtraBold 800 for the wordmark and impact; Black 900 rarely |
| Body, captions, labels, UI | Inter | Regular 400, Medium 500, SemiBold 600 |
| Code, data, emails, URLs | JetBrains Mono | Regular 400 |

All are free on Google Fonts. Fallbacks: Gabarito → Arial, sans-serif · Inter → Arial, sans-serif · JetBrains Mono → monospace.

Scale:
- Display: Gabarito 60px / 1.0, Bold, tracking −0.045em (proposed size)
- Heading: Gabarito 29px / 1.15, Bold, tracking −0.04em
- Body: Inter 16px / 1.6, Regular, color `#C4C4C4` on ink
- Caption: Inter 13px / 1.65, Regular, tracking +0.015em
- Label: Inter 12px, Medium 500, tracking +0.15em, uppercase, color `#AAAAAA`

## 6. Layout and UI

- Dark by default: ink `#050505` ground, `#090909` panels, 1px borders at white 15%.
- Radius: 18px panels, fully rounded pills for buttons; 8px for small chips (proposed).
- Page width up to 1440px; 32px side gutters (18px on phones). Spacing on an 8px base: 8, 16, 24, 32, 48 (proposed).
- Buttons: at least 44px tall. Primary = spectrum gradient fill with ink text (proposed). Secondary = 1px white-30% border, white text.
- Focus: 2px gold outline, 5px offset. Respect `prefers-reduced-motion`.
- Icons in interfaces (proposed): simple 2px outline strokes in white or one signal color.
- Social images (proposed): Open Graph 1200×630 (wordmark centered on ink); banner 3:1 (wordmark left, one short line); square 1:1 (monogram with headline below).

## 7. Quick checklist

1. Dark ground, thin borders, rounded panels?
2. Gabarito for headlines, Inter for body and labels, JetBrains Mono for code?
3. Color limited to small accents, gradient used sparingly?
4. Text contrast passes on its background?
5. Copy sounds warm, plain and inclusive, with no corporate filler?
6. Logo has clear space, correct version for its background, and is unaltered?
