# Analyzing-ISRO-Sea-Surface-Dataset

This project explores Sea Level Rise trends in the North Pacific Oceanic Region using a **satellite-based dataset** provided by **ISRO (Indian Space Research Organisation)**, thanks to Dr. Neeraj Agarwal to give us this opportunity. The dataset spans 30 years (1993–2022) and was provided in NetCDF (.nc) format under the name ALL_MONTHLY_SLA_1993-2022.nc. (Since the dataset is huge, I couldn't attach it here)

The project's goal was to contribute to ISRO's research in analysing and visualizing trends on how sea levels have changed over time in the region, and identify key environmental parameters influencing this trend, such as Sea Surface Temperature (SST), Salinity, and Ice Melt Indicator.

## What We Did
1. <ins>Data Extraction & Preprocessing</ins>

Used latitude and longitude slicing to isolate the North Pacific subregion.
Extracted variables such as:

-> Sea Level Anomaly (SLA)

-> Sea Surface Temperature (SST)

-> Salinity

  This preprocessing allowed for clean, consistent, and reproducible analysis.

2. <ins>Visualization of Spatio-Temporal Trends</ins>
   
  Created temporal line plots to track sea level and temperature trends over time (1993–2022), for the North Pacific, as well as Global trends.

3. <ins>Interpretation & Environmental Inference</ins>
   
Interpreted visual data to identify:

-> Gradual rise in sea levels over time.

-> Strong links between rising SST and corresponding SLA increases.

-> Periodic variations linked to monsoons and ENSO (El Niño–Southern Oscillation) effects.

These observations were supported by climate science literature and real-world ocean behaviour, validating the analysis.

Please refer to the Jupyter Notebook and Results section to know more!

