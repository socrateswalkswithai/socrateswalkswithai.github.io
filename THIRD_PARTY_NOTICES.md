# Third-party notices

## GSHHG shoreline data

`engine/greece-islands-shapes.js` contains simplified/projected geometry derived at build time from the Global Self-consistent, Hierarchical, High-resolution Geography Database (GSHHG), accessed through the locally installed Basemap data package.

GSHHG is maintained by Paul Wessel and Walter H. F. Smith and is distributed under the GNU Lesser General Public License. The application has no runtime dependency on Basemap or GSHHG.

## Greece former-prefecture outline

`engine/greece-islands-shapes.js` also contains former-prefecture (nomos) internal/terrestrial boundary information derived at build time from the public-domain historical outline **File:Greece prefectures map.png** on Wikimedia Commons. In v382 those historical lines are combined at build time with the unchanged GSHHG coastline to reconstruct the prefecture faces; the source raster is not bundled and the application has no runtime dependency on Wikimedia or any mapping service.
