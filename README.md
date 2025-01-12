# Outlier EDA for Air Quality Analysis

**Overview**
This repository contains an exploratory data analysis (EDA) focused on identifying and analyzing outliers in air quality data. The project specifically investigates pollutants that pose significant health risks, including **SO2, CO, NO2, and PM25,** over the period 2021–2024. Using statistical methods and visualizations, this EDA provides insights into pollutant behavior, their correlation with weather conditions, and temporal trends.

# Steps in the Analysis

**1. Data Import and Initial Inspection:** The dataset is loaded and inspected for structure, completeness, and initial trends.

**2. Descriptive Statistics and Distributions:** Key statistical metrics for each pollutant are calculated. Histograms visualize the distribution of pollutant levels.

**3. Outlier Analysis:** Outliers are detected using the Interquartile Range (IQR) method. **SO2 and CO,** identified as having the largest number of outliers, are further investigated alongside **NO2 and PM25,** which pose health risks. Outliers are analyzed visually using boxplots and grouped by temporal factors **(month, day of the week).**

**4. Correlation with Weather Conditions:** Weather variables (temperature, wind speed, humidity) are analyzed for their relationship with pollutant outliers. Overlapping events between SO2 and CO are identified and investigated.

**5. Temporal Analysis:** Monthly and yearly trends for outliers are explored, highlighting seasonal and activity-driven patterns. Time series visualizations showcase pollutant levels over the period 2021–2024.

**6. Insights and Recommendations:** A summary of key findings, including pollutants with the highest variability and health risks. Actionable recommendations for mitigating peak pollution periods based on temporal and weather patterns.

**Key Findings:**
**1. SO2 and CO** exhibited the highest number of outliers, often peaking during **December and mid-week days.**
**2. NO2 and PM25** showed fewer outliers but remain significant due to their health impacts.
3. Correlation analysis revealed that weather conditions, such as **low wind speeds and high humidity,** could influence pollutant accumulation.
