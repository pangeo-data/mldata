# Raw datasets

This is a list of raw weather and climate datasets that are commonly used in ML research. The list is in alphabetical order.


### CMIP6
- *Reference*: [Eyring et al. 2016](https://gmd.copernicus.org/articles/9/1937/2016/)
- *Data*: [https://pcmdi.llnl.gov/CMIP6/](https://pcmdi.llnl.gov/CMIP6/)
- *Description*: Huge archive of global climate model simulations following all kinds of different scenarios. 
- *Examples of papers using this dataset*: [Ham et al. 2019](https://www.nature.com/articles/s41586-019-1559-7)

### ERA5
- *Reference*: [Hersbach et al. 2020](https://rmets.onlinelibrary.wiley.com/doi/full/10.1002/qj.3803)
- *Data*: [https://cds.climate.copernicus.eu/](https://cds.climate.copernicus.eu/)
- *Description*: The ultimate reanalysis dataset covering the last 40 years (1950 to 1978 as a preliminary version) at 0.25 degree global resolution. Hourly data available. Pretty much every variable.
- *Notes*: Care is to be taken for a bunch of surface variables, such as precipitation and wind. These often don't match direct observations very closely.
- *Examples of papers using this dataset*: [WeatherBench](https://doi.org/10.1029/2020MS002203)

### TIGGE
- *Reference*: [Bougeault et al. 2010](https://journals.ametsoc.org/view/journals/bams/91/8/2010bams2853_1.xml)
- *Data*: [https://apps.ecmwf.int/datasets/data/tigge/levtype=sfc/type=cf/](https://apps.ecmwf.int/datasets/data/tigge/levtype=sfc/type=cf/)
- *Description*: 15 year archive of operational global ensemble forecasts from different centers (not live).
- *Examples of papers using this dataset*: [WeatherBench](https://doi.org/10.1029/2020MS002203)

