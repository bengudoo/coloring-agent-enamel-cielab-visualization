# Coloring agent, enamel thickness and CIELAB

Interactive 3D visualization of the colour coordinates of resin composite specimens intrinsically characterized with ochre and yellow coloring agents and layered with enamel composite of two thicknesses.

**[View the visualization →](https://bengudoo.github.io/coloring-agent-enamel-lab-visualization/)**

## What it shows

Two panels side by side, one for each enamel thickness. Each panel plots the L\*, a\* and b\* coordinates of 50 specimens inside the CIELAB colour space.

| Encoding | Meaning |
|---|---|
| Yellow | Yellow coloring agent |
| Ochre | Ochre coloring agent |
| Blue | Control, no coloring agent |
| Square | High amount applied |
| Circle | Low amount applied |
| Triangle | Control |

All three axes share one scale, so a given distance means the same thing whichever direction it runs. The sphere is a reference frame of radius 60 centred on L\* 50; it is not a gamut boundary.

## How to use it

- **Drag** to rotate, **scroll** to zoom, **shift-drag** to pan
- **Whole space / Zoom to specimens** switches between the overview and a close view of the cloud
- **Linked views** keeps both panels at the same angle so the two thicknesses can be compared directly
- **Read-off grid** drops a stem from every specimen onto the a\*–b\* plane, where each grid square is 2 units of a\* by 5 of b\*
- Click any legend entry to hide or show that group
- Hover a specimen for its number and exact coordinates

## Specimens

100 specimens in 10 groups of 10, in a 2 × 2 × 2 design (two coloring agents × two amounts × two enamel thicknesses) plus a thickness-matched control for each thickness. Each specimen is a dentin composite disc carrying the coloring agent, covered by an enamel composite layer of 0.5 mm or 1.0 mm. Colour coordinates were recorded with a spectrophotometer against a grey background.

## Running it locally

`index.html` is self contained: the coordinates are embedded in the file. Download it and open it in any browser, no server needed. It loads three.js and one webfont from public CDNs, so the first open needs an internet connection.
