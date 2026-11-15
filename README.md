# Awesome Web GIS Resources [![Awesome](https://awesome.re/badge.svg)](https://github.com/sindresorhus/awesome)

A curated collection of **useful web-based geospatial tools**, interactive GIS applications, cloud-native data explorers, map services, and cartographic design resources.

The focus is on **things you can use**, not programming libraries or frameworks. Browser-based tools, public dataset catalogs, and ready-to-use mapping services are welcome, whether open-source, free, or commercial. See [CONTRIBUTING.md](CONTRIBUTING.md) before suggesting an entry.

Inspired by [awesome-gis](https://github.com/sshuair/awesome-gis).

## Contents

- [Web GIS & Map Makers](#web-gis--map-makers)
- [Geospatial Visualization & Storytelling](#geospatial-visualization--storytelling)
- [Data Discovery & Download](#data-discovery--download)
- [Cloud-Native Geospatial & Data Catalogs](#cloud-native-geospatial--data-catalogs)
- [Data Processing, Conversion & Editing](#data-processing-conversion--editing)
- [Cartography & Map Design](#cartography--map-design)
- [3D GIS & Terrain](#3d-gis--terrain)
- [Earth Observation & Satellite Imagery](#earth-observation--satellite-imagery)
- [Coordinates, Spatial Indexing & Utilities](#coordinates-spatial-indexing--utilities)
- [Basemaps, Tiles & Map Services](#basemaps-tiles--map-services)
- [Geospatial APIs & Location Services](#geospatial-apis--location-services)
- [Related developer-oriented resources](#related-developer-oriented-resources)

## Web GIS & Map Makers

- [RustGIS Web](https://web.rustgis.app/) — Open-source GIS running in the browser, with mapping, data editing, and analysis tools.
- [GeoLibre Web](https://web.geolibre.app/) — Cloud-native GIS workspace for exploring, styling, and processing geospatial datasets in the browser.
- [Felt](https://felt.com/) — Collaborative web mapping and spatial data exploration platform.
- [uMap](https://umap.openstreetmap.fr/) — Create and share interactive maps using OpenStreetMap basemaps.
- [Instamaps (ICGC)](https://www.icgc.cat/en/Tools-and-viewers/Tools/Instamaps) — Free online map creation, customization, and publishing tool from the Cartographic and Geological Institute of Catalonia.
- [CARTO](https://carto.com/) — Cloud-native location intelligence platform for geospatial analysis, data exploration, and map applications.

## Geospatial Visualization & Storytelling

- [kepler.gl](https://kepler.gl/) — Browser-based visual exploration of large geospatial datasets, including spatial aggregations and animated trips.
- [Flowmap.blue](https://flowmap.blue/) — Create interactive maps of movements and flows between locations.
- [Datawrapper Maps](https://www.datawrapper.de/maps) — Create and publish choropleth and symbol maps for data journalism and communication.
- [Flourish](https://flourish.studio/) — Build interactive maps, animations, and data stories without writing code.

## Data Discovery & Download

### Open and global datasets

- [geodatadownloader](https://geodatadownloader.com/) — Geospatial data downloading utility.
- [Overpass Ultra](https://overpass-ultra.trailsta.sh/) — Query and explore OpenStreetMap data with Overpass.
- [Overpass Turbo](https://overpass-turbo.eu/) — Interactive Overpass query builder and map for OpenStreetMap data.
- [Overture Maps Explorer](https://explore.overturemaps.org/) — Inspect and download Overture's global buildings, places, transportation, and other map features.
- [Geofabrik Downloads](https://download.geofabrik.de/) — Download regional OpenStreetMap extracts.
- [geoBoundaries](https://www.geoboundaries.org/) — Discover and download openly licensed administrative boundaries.

## Cloud-Native Geospatial & Data Catalogs

### Catalog discovery and exploration

- [Portolan Registry](https://www.portolan-sdi.org/registry) — Discover independently hosted, cloud-native geospatial catalogs from different publishers.
- [STAC Index](https://stacindex.org/catalogs) — Browse public and protected SpatioTemporal Asset Catalog (STAC) endpoints.
- [Copernicus STAC Browser](https://browser.stac.dataspace.copernicus.eu/) — Explore and filter Earth observation products through the Copernicus Data Space STAC interface.
- [Microsoft Planetary Computer Explorer](https://planetarycomputer.microsoft.com/explore) — Browse and visualize datasets from the Planetary Computer STAC catalog.

### Large cloud-native datasets

- [Overture Maps Cloud Data](https://docs.overturemaps.org/getting-data/) — Access global geospatial datasets distributed as cloud-hosted GeoParquet; includes browser exploration and download guidance.
- [Overture Maps STAC Catalog](https://stac.overturemaps.org/catalog.json) — Browse the STAC metadata for Overture's public releases and GeoParquet assets.

## Data Processing, Conversion & Editing

### Map and geometry editing

- [Mapshaper](https://mapshaper.org/) — Edit, simplify, join, and convert vector data in the browser.
- [geojson.io](https://geojson.io/#map=2/6.8/-19.3) — Draw and edit GeoJSON features directly on a map.
- [MapTiler Vector Data Editor](https://www.maptiler.com/cloud/edit-geodata/) — Draw and edit vector map features online.

### File conversion and data validation

- [Convertbox](https://betaportal.icgc.cat/convertbox/) — Geospatial data conversion utility from ICGC.
- [GIS Toolbox](https://gis.taoliapp.com/) — Browser-based geospatial format conversion and coordinate tools.
- [GeoJSONLint](https://geojsonlint.com/) — Validate GeoJSON syntax and geometry structure.

## Cartography & Map Design

### Color and cartographic utilities

- [ColorBrewer](https://colorbrewer2.org/#type=sequential&scheme=BuGn&n=3) — Color schemes for thematic maps.
- [Bivariate choropleth color generator](https://observablehq.com/@benjaminadk/bivariate-choropleth-color-generator) — Generate bivariate choropleth palettes.
- [Colours for maps](https://observablehq.com/d/ab5d7d5a5d9e9e16) — Explore color choices for maps.
- [Chroma.js Color Palette Helper](https://gka.github.io/palettes) — Design and preview color palettes.
- [MapColPal](https://mapcolpal.org) — Color palettes for maps.
- [Airtable CartoTools](https://airtable.com/embed/shr864WB1Q2ElGRpN/tblvGdsQDCgSexAAw?backgroundColor=blue&viewControls=on) — Collection of cartographic utilities.

### Map styling tools

- [Maputnik](https://maputnik.github.io/) — Visual editor for MapLibre-compatible vector map styles.
- [MapTiler Map Designer](https://www.maptiler.com/cloud/customize/) — Customize basemap colors, typography, symbols, and layers online.
- [Maperture](https://stamen.github.io/maperture) — Compare web map styles.
- [Cartographer](https://chartographer.stamen.com/) — Inspect stylesheet properties by layer and zoom level.

### Design guidelines and inspiration

- [Esri — Primary Design Principles for Cartography](https://www.esri.com/arcgis-blog/products/arcgis-pro/mapping/primary-design-principles-for-cartography) — Guide to legibility, contrast, visual hierarchy, figure–ground, and proportion in map design.
- [Ordnance Survey — Guide to Cartography](https://docs.os.uk/more-than-maps/geographic-data-visualisation/guide-to-cartography) — Practical guide to symbols, color, typography, generalization, map layout, and other cartographic fundamentals.
- [Ordnance Survey — GeoDataViz Design Principles](https://docs.os.uk/more-than-maps/geographic-data-visualisation/guide-to-data-visualisation/geodataviz-design-principles) — Eight principles for effective and accessible geographic data visualizations.
- [Ordnance Survey — GeoDataViz Toolkit](https://github.com/OrdnanceSurvey/GeoDataViz-Toolkit) — Design guidance, color palettes, and downloadable cartographic assets.

## 3D GIS & Terrain

- [Eduard](https://eduard.earth/) — Online hillshade and terrain visualization.
- [Google Earth Web](https://earth.google.com/web/) — Explore satellite imagery, terrain, and places in a 3D globe.
- [F4map](https://demo.f4map.com/) — Interactive 3D map visualization based on OpenStreetMap data.

## Earth Observation & Satellite Imagery

### Imagery explorers

- [Copernicus Browser](https://browser.dataspace.copernicus.eu/) — Search, visualize, and compare Copernicus satellite imagery.
- [NASA Worldview](https://worldview.earthdata.nasa.gov/) — Explore global satellite imagery and near-real-time Earth observations.
- [Google Earth Engine Timelapse](https://earthengine.google.com/timelapse/) — Visualize decades of global land-surface change.

### Training data and machine learning

- [Earth Observation Training Data Lab (EOTDL)](https://www.eotdl.com/) — Discover and share Earth observation training datasets and machine-learning models.

## Coordinates, Spatial Indexing & Utilities

### Coordinate systems and transformations

- [Calculation Hub Coordinate Converter](https://calculation-hub.com/geography/coordinate-converter) — Convert between decimal degrees, DMS, and UTM; not a general-purpose CRS transformation engine.
- [EPSG.io — Transform](https://epsg.io/transform#s_srs=4326&t_srs=3857) — Find coordinate reference systems and transform coordinates.
- [ICGC Coordinate Calculator](https://www.icgc.cat/es/Administracion-y-empresa/Herramientas/Cambia-coordenada-formato/Calculadora) — Convert coordinates through the ICGC online calculator.
- [Geo-projections](https://www.geo-projections.com/) — Explore geographic projections.

### Spatial indexes and grids

- [H3 Viewer](https://clupasq.github.io/h3-viewer/) — Inspect H3 hexagonal cells, resolutions, and cell identifiers on an interactive map.
- [H3 Hexagon Mapper](https://ivangfr.github.io/h3-hexagon-mapper/) — Explore and select H3 hexagons on a map.

### Lookup and geometry utilities

- [EPSG.io — Map](https://epsg.io/map#srs=4326&x=0.000000&y=0.000000&z=1&layer=streets) — Find locations on an interactive coordinate reference system map.
- [LatLong](https://www.latlong.net/) — Find latitude and longitude for places.
- [Bounding Box](https://boundingbox.klokantech.com/) — Select geographic bounding boxes on a map.

## Basemaps, Tiles & Map Services

- [OpenFreeMap](https://openfreemap.org/) — Free, open-source OpenStreetMap vector basemaps with a public tile service and no API key.
- [MapTiler Cloud](https://www.maptiler.com/cloud/) — Hosted basemaps, tiles, and map customization services.
- [Protomaps](https://protomaps.com/) — Tools and hosting approaches for serving map tiles from static archives.
- [Mapbox](https://www.mapbox.com/) — Hosted mapping, tiles, and location services for web and mobile applications.

## Geospatial APIs & Location Services

- [Mapbase](https://mapbase.dev/) — Location registry API for coordinates, administrative locations, custom zones, hierarchies, and geometries.
- [Nominatim](https://nominatim.openstreetmap.org/ui/search.html) — Search and reverse-geocode OpenStreetMap locations through a public web interface.
- [openrouteservice](https://openrouteservice.org/) — Routing, isochrone, and geospatial location services with online map tools.

## Related developer-oriented resources

These existing resources are retained for reference but are **libraries or developer tooling rather than standalone browser applications**. New submissions should normally meet the browser-tool or ready-to-use-service criteria in [CONTRIBUTING.md](CONTRIBUTING.md).

- [GeoDesk](https://www.geodesk.com/) — Spatial database engine and query tooling for OpenStreetMap data.
- [GDAL3.js](https://gdal3.js.org/) — JavaScript and WebAssembly integration for running GDAL functionality in browser-based applications.
- [Giro3D](https://giro3d.org/index.html) — Framework for developing 3D geospatial visualizations on the web.

---

## Contributing

Have a useful Web GIS tool, public catalog, or map service to share? Read [CONTRIBUTING.md](CONTRIBUTING.md), check for duplicates, describe the resource's practical value, and disclose any affiliation.

## License

This curated list is shared under the [Creative Commons Attribution 4.0 International License](LICENSE.md). Third-party tools and websites retain their own licenses and terms.
