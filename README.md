# blackbalsam-covid-19-data

This repository defined the COVID-19 data set for the [Blackbalsam](https://github.com/stevencox/blackbalsam/edit/master/README.md) COVID-19 research platform.

More data sets will be added soon. The ones below exist in the `/home/shared` directory mounted to each Jupyter notebook.

### CORD-19 Dataset
The [CORD-19 Open Research Data Set](https://www.semanticscholar.org/cord19/download)

### New York Times
The [New York Times COVID-19](https://github.com/nytimes/covid-19-data) GitHub data set 

### PM_COVID
The [COVID-19 and Particulate Matter link](https://projects.iq.harvard.edu/covid-pm/home) and related [analytics](https://github.com/wxwx1993/PM_COVID)

### GeoJSON
Choropleth boundaries at the state and county level at multiple resolutions.

See the `update` script for details of current data sets. Submit a pull request to add a data set.

```
data/
|-- PM_COVID
|   |-- Analyses.R
|   |-- Data
|   |-- Figure.R
|   |-- LICENSE
|   |-- Manuscript
|   |-- Preprocessing.R
|   |-- README.md
|   `-- additional_preprocessing_code
|-- cord-19
|   |-- 2020-04-17-CORD-19-MappedTo-2020-04-10-MAG-Backfill.csv
|   |-- all_sources_metadata_2020-03-13.readme
|   |-- antiviral_with_properties.sdf.gz
|   |-- biorxiv_medrxiv.tar.gz
|   |-- candidate_compounts.readme
|   |-- comm_use_subset.tar.gz
|   |-- cord_19_embeddings_4_24.tar.gz
|   |-- custom_license.tar.gz
|   |-- metadata.csv
|   `-- noncomm_use_subset.tar.gz
|-- cord19
|   |-- all_sources_metadata_2020-03-13.readme
|   |-- antiviral_with_properties.sdf.gz
|   |-- biorxiv_medrxiv.tar.gz
|   |-- candidate_compounts.readme
|   |-- comm_use_subset.tar.gz
|   |-- cord_19_embeddings_4_24.tar.gz
|   |-- custom_license.tar.gz
|   |-- metadata.csv
|   `-- noncomm_use_subset.tar.gz
|-- covid-tracking
|   |-- counties.csv
|   |-- counties.json
|   |-- current.csv
|   |-- current.json
|   |-- daily.csv
|   |-- daily.json
|   |-- info.csv
|   |-- info.json
|   |-- press.csv
|   |-- press.json
|   |-- screenshots.csv
|   |-- screenshots.json
|   |-- urls.csv
|   `-- urls.json
|-- geojson
|   |-- gz_2010_us_040_00_20m.json
|   |-- gz_2010_us_040_00_500k.json
|   |-- gz_2010_us_040_00_5m.json
|   |-- gz_2010_us_050_00_20m.json
|   |-- gz_2010_us_050_00_500k.json
|   `-- gz_2010_us_050_00_5m.json
|-- litcovid
|   |-- litcovid2BioCJSON.gz
|   `-- litcovid2pubtator.gz
`-- nytimes
    `-- covid-19-data
```
