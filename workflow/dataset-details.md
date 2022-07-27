## Overview ##

This dataset contains SNOTEL station GeoJSON files by state and for the US.
The initial focus is simply to create layer files that can be used in web applications.

Feedback from NRCS staff is that querying the NRCS web services for
SNOTEL time series, and then using the station locations for the layer,
is currently the best way to generate a layer.
Because only the recent 3 years of data is queried for time series,
historical stations may not be included in the layer.

## Downloads ##

The following files can be downloaded or used directly.

| **Layer File** | **Description** |
| -- | -- |
| [`us-snotel-stations.geojson`](us-snotel-stations.geojson) | All SNOTEL stations in the US. |
| [`ak-snotel-stations.geojson`](ak-snotel-stations.geojson) | Alaska SNOTEL stations. |
| [`az-snotel-stations.geojson`](az-snotel-stations.geojson) | Arizona SNOTEL stations. |
| [`ca-snotel-stations.geojson`](ca-snotel-stations.geojson) | California SNOTEL stations. |
| [`co-snotel-stations.geojson`](co-snotel-stations.geojson) | Colorado SNOTEL stations. |
| [`id-snotel-stations.geojson`](id-snotel-stations.geojson) | Idaho SNOTEL stations. |
| [`mt-snotel-stations.geojson`](mt-snotel-stations.geojson) | Montana SNOTEL stations. |
| [`nm-snotel-stations.geojson`](nm-snotel-stations.geojson) | New Mexico SNOTEL stations. |
| [`nv-snotel-stations.geojson`](nv-snotel-stations.geojson) | Nevada SNOTEL stations. |
| [`or-snotel-stations.geojson`](or-snotel-stations.geojson) | Oregon SNOTEL stations. |
| [`ut-snotel-stations.geojson`](ut-snotel-stations.geojson) | Utah SNOTEL stations. |
| [`wa-snotel-stations.geojson`](wa-snotel-stations.geojson) | Washington SNOTEL stations. |
| [`wy-snotel-stations.geojson`](wy-snotel-stations.geojson) | Wyoming SNOTEL stations. |

## Workflow ##

See the [`owf-data-us-snotel`](https://github.com/OpenWaterFoundation/owf-data-us-snotel)
GitHub repository for information.

## Update Frequency and Versions ##

The dataset is updated in early spring to account for stations that have reported in the
previous three years, and when new data or edits are provided.
A single version is published.

## Credits ##

* The Open Water Foundation created and maintains the dataset.

## License ##

[Attribution-ShareAlike 4.0 International](https://creativecommons.org/licenses/by-sa/4.0/)
