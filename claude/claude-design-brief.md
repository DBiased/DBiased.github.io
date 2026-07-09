# Claude Design Brief For DBiased

Use this brief when generating new pages or redesign concepts for DBiased.

## Context

DBiased is a market-intelligence brand with a compact, confident, high-contrast web presence. The live site uses a bold orange and violet palette, Exo 2 typography, a centered composition, and subtle animated gradient movement.

## Objective

Design pages that feel like DBiased:

- Analytic
- Direct
- Contrarian
- Energetic
- Minimal, but not generic

## Hard Constraints

1. Keep the orange / violet color relationship intact.
2. Use Exo 2 or a close geometric sans with a similar personality.
3. Prefer one clear message over multiple competing blocks.
4. Keep motion ambient and restrained.
5. Use thick borders, crisp contrast, and compact spacing.

## Visual Direction

- Backgrounds can be full-bleed warm gradients
- Headlines should be short and strong
- Forms should feel simple and decisive
- Supporting UI should use cream or white surfaces
- Data and callouts should read like signal, not decoration

## UI Notes

- Avoid generic SaaS chrome
- Avoid pastel color systems
- Avoid soft glass overlays
- Avoid a cluttered marketing homepage
- Avoid playful illustration unless it clearly supports the message

## Suggested Building Blocks

- Centered hero with one market statement
- Strong CTA button
- Email capture or single action form
- Stat blocks or compact signal cards
- Subtle motion on background only

## Token References

- Colors: `tokens/design-tokens.json`
- CSS variables: `tokens/design-tokens.css`
- Component rules: `components/component-specs.md`

## Copy Tone

Keep copy:

- Short
- Assertive
- Market-aware
- Slightly skeptical

Example tone:

- "Market logics are shifting."
- "Signal over noise."
- "Track the move before the crowd names it."

## Deliverable Prompt

If you want a single prompt to give Claude Design, use this:

> Design a DBiased page using the provided tokens and component rules. Preserve the orange/violet identity, the Exo 2 typographic feel, and the compact centered structure. Make it feel like a sharp market-intelligence brand, not a generic SaaS product. Use bold borders, warm gradients, restrained motion, and short analytical copy. Avoid pastel colors, glassmorphism, and crowded layouts. Keep the design confident, minimal, and high-contrast.

