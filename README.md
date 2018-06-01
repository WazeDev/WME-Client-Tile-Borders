# WME-Client-Tile-Borders

Displays the borders of the tiles that are built during the nightly cycle. Tiles are built for multiple client zoom levels, the borders displayed represent only the most zoomed-in level.

The borders are turned on and off via the Layers menu.

## Intended Audience

Most editors will not have a need to see where the tile borders are on a regular basis, outside of curiosity. There are some scenarios where this is useful, however:

- Which trigger objects are on the same tile as an area place polygon that can be used to force a tile update.
- Explaining partial or odd area place polygons in the client.
- Helping to diagnose very rare issues when objects cross tile borders.

## Disclaimer

While I am reasonably certain that the borders displayed are accurate based on our existing knowledge of map tiles followed by observations and testing in the client, this has not been confirmed.  