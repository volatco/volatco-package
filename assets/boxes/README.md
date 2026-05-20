# Volatco board box set

## Files

- VOLxx mockup: `VOLxx-box.svg`
- VOL00 mockup: `VOL00-box.svg`
- VOL01 mockup: `VOL01-box.svg`
- Cartheur logo asset: `cartheur-logo.jpg`
- Folding dieline: `volatco-folding-pattern.svg`
- VOL00-only dieline: `vol00-folding-pattern.svg`
- 3D folded render: `volatco-box-3d-render.svg`
- Dieline notes: `FOLDING-PATTERN.md`

## Approximate folded 3D render

Palette aligned to Cartheur logo colors sampled from `cartheur-dark-sm.jpg`: primary `#101010`, accent `#20F8A8`.
The actual Cartheur logo is rendered on the SVG assets via `cartheur-logo.jpg`.

![Approximate 3D render of folded Volatco box](./volatco-box-3d-render.svg)

## Mechanical and physical specification

### Reference geometry

- Bare board size (from Volatco docs): **60 x 40 x 15 mm**
- ESD protective wrap: **3 mm bubble wrap per side**
- Wrapped board envelope: **66 x 46 x 21 mm**
- Assembly clearance allowance: **+2 mm each axis**
- Final internal box size target: **68 x 48 x 23 mm**

### Box style and panel construction

- Style: **Straight-line folding carton** (reverse tuck top + friction bottom)
- Glue seam: **12 mm** side glue flap (PVA or hot-melt compatible)
- Main panels:
  - Front/back: **68 x 48 mm**
  - Side panels: **23 x 48 mm**
- Closing flaps:
  - Top flap depth: **25 mm**
  - Bottom flap depth: **25 mm**

### Recommended substrate (paperboard)

Optimal target for this small electronics carton:

- Material: **SBS C1S folding boxboard** (Solid Bleached Sulfate, coated one side)
- Caliper (thickness): **0.50 mm** nominal (approx. 20 pt)
- Basis weight range: **350-400 gsm**

Alternative grades:

- Lightweight option: **0.40 mm (16 pt), ~300-325 gsm**
- Heavy-duty option: **0.60 mm (24 pt), ~420-460 gsm**

### Mechanical targets and tolerances

- Carton should remain closed under normal handling with no tape.
- No visible panel crease whitening on first fold.
- No side wall buckling when lightly squeezed by hand.
- Minimum top-panel load target (static): **1.5 kg** without permanent deformation.
- Die-cut tolerance: **+/-0.20 mm**
- Score-to-score tolerance: **+/-0.15 mm**
- Internal dimension tolerance after folding: **+/-0.5 mm**
- Recommended crease width for 0.50 mm SBS: **1.0-1.2 mm**

### ESD and finish notes

- Use **anti-static pink bubble wrap** or **metallized ESD bubble** at 3 mm thickness.
- Optional ESD shielding bag can be added if total extra film thickness is <=0.2 mm.
- Exterior print: CMYK + optional spot color for Cartheur mint accent `#20F8A8`.
- Finish: **Matte aqueous coating** preferred.
- Keep critical text/marks at least **3 mm** inside cut edges.

## Summary recommendation

Use **SBS C1S, 0.50 mm, 350-400 gsm** with internal dimensions **68 x 48 x 23 mm**, reverse tuck top/friction bottom closure, and **3 mm anti-static bubble wrap** around the board.
