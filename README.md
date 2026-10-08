# structural-isometrics

Animated, isometric line studies of structural models. Each page is one looping black-and-white animation; move across the drawing to scrub it, or pick a stage from the rail underneath.

- [`concrete-hairline/index.html`](concrete-hairline/index.html): a reinforced concrete beam, built in twelve stages: dimensions, keypoints, lines, area, volume, partition, reinforcement, materials, mesh, supports, loads and cracking.
- [`turbine-foundation/index.html`](turbine-foundation/index.html): a tabletop turbine-generator foundation, built in ten stages: column grid, keypoints, frame, raft plan, volumes (raft, columns, beam-grid table top), materials, mesh, soil springs, the machine with its unbalance, and the first two vibration modes.
- [`pump-foundation/index.html`](pump-foundation/index.html): a pump pedestal foundation, built in eleven stages: outline, keypoints, lines, footing area, volumes (footing, cast-in anchor bolts, pedestal pour), grout and baseplate with nuts, materials, mesh, piles, the pump and motor running, and two vibration modes (rocking and torsion).

Both are drawn on the [hairline](https://github.com/lucasmarkes/hairline) kernel by Lucas Marques (MIT), inlined unchanged. The pages are written as artifact bodies (no `<html>`/`<head>` wrapper); opened directly in a browser they still render. Deflections, crack patterns and mode shapes are illustrative sketches, not analysis output.
