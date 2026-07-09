# DBiased Design System

This repository packages a design system extracted from the current `dbiased.com` site so it can be handed to Claude Design or reused for future DBiased pages.

## Source Of Truth

The live site currently establishes these brand cues:

- High-contrast orange and violet palette
- `Exo 2` typography
- Compact, centered layout
- Animated gradient background
- Short, confident copy
- Simple form interactions with strong borders

## Design Principles

1. Signal over noise
2. Bold color over neutral corporate defaults
3. One strong message per screen
4. Thick borders, crisp edges, minimal decoration
5. Motion should feel ambient, not distracting

## Repository Contents

- `tokens/design-tokens.json` - machine-readable token set
- `tokens/design-tokens.css` - CSS custom properties
- `components/component-specs.md` - UI component guidance
- `claude/claude-design-brief.md` - ready-to-paste design prompt

## Recommended Usage

Use the tokens first, then adapt layouts around the following patterns:

- Hero sections with one dominant headline
- Centered capture forms
- Strong CTA buttons with dark fills and warm labels
- Data cards and stat blocks with thick borders
- Slow gradient motion or other ambient background movement

## Brand Voice

- Direct
- Analytical
- Slightly contrarian
- No filler
- Minimal but not sterile

## What Not To Do

- No generic SaaS gradients
- No pastel palettes
- No thin, airy UI chrome
- No overloaded dashboards
- No whimsical illustration style unless it serves a clear purpose

## Hand-off Notes For Claude Design

When generating concepts from this system, keep the work grounded in the live site:

- Use the orange / violet contrast as the primary visual anchor
- Preserve the compact, centered structure for simple pages
- Keep typography bold and legible
- Keep animation restrained and intentional
- Use the tokens instead of inventing a new palette

