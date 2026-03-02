# Heatwave and precipitation risk assessment for infrastructure (airports)

Short description.

Objectives.

Climate impacts covered: extreme temperatures and precipitation.


## Strengths and weaknesses

TODO: Comparative added value to other similar tools.


## Hazard assessment

### Part 1: data retrieval and preparation

UERRA reanalyis and EURO-CORDEX climate projections.

- [Prepare climate datasets (UERRA)](./Hazard_prepare_climate_data_UERRA.ipynb)
- [Prepare climate datasets (EURO-CORDEX)](./Hazard_prepare_climate_data_CORDEX.ipynb)

Other datasets that cover variables total precipitation/precipitation flux and maximum temperature can be used.

:::{tip}
EURO-CORDEX variables required to run the workflow as the same as used by the heatwave (xclim) and extreme precipitation workflows. If you have run these workflows already, it is likely that data already downloaded can be reused here.
:::

### Part 2: computation of hazard

Heatwave indicators from xclim, percentiles and return periods of extreme events.

- [Compute climate indicators](./Hazard_indicators_compute.ipynb)

Outputs: TODO


### Part 3: visualisation of hazard

- [Visualise climate indicators](./Hazard_plot.ipynb)
- [Visualise climate indicators (change in projection)](./Hazard_plot_change.ipynb)

Outputs: TODO


## Risk assessment

Extract hazard data for airport locations, define exposure and vulnerability indicators for the infrastructure, and determine risk after normalisation of each contributing factor.

- [Risk assessment for airport infrastructure](./Risk_assessment_airports.ipynb)

Outputs: TODO


## Contributors

- Giuseppe Giugliano (giuseppe.giugliano@cmcc.it)
- Carmela de Vivo (carmela.devivo@cmcc.it)
- Daniela Quintero (daniela.quintero@cmcc.it)
