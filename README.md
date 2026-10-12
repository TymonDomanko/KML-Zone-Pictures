# KML Zone Pictures

Open a KML or KMZ file of zones and get one map page per zone, with each zone centred and sized to fill a set percentage of the page. Export everything as a single PDF or as a zip of PNGs.

**Open the tool: https://tymondomanko.github.io/KML-Zone-Pictures/**

Runs entirely in the browser. Nothing is uploaded anywhere.

## Use it

Use the link above, or download `index.html` and open it in any browser.

1. Click **Open KML or KMZ** (or drop the file on the page).
2. Set the page size (A4 by default), orientation and how much of the page the zone should fill.
3. Pick a zone in the list or on the map to check the proof in the top-right corner. The dashed frame on the map shows what will be on the page.
4. Untick any zones you don't want, then **Export PDF** or **Export PNGs (zip)**.

## Options

| Setting | What it does |
| --- | --- |
| Page size | A5, A4, A3, A2, Letter, Legal or a custom size in mm |
| Resolution | 96–300 dpi. Map detail stays the same, only sharpness changes |
| Orientation | Auto picks whichever way gives the zone more room |
| Zone fills | Percentage of the page taken by the zone's longest side |
| Base map | Sharp vector maps from OpenFreeMap (streets, bright streets, light grey), or image tiles from OpenStreetMap and Esri (streets, light grey, satellite), or none. None need an API key |
| Street label size | Prints street names larger or smaller. Vector maps stay sharp at every size; image tiles blur when enlarged |
| Zone style | Outline colour, width and opacity, fill opacity, fade outside the zone, KML colours |
| Neighbouring zones | On or off, with their own colour (or KML colours), outline width and opacity, fill opacity, dashed or solid, names on or off |
| Summary page | Optional first page (A3 by default, up to A0) showing every selected zone with its name on top. Own size, orientation, fill and name size |
| Locator minimap | Zoomed-out map (type any multiplier, e.g. 8× wider) centred on the zone, showing the page's area, with adjustable street detail. Auto picks the corner that covers the least of the zone, or choose a corner |
| Extras | Zone name and page number, scale bar |
| Page order | File order or natural name order (1, 2, 10) |

Settings are remembered in your browser.

## Notes

- Zones must be polygons. Lines and pins are skipped. Holes in polygons are supported.
- Map tiles come from the selected provider, so you need an internet connection. If tiles fail to load you'll get a warning and those areas print grey.
- Each page credits the map provider in the bottom-right corner, as their terms require.
