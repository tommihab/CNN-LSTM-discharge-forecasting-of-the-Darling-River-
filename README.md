# CNN-LSTM-discharge-forecasting-of-the-Darling-River-
This repository contains the supplementary material of the study "Dual-Input CNN-LSTM for river discharge forecasting of the Darling River, Australia, using gridded Hydro-Meteorological data"

## Contents

- `Google Colab Jupyter Notebooks/`: Google Colab notebooks used for data preprocessing, model     training, and evaluation.
- `processed_input_data`:
      discharge_aligned.csv: Darling River maximum daily discharge at the Bourke gauging station
      precip_aligned.nc: Precipitation as gridded data (.nc file), daily from 1972-2025
      et_aligned: Evapotranspiration as gridded data (.nc file), daily from 1972-2025
      sm_aligned.nc: Soil moisture as gridded data (.nc file), daily from 1972-2025
      

## Study overview

The repository contains the implementation of a CNN-LSTM for daily discharge forecasting at Bourke gauging station of the Darlin River, New South Wales, Australia at forecast lead times of 3, 5, 10 and 15 days.

## Data availability

Discharge data used in this study was obtained from the Bureau of Meteorology’s Water Data Online platform (https://www.bom.gov.au/waterdata/), while the gridded precipitation, evapotranspiration and soil moisture datasets were retrieved from the Australian Water Outlook (https://awo.bom.gov.au/products/historical/precipitation/4.5,-29.826,142.952/nat,-29.062,143.631/r/d/2026-02-28).

## License

See LICENSE file
