# Design Spec

## Direction
- **Art direction:** 
- **Impressions (max 3):** 
- **Signature element:** what a visitor must remember after 10 seconds.
- **References:** what is borrowed (layout / type / color / motion / tone) and what is rejected. No bare URLs.

## Principles
3–5 rules that decide trade-offs, each with a consequence. Example: "Density over decoration → no illustration inside data views."
Avoid words that decide nothing ("modern", "clean", "premium") unless backed by a rule below.

## Tokens
| Token | Value | Use |
| --- | --- | --- |
| `--bg` | | page background |
| `--surface` | | cards, panels |
| `--text` | | body |
| `--text-muted` | | secondary |
| `--accent` | | primary action only |
| `--border` | | dividers |
| `--radius-*` | | per component class |
| `--space-*` | 4/8/12/16/24/32/48/64 | spacing scale |
| `--font-display` | | headlines |
| `--font-body` | | text |
| `--type-scale` | | sizes per step |
| `--ease`, `--dur` | | motion |

Contrast pairs must be checked, not assumed: text/bg, text/surface, text/accent, focus ring/bg.

## Layout
Grid columns, max width, gutters, breakpoints, hero composition, density per page.
Responsive behavior: what changes, what collapses, what hides (and why hiding is acceptable).

## Components
Per component: purpose, variants, states (default/hover/focus/active/disabled/loading/empty/error), and what it must not do.

## Motion
Intensity, one-liner purpose per animation, trigger, duration/easing, library, reduced-motion fallback. Motion that serves no UX goal is removed.

## Accessibility
Target level, contrast targets, keyboard path per interactive region, focus-visible style, screen-reader labels, text resize behavior.

## Do / Don't
| Do | Don't | Why |
| --- | --- | --- |
