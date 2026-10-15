# Unit C Layout — fork of floorplan-3d

Fork of [wy51ai/floorplan-3d](https://github.com/wy51ai/floorplan-3d) (MIT) with the original 3-bedroom plan replaced by
**Unit C, 31F, Alfred House Avenue, Colombo 03**, traced from the developer's DWG of 15.10.2026.

What changed from upstream:
- `WALLS`, `WINS`, `DOORS`, `SLIDES`, `ROOMS` replaced with Unit C (façade, partitions and RC walls/columns; RC = black, cannot be demolished).
- New `OPENS` list for wall openings without a door (thresholds), and `UNITC_DIMS` with the developer's dimensions.
- Heights: ceiling 3.11 m, doors 2.4 m, façade sliders DW1/DW2/DW3 2.65 m, FL1 windows sill 1.75 m / head 2.65 m.
- Balconies are shown and floored but kept out of the net floor area.
- Default furniture is empty, English UI by default, separate local-storage key (`unitc-design-v1`).

The furniture library, 3D scene, walk mode, measure, demolish and the JSON save/load format are unchanged,
so layouts saved here open in the same format (`furniture`, `rooms`, `demolished`, `measures`).

Open `index.html` in a browser — no build step.
