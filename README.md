# structural-isometrics

Animated, isometric line studies of structural models. Each page is one looping black-and-white animation; move across the drawing to scrub it, or pick a stage from the rail underneath.

- [`concrete-hairline/index.html`](concrete-hairline/index.html): a concrete beam, built in eleven stages: dimensions, keypoints, lines, area, volume, partition, materials, mesh, supports, loads and cracking.
- [`turbine-foundation/index.html`](turbine-foundation/index.html): a tabletop turbine-generator foundation, built in ten stages: column grid, keypoints, frame, raft plan, volumes (raft, columns, beam-grid table top), materials, mesh, soil springs, the machine with its unbalance, and the first two vibration modes.
- [`pump-foundation/index.html`](pump-foundation/index.html): a pump pedestal foundation, built in eleven stages: outline, keypoints, lines, footing area, volumes (footing, cast-in anchor bolts, pedestal pour), grout and baseplate with nuts, materials, mesh, piles, the pump and motor running, and two vibration modes (rocking and torsion).
- [`building-substructure/index.html`](building-substructure/index.html): the substructure of an industrial building, built in five stages against a fixed grade datum: slabs (outlines at four floor levels: hall +1′-0″, dock +4′-0″, office +1′-6″, pit −3′-0″), walls (room walls, then pit walls), slab on grade (hall one foot above grade, then dock and office, then pit), materials, and mesh. No footings. Heights are drawn at an exaggerated scale.

Both are drawn on the [hairline](https://github.com/lucasmarkes/hairline) kernel by Lucas Marques (MIT), inlined unchanged. The pages are written as artifact bodies (no `<html>`/`<head>` wrapper); opened directly in a browser they still render. Deflections, crack patterns and mode shapes are illustrative sketches, not analysis output.
