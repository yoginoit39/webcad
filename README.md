# WebCAD

A web-based 2D CAD tool for architectural drafting. Single self-contained HTML file — no install, no build, no backend. Runs in any modern browser.

Inspired by [Rayon Design](https://www.rayon.design).

## Try it

Open `index.html` in any browser, or visit the deployed version.

## Features

**Drawing**
Line · Polyline · Rectangle · Circle · Arc (3-point) · Ellipse · Text · Linear dimension · Hatch

**Architect-specific**
Wall (with thickness + auto-mitered corners) · Door (with swing arc) · Window (in-wall double-line) · Room (auto-detects enclosed boundary, computes area)

**Modify**
Erase · Move · Copy · Rotate · Mirror · Scale · Offset · Trim · Fillet

**Drafting aids**
Object snap (endpoint, midpoint, center, quadrant, intersection, perpendicular, grid, alignment tracking) · Ortho · Polar tracking · Grid · HiDPI rendering

**UI**
Light + dark themes · Layer system (visibility, lock, color) · Properties panel · Component library (bed, sofa, toilet, sink, bathtub, etc.) · AutoCAD-style command bar · Hover tooltips · Help overlay (`?` button)

**File**
JSON save/open · SVG export · PNG export · 100-level undo/redo · Copy/paste

## Keyboard shortcuts

| Key | Tool |
|---|---|
| `W` | Wall |
| `D` | Door |
| `WIN` | Window |
| `R` | Room |
| `L` | Line |
| `PL` | Polyline |
| `REC` | Rectangle |
| `C` | Circle |
| `A` | Arc |
| `M` / `CO` / `RO` / `MI` / `SC` | Move / Copy / Rotate / Mirror / Scale |
| `E` / `Delete` | Erase |
| `F3` / `F7` / `F8` / `F10` | Snap / Grid / Ortho / Polar toggles |
| `Ctrl+Z` / `Ctrl+Y` | Undo / Redo |
| `Ctrl+S` / `Ctrl+O` | Save / Open |

Press the `? Help` button in the top bar for the full reference.

## Tech

Pure vanilla JavaScript + HTML5 Canvas. No frameworks, no dependencies, no build step. ~4,000 lines, single file.
