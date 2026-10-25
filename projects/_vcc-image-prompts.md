# Image prompts for the Virtual Cell Challenge page

Not rendered by Quarto (the leading underscore keeps it out of the site).

## How to drop an image in

1. Generate the image, export it as `.webp` (about 1600 px wide) and save it under `assets/vcc/` with the filename listed below.
2. In `projects/virtual-cell-challenge.qmd`, find the `<figure class="vcc-slot" id="img-XX">` block and replace the whole `<div class="vcc-slot-frame">…</div>` with:

   ```html
   <img class="vcc-illustration" src="../assets/vcc/FILENAME.webp" alt="ALT TEXT">
   ```

3. Add `assets/vcc/` to `project.resources` in `_quarto.yml` if Quarto doesn't pick the files up automatically.

## Shared style (paste this at the start of every prompt)

> Editorial science illustration for a personal research blog. Flat, hand-drawn ink line work in warm charcoal (#292722) with soft watercolour fills in terracotta (#c96545), sage green (#687f73), peach (#f1dfd1) and wheat (#f1e7d5), on a warm cream paper background (#f7f3ea). Calm, friendly, slightly playful, generous empty space, no gradients, no 3D, no photorealism. No text or labels inside the image unless asked. Wide 16:7 landscape format.

---

### 01 · Hero · `vcc-01-hero.webp` (16:6)

A single cell drawn as a small round city at dusk, seen from slightly above. Streets are like branching threads, little houses are lit windows. On one side, a tiny control panel with a row of switches; one switch is flipped off and highlighted in terracotta. From that switch, a gentle ripple spreads across the city: some windows brighten, some dim, most stay the same.

Alt: A cell drawn as a small city where flipping one switch changes lights across the streets.

### 02 · The question · `vcc-02-transfer.webp`

Two cells side by side. Left cell: well-known, with a clear ripple pattern of up and down arrows drawn inside it, small notebook pages around it (measured experiments). Right cell: a different shape and colour, calm and at rest, with a soft dashed question mark where its ripple pattern should be. A curved arrow from left to right, labelled "transfer?" (this one label is allowed).

Alt: A known perturbation response on one cell type, and a question mark over a new cell type.

### 03 · Direction vs size · `vcc-03-direction-size.webp`

A thick arrow that splits into two strands. The upper strand (direction) receives many small thin lines from a crowd of tiny figures (many weak voices). The lower strand (size, drawn as a ruler) is held only by five sturdy figures. The two strands join again into one arrow on the right.

Alt: A prediction split into direction, voted on by many small sources, and size, decided by a trusted core.

### 04 · Same totals, different cells · `vcc-04-redistribution.webp`

Two rows of eight glass jars. Top row: each jar holds exactly the same small stack of sugar cubes, perfectly uniform. Bottom row: the jars hold uneven, natural-looking amounts. Beside them, a balance scale shows both rows weigh the same.

Alt: Same total spread evenly versus naturally across cells.

### 05 · Routing branches · `vcc-05-routing.webp`

A small railway junction from above. Three little trains marked A, B and C arrive from the left. A signal box looks at each one through a magnifying glass. Two tracks leave to the right, one leading to a station shaped like a stem cell (H1), the other to a station shaped like a T cell (CD4). Train A heads to one station, B and C to the other.

Alt: Validation contexts being routed to different source branches based on how their controls look.

### 06 · More is not better · `vcc-06-backpack.webp`

A hiker struggling up a gentle hill with a comically overstuffed backpack, items poking out: folded maps, extra masks, a big volume knob, many notebooks. Next to them, a second hiker with a small neat pack walks past easily and a little ahead.

Alt: An overloaded hiker beside a lighter hiker who is moving faster.

### 07 · Removing background noise · `vcc-07-denoise.webp`

A messy, tangled sound wave enters a pair of over-ear headphones from the left and leaves on the right as a clean, distinct melody line in terracotta. A soft grey hum floats away above the headphones, drawn as faint wavy lines.

Alt: A noisy signal passing through headphones and coming out clean, with the background hum removed.

### 08 · Final choice · `vcc-08-crossroads.webp`

A traveller at a crossroads holding two maps. One is shiny and new but has large blank areas. The other is older, creased and well-worn, with a route already traced in terracotta. The traveller follows the worn map toward three small doors in the distance marked D, E and F.

Alt: Choosing the well-tested map over the newest one before walking to three new doors.

### 09 · Big models vs simple tool · `vcc-09-models.webp`

A row of big, shiny, complicated machines with blinking lights, dials and tubes. At the end of the row, a small, well-used wooden hand tool on a workbench. A tape measure across the bottom shows the hand tool's mark landing closest to a target line.

Alt: Large complicated machines next to a simple tool that lands closest to the target.

### 10 · The practice exam · `vcc-10-practice-exam.webp`

A student stands in a corridor holding a practice test with a big circled A on it. In front of them is a closed exam-hall door. Through the keyhole you can see part of a different-looking exam paper with unfamiliar shapes.

Alt: A student with a good practice test facing a closed door with a different exam behind it.
