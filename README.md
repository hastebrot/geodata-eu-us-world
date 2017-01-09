geodata-eu-us-world
===================

A small collection of EU, US, and world shapefiles.

<!-- TOC depthFrom:1 orderedList:false -->

- [Sources](#sources)
- [Contents](#contents)
- [Coordinate Systems](#coordinate-systems)
- [References](#references)
- [Copyright](#copyright)

<!-- /TOC -->

## Sources

- GISCO 2013 &mdash; Geographic Information System of the COmmission
- TIGER 2013 &mdash; Topologically Integrated Geographic Encoding and Referencing

## Contents

- `gisco-2013-cntr-at` (876 kB) &mdash; World (countries), attribute table
- `gisco-2013-cntr-rg-10m` (3.8 MB) &mdash; World (countries), regions at 1:10,000,000
- `gisco-2013-nuts-at` (2.9 MB) &mdash; European Union (statistical units), attribute table
- `gisco-2013-nuts-rg-10m` (4.8 MB) &mdash; European Union (statistical units), regions at 1:10,000,000
- `tiger-2013-us_state` (13.7 MB) &mdash; United States (states)

## Coordinate Systems

- GISCO (NUTS)
  - Geodetic: ETRS89 ([EPSG:4258](https://epsg.io/4258))
  - Projected (suggestion): ETRS Lambert Azimuthal Equal Area ([EPSG:3035](https://epsg.io/3035))
- TIGER (States)
  - Geodetic: NAD83 ([EPSG:4269](https://epsg.io/4269))
  - Projected (suggestion): US National Atlas Equal Area ([EPSG:2163](https://epsg.io/2163))

## References

- Official Eurostat GISCO Shapefiles, http://ec.europa.eu/eurostat/web/gisco/geodata/reference-data
- Selected U.S. Census TIGER Shapefiles, http://forever.codeforamerica.org/Census-API/shutdown-2013.html

## Copyright

GISCO:

>The Commission agrees to grant the non-exclusive and not transferable right to use and process the Eurostat/GISCO geographical data downloaded from this page (the "data").
>
>The permission to use the data is granted on condition that: the data will not be used for commercial purposes; the source will be acknowledged. A copyright notice, as specified below, will have to be visible on any printed or electronic publication using the data downloaded from this page.

&mdash; http://ec.europa.eu/eurostat/web/gisco/geodata/reference-data/administrative-units-statistical-units

TIGER:

> Copyright protection is not available for any work of the United States Government (Title 17 U.S.C., Section 105). Thus, you are free to reproduce census materials as you see fit. We would ask, however, that you cite the Census Bureau as the source.

&mdash; https://www2.census.gov/geo/pdfs/maps-data/data/tiger/tgrshp2014/TGRSHP2014_TechDoc_Ch1.pdf
