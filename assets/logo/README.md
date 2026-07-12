# GPS OS Logo

## Concept

The mark is a **waypoint loop**: a ring that is almost — but not quite —
closed, sweeping into an arrowhead that is always chasing its way back to
a single fixed dot.

It comes directly from GPS OS's own language:

- The GPS Navigation Model is a loop that always returns to **Reality**
  (Discover → Map → Design → Build → Validate → Ship → Learn → Reality).
- *"The destination rarely changes. The route often does."* (04_Method.md)

The dot is the fixed point — reality, the mission, the problem you started
with. The ring is the route — the method, which is never quite finished
and never fully closes. It is not a literal compass rose; it is what a
compass rose becomes once you strip it down to only the part that matters.

## Palette

| Token | Hex | Use |
|---|---|---|
| Navy ink | `#1C2B49` | Primary mark / wordmark ink (light backgrounds) |
| Brass | `#BB8C3E` | Waypoint dot, accent (light backgrounds) |
| Parchment ink | `#F2ECDD` | Primary mark / wordmark ink (dark backgrounds) |
| Brass (reversed) | `#D6A94F` | Waypoint dot, accent (dark backgrounds) |
| Graphite | `#5B5A54` | Caption text, light backgrounds |
| Muted parchment | `#B9B4A6` | Caption text, dark backgrounds |

Navy and brass were chosen over a typical startup palette because GPS OS's
own subject matter is navigation instruments and trade — the mark should
read like it belongs on a chart or a compass housing, not a SaaS landing
page.

## Files

- `gps-os-mark.svg` — icon only, for favicons, avatars, small placements. Use on light backgrounds.
- `gps-os-mark-reversed.svg` — same icon, light ink, for dark backgrounds.
- `gps-os-lockup-horizontal.svg` — mark + wordmark, for repo headers, docs, slides. Light backgrounds.
- `gps-os-lockup-horizontal-reversed.svg` — same lockup, for dark backgrounds (e.g. GitHub dark mode).
- `gps-os-badge-stacked.svg` — square badge (mark above wordmark), for social cards, org avatars.
- `png/` — rasterized versions of each file above, for places that don't accept SVG.

## Usage notes

- SVGs are the source of truth — vector, so they scale to any size without quality loss.
- Don't recolor the mark outside the two palettes above; the navy/parchment pairing is what keeps it legible in both light and dark contexts.
- Minimum recommended size for the icon alone: 24px (below that the open gap in the ring starts to disappear).
- Suggested placement in the repo: `gps-os/assets/logo/`, replacing the current placeholder files.

## In the README

```markdown
<img src="assets/logo/gps-os-mark.svg" width="80" alt="GPS OS" />
```

Or for the full lockup at the top of the repo README:

```markdown
<img src="assets/logo/gps-os-lockup-horizontal.svg" width="360" alt="GPS OS — Operating System for Transforming Operational Knowledge into Reliable Software" />
```
