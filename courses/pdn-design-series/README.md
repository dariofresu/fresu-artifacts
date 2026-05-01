# PDN Design Series — Fresu Electronics

**Date:** 2026-05-01  
**Status:** Draft — ready for review  
**Topic:** Power Delivery Network design for high-speed PCBs

## Resources

| File | Format | Description |
|------|--------|-------------|
| `pdn-explainer.html` | Scroll guide | 8-section editorial explainer with SVG diagrams, ~25 min read |
| `pdn-minicourse.html` | Interactive course | 10 chapters, quiz after each, progress tracking |
| `pdn-cheatsheet.html` | Reference card | A4 landscape, print-ready, all formulas + rules |
| `pdn-wizard.html` | Decision tool | 5-question wizard → personalised PDN recommendations |
| `pdn-bundle.html` | Sales page | Landing page presenting all 4 resources as a product set |

## Topics Covered

1. Field theory — energy in dielectric, not copper
2. Target impedance — Z = V_noise / I_inst, f_max = 0.5 / t_rise
3. Via inductance — spacing dominates, not size (60% rule)
4. Capacitor mounting — end vs side vias, polarity rules
5. Decoupling strategy by rise time — slow vs high-speed boards
6. Plane inductance — per-square, IC placement impact
7. Board stackup — 4-layer traps, copper pour fix, 10x improvement
8. Capacitor orientation around BGAs — alternating polarity study
9. On-package & on-die decoupling (OPD / ODC)
10. 10 rules to apply before layout

## Notes

- All content is original Fresu Electronics IP, copyright protected
- No speaker names, event names, or third-party attribution
- Brand: dark bg #0a0a0a, accent #00FF94, Poppins font, Fresu logo
- Source transcript: Rick Hartley PDN lecture (used as technical reference only — fully rewritten)
