# Analyzing Tropospheric Formaldehyde (HCHO) Gas in Sri Lanka

## Introduction
This repository contains a project focused on analyzing tropospheric formaldehyde (HCHO) levels in seven cities in Sri Lanka using data from the Sentinel-5P satellite. The project aims to uncover trends in air quality, pinpoint possible pollution sources, and create predictive models to project future HCHO levels.

## Dataset
The dataset includes daily measurements of tropospheric formaldehyde (HCHO) column number density from January 1, 2019, to December 31, 2023, sourced from the Sentinel-5P satellite. It covers seven cities in Sri Lanka:
- Colombo Proper
- Deniyaya (Matara)
- Nuwara Eliya Proper
- Bibile (Monaragala)
- Kurunegala Proper
- Jaffna Proper
- Kandy Proper

The dataset underwent preprocessing to handle missing values, outliers, and format inconsistencies.

## File Structure
- **Weather_Preprocessing.ipynb**: Jupyter Notebook containing data preprocessing steps.
- **Sri Lanka Weather Dataset.ipynb**: Jupyter Notebook containing data preprocessing steps for partial dataset.
- **HCHO-Analysis-in-Sri-Lanka.ipynb**: Jupyter Notebook containing machine learning model development and spatio-temporal analysis.
- **weather_new.csv**: Preprocessed weather data.
- **SriLanka_Weather_new.csv**: Preprocessed partial weather data.
- **col_mat_nuw_output.csv**, **mon_kur_jaf_output.csv**, **kan_output.csv**: Raw data files.
- **HCHO Monitoring Dashboard.pbix**: Power BI for interactive visualization dashboard.

## Results and Insights
- Descriptive statistics and visualizations provide insights into HCHO levels across different cities.
- Correlation analysis with external factors suggests relationships between HCHO levels and weather variables.
- COVID-19 lockdown impact analysis shows decreased HCHO levels in certain cities during the lockdown period.
- ARIMA model predicts future HCHO levels with evaluation metrics.

## Power BI Visualization
Preprocessed data was exported to Power BI for interactive visualization. The Power BI dashboard allows for dynamic exploration of HCHO trends, correlation analysis, and geographical mapping of data.

## Limitations
- Data sources may have measurement errors or missing data.
- Assumptions made in the analysis may not always hold true in real-world scenarios.

## Impact of Findings
- Predicting HCHO levels allows for issuing targeted health alerts and implementing pollution control measures.
- Research findings contribute to advancing environmental science and promoting healthier cities.

## Further Research
- Incorporating additional external factors into the ARIMA model for improved predictions.
- Comparing ARIMA with advanced machine learning models for HCHO prediction.

## References
- NOAA Climate Data Online: [Link](https://www.ncdc.noaa.gov/cdo-web/search?datasetid=GHCND)
- Sri Lanka Weather Dataset on Kaggle: [Link](https://www.kaggle.com/datasets/rasulmah/sri-lanka-weather-dataset)

## Acknowledgments
I would like to express my gratitude to Mr. Mohamed Ayoob and Mr. Nipuna Senanayake for their guidance and support throughout this project.
