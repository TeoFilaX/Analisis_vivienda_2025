# Housing Price Index Analysis (INE Table 50902)

## Conclusions

The analysis of Spain’s housing price index (\u00cdndice de Precios de Vivienda) using data from the Instituto Nacional de Estadística shows a sustained upward trend over the last two decades. When the series is normalised relative to the maximum index value (118.485), the average index for 2002 corresponds to roughly 59.4%, while 2025 reaches 100%. This indicates an approximate **40% increase** in the index between 2002 and 2025.

Below is a table summarising the annual average index values and their normalised percentages for 2002 and 2025:

| Year | Average Index Value | Normalised Percentage* |
| --- | --- | --- |
| 2002 | 70.36 | 59.4% |
| 2025 | 118.61 | 100.0% |

\*Percentage relative to the maximum value (118.485).

### Visualising the Increase

The chart below depicts the normalised index over time. Starting at ~59% in 2002, the index climbs steadily to 100% by 2025, highlighting the cumulative 40% rise.

![Normalised Housing Price Index](./housing_increase_new

## Project Overview

This repository contains the notebook `consulta_economica_vivienda.ipynb`, which retrieves housing price index data from INE’s API, processes it into a usable format, computes annual averages, normalises the series relative to the maximum value, and visualises the long‑term trend. The notebook also highlights the 40% increase from 2002 to 2025.

## How to Run

1. Clone the repository:

       git clone https://github.com/TeoFilaX/Analisis_vivienda_2025.git
       cd Analisis_vivienda_2025

2. Install the required dependencies:

       pip install pandas matplotlib requests beautifulsoup4

3. Open the notebook and run all cells:

       jupyter notebook consulta_economica_vivienda.ipynb


The notebook will download the data (if available), compute the annual averages, normalise the values, and generate the chart shown above.

## Author

**Christian Monzón**

## Future Work

- Incorporate more granular regional data for deeper analysis.
- Explore forecasting models (e.g., ARIMA, regression) to predict future housing price trends.
- Build an interactive dashboard for visualising the index data.

## License

This project is open‑source and available under the MIT License.


