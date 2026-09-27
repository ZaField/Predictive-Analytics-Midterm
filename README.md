# Midterm Predictive Analytics (Pred2)

## Zaky Hafiedz - 24130500006

**time-series forecasting** pipeline to predict Benzene (C6H6) concentration using the UCI Air Quality dataset (hourly sensor readings from an Italian city, March 2004 - April 2005).

## Dataset

**Dataset Name:** Air Quality Dataset

**Owner/Donor:** Saverio Vito

**Source:** UCI Machine Learning Repository, Dataset ID 360
https://archive.ics.uci.edu/dataset/360/air+quality

**License:** Creative Commons Attribution 4.0 International (CC BY 4.0)

**Dataset Characteristics:**
- **Rows:** 9,358 hourly observations
- **Columns:** 15 features (date, time, 5 metal-oxide sensor readings, and reference gas concentrations from certified analyzer)
- **Time Span:** March 2004 – February 2005 (one full year)
- **Frequency:** Hourly
- **Unit of Analysis:** One hourly-averaged sensor reading from an Air Quality Chemical Multisensor Device
- **Device Location:** Field deployment at road level in a significantly polluted area of an Italian city

**Loading the Dataset:**
We will use the `ucimlrepo` package to fetch the dataset directly from the UCI Machine Learning Repository, ensuring reproducibility without requiring local file uploads.