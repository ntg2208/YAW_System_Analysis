# Wind Turbine YAW System Analysis

## Project Overview

This project focuses on analyzing the performance of the YAW system in wind turbines using data from the Kelmarsh wind farm, specifically Turbine 2 for the year 2022. The YAW system is crucial for aligning the turbine's rotor with the wind direction to maximize energy production and reduce structural stress.

## Data Source

The data used in this analysis is from the Kelmarsh wind farm, Turbine 2, for the year 2022. It was released by Cubico Sustainable Investments Ltd under a CC-BY-4.0 open data license.

## Key Findings

1. **Overall YAW System Performance:** The system generally performs well, with a high correlation (0.8696) between wind direction and nacelle position.

2. **Yaw Error Analysis:**
   - Average yaw error is lowest (4.00°) in the 10-15 m/s wind speed range.
   - Highest average yaw error (15.46°) occurs at low wind speeds (0-5 m/s).

3. **Wind Vane Issues:** The analysis revealed potential problems with the wind vane system, showing weak correlation (0.0445) between wind direction and vane position.

4. **Yaw Rate vs Wind Speed:** A weak negative correlation (-0.0659) was found between wind speed and yaw rate, with more active yawing at lower wind speeds.

## Recommendations

1. Investigate and potentially recalibrate the wind vane system to improve accuracy.
2. Optimize yaw control strategies for low wind speed conditions to reduce yaw error.
3. Consider implementing more aggressive yaw control for wind speeds above 9 m/s to maintain yaw errors below 5°.

## Future Work

1. **Machine Learning for Anomaly Detection:**
   - Develop ML models to detect anomalies in YAW system behavior, potentially identifying failures before they occur.
   - Use techniques such as autoencoders or isolation forests to identify unusual patterns in yaw error, yaw rate, or wind vane data.

2. **Predictive Maintenance:**
   - Create predictive models to forecast when YAW system components may require maintenance.
   - Incorporate additional data such as component age, maintenance history, and environmental factors to improve prediction accuracy.

3. **Advanced Data Analysis:**
   - Perform time series analysis to identify seasonal or temporal patterns in YAW system performance.
   - Use clustering algorithms to identify different operational modes or conditions that affect YAW system behavior.