# UI Review

Date: 2026-04-14
Project: DevChell Portfolio

## Overall

Score: 21/24

This pass focused on reducing the oversized feel of the first implementation
while preserving the Figma composition, the typography weight hierarchy, and
the editorial/code-driven visual language.

## Pillars

| Pillar | Score | Notes |
|-------|-------|-------|
| Copywriting | 4/4 | Clear, direct, and aligned with a portfolio/service site. |
| Visuals | 3/4 | Strong Figma fidelity preserved. Project card and contact shell were compacted for better viewport fit. |
| Color | 4/4 | Light/dark themes remain consistent and readable. |
| Typography | 3/4 | Primary UI scale was reduced and code areas now read more like an IDE. |
| Spacing | 3/4 | Major vertical excess was removed from hero, sections, and form. |
| Experience Design | 4/4 | Section lock was removed, scroll is now free, and mobile layout is significantly cleaner. |

## Main Findings

1. The previous version felt zoomed because multiple sections were using full-screen
   proportions plus large internal gaps at the same time.
2. The contact form was visually faithful but too inflated for desktop and mobile,
   especially in the code-simulated area.
3. The projects card needed a dedicated mobile pass so the arrows, external link,
   and summary could coexist without overlap.

## Fixes Applied

- Reduced desktop container widths and global section spacing.
- Reduced hero title, supporting text, button sizes, and vertical gaps.
- Removed forced wheel-lock section behavior and kept smooth free scroll.
- Rebalanced About, Projects, and Contact proportions for more natural viewport fit.
- Switched code-style areas to a more IDE-like reading rhythm using the mono font
  with tighter spacing and smaller scale.
- Reworked the contact shell into a cleaner grid layout.
- Improved mobile project card spacing and separated the external link from the
  navigation arrow cluster.

## Residual Notes

- The portfolio still intentionally feels bold and editorial, but it no longer
  depends on oversized spacing to create impact.
- If a future pass is needed, the next area to refine would be project imagery
  art direction rather than layout scale.
