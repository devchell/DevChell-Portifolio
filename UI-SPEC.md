# UI Spec

Date: 2026-04-14
Project: DevChell Portfolio

## Direction

Refine the portfolio into a sharper monochrome editorial interface with code-native personality, elevated surfaces, and purposeful motion. The design should feel premium, technical, and clean without relying on borders, dividers, glass effects, or tinted backgrounds.

## Visual Principles

- Light mode uses neutral black, white, and grayscale only. No off-white drift.
- Dark mode uses dark grayscale only. No blue bias.
- Borders are not part of the visual language; separation comes from spacing, mass, and shadow.
- Buttons, arrows, and social controls should feel lifted and tactile, not flat.
- Code surfaces keep mono typography and stronger structure than the rest of the UI.

## Layout Contract

- Navbar: compact floating shell, quieter than before, with active state defined by contrast rather than framing.
- Hero: left side communicates authority, right side provides animated code credibility.
- About: reading block and code block stay balanced, with facts treated as elevated tokens.
- Projects: screenshot stage first, content tray second; CTA and stacks must remain in fixed spatial roles.
- Contact: fully integrated code simulator with input focus states and action buttons that feel elevated.
- Footer: two anchored sides, never centered as a whole; left for contact, right for socials, signature below.

## Typography

- Main UI copy uses the primary sans font.
- `</devchell>` in the footer uses JetBrains Mono only, but keeps the surrounding text weight and rhythm.
- Code emulators use mono font exclusively.
- Headlines stay bold and high-contrast, but body text should remain calm and readable.

## Motion Contract

- Reveal animations should be smooth and editorial, not flashy.
- Code lines can stagger in with subtle timing.
- Hero editor may float gently to add life.
- Project screenshots should drift slightly while active, and project metadata should re-enter when the project changes.
- All motion must respect `prefers-reduced-motion`.

## Component Rules

- Primary and secondary CTAs use shadow depth instead of outlines.
- Project visit button and carousel arrows should feel like tactile controls with soft elevation.
- Stack badges should feel lightweight, compact, and stable across projects.
- Form fields in the code simulator should respond on focus through motion and surface change, not borders.

## Quality Bar

- The interface must look intentional in both light and dark mode.
- No visible border lines should be required for structure.
- Motion should clarify hierarchy and interaction, never distract from content.
- Desktop and mobile must preserve the same visual story and CTA clarity.
