# Bank Network Briefing Design

## Visual Direction

Executive progress report in a KFTC poster-inspired light product style. The deck uses a print-friendly white canvas, precise information hierarchy, thin blue-gray borders, and sparse KFTC blue accents. The tone is confident, operational, and understated: the executive should quickly read that the roundtable is on track, participating banks are responding well, and the agenda is practically useful.

## Tokens

- Page background: `#ffffff`
- Panel background: `#f7fbff`
- Elevated surface: `#eef6ff`
- Hover/elevated surface: `#e6f0fb`
- Primary text: `#101828`
- Secondary text: `#26384f`
- Muted text: `#5b6b80`
- Quiet text: `#7a8798`
- KFTC blue: `#006fd6`
- Poster sky blue: `#23a8e0`
- Deep navy: `#003b71`
- Success green: `#0f8f63`
- Border standard: `rgba(0,77,153,0.16)`
- Border subtle: `rgba(0,77,153,0.10)`

## Typography

- Primary font: Paperlogy, then Noto Sans KR and system sans fallbacks.
- Monospace-style labels: Paperlogy. Do not switch captions, stat labels, or footer notes to a separate monospace font.
- Use Paperlogy weights 400, 500, and 600. Avoid heavier weights for print readability.
- Letter spacing is kept at `0` across the deck for predictable Korean rendering and layout stability.

## Components

- Stat panels: pale blue surface, 1px blue-gray border, 8px radius, large numeric focus.
- Agenda steps: numbered mono labels, strong title, concise operational outcome.
- Quotes/opinions: paraphrased bank reactions in compact evidence blocks, not decorative testimonials.
- Network diagrams: abstract lines and nodes only; no busy architecture detail.
- Accent usage: reserve KFTC blue for progress, active emphasis, and executive conclusion.

## Layout

- 1920x1080 composition.
- Generous white space with max-width text blocks.
- No nested cards.
- Text wraps naturally with `word-break: keep-all` and conservative line lengths.
- Repeated cards are capped at 8px radius.
