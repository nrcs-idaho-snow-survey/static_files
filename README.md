# Static Files
Static files that we use for metadata.

## Data Sources

### reservoir_associations.json
The `adequate irrigation supply` and `1991-2020 spring to summer streamflow` fields were taken from an Excel file created in Nov, 2021 for a presentation by Erin Whorton. **Further documentation is needed for how these numbers were generated!**

### data/reservoir/
These data were pulled from NRCS ReportGenerator in Nov, 2021, using https://github.com/nrcs-idaho-snow-survey/water_supply, and subsequently collected with https://github.com/nrcs-idaho-snow-survey/scripts/blob/main/collect_reservoir_data.py.

### data/snowpack/idaho_snotel_median_swe_1991-2020.csv
These data were pulled from the csv versions of https://www.nrcs.usda.gov/Internet/WCIS/AWS_PLOTS/siteCharts/POR/WTEQ/ID/.

## Notes
- Feel free to add any desired basin associations, they just need to be comma separated. Note that all current software searches for exact, case sensitive matches.
- Basin definitions should match across files, i.e. it should be 'West Central' in both `iddco_sites_metadata.csv` and `id_reservoirs_metadata.csv`.
