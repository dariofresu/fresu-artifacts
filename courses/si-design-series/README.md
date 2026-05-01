# Signal Integrity Design Series — Fresu Electronics

**Date:** 2026-05-01
**Status:** Draft — ready for review
**Source:** Original content based on Fresu Electronics' "Mastering EMI Control in PCB Design" Altium article series (authored by Dario Fresu) + field-centric SI framework

## Resources

| File | Format | Description |
|------|--------|-------------|
| `si-explainer.html` | Scroll guide | 8-section editorial explainer with SVG diagrams, ~30 min read |
| `si-minicourse.html` | Interactive course | 8 chapters, quiz after each, progress tracking, completion screen |
| `si-cheatsheet.html` | Reference card | A4 landscape, print-ready, all formulas + rules |
| `si-wizard.html` | Decision tool | 5-question wizard → personalised SI recommendations |
| `si-bundle.html` | Sales page | Landing page presenting all 4 resources as a product set |

## Topics Covered

1. EM field propagation — signals as fields, rise time vs clock frequency, BW = 0.35/tr
2. Return path — path of least inductance, no routing over gaps, zone vs split planes
3. Characteristic impedance — geometric control, reflection coefficient, via discontinuities
4. Reflections & termination — critical length, series/parallel/AC strategies, topology
5. Crosstalk — NEXT/FEXT, 3W rule, orthogonal routing, differential pairs
6. Ground bounce — ΔV = L × di/dt, PDN/SI convergence, decoupling strategy
7. SI routing rules — reference planes, return via, layer discipline, serpentine spacing
8. Interface-specific — DDR fly-by, SerDes AC coupling, RF/ADC boundary

## Source Material

- Primary: Dario Fresu's own "Mastering EMI Control in PCB Design" series (Altium, 6 articles)
- All content is original Fresu Electronics IP — rewritten fresh from Dario's own framework
- No external speaker transcripts used for this series

## Notes

- Brand: #0a0a0a bg · #00FF94 accent · Poppins · Fresu logo + author photo
- All cross-links between resources included
- Copyright notice embedded in each artifact
