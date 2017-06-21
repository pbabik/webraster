# webraster

Example of using [geotiff.js](https://github.com/constantinius/geotiff.js), [plotty](https://github.com/santilland/plotty) and [OpenLayers 4](https://openlayers.org) to display GeoTIFF in the browser.

## Motivation

While GeoTIFF files are usually large and impractical to send over the wire, there are still use cases for rendering GeoTIFFs directly in the browser, especially in thematic mapping. Sometimes a low-resolution TIFF will be orders of magnitude smaller than bunch of rendered PNG tiles. This is a minimalistic example of integrating geotiff.js, Plotty and OpenLayers 4 in order to display an SRTM elevation model in GeoTIFF format on a web map.

For more functionality including changing color palette and display range, visit the [eox.at](https://eox.at/tag/geotiff/) website.

## Demo

[https://pbabik.github.io/webraster/](https://pbabik.github.io/webraster/)

