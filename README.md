# Weather Analysis Repository

## Overview
This repository contains an analysis of weather trends, seasonal variations, and correlations between various weather attributes using Excel and SQL. Additionally, a Power BI dashboard is developed to facilitate historical weather monitoring and real-time insights.

## Dataset Description
The dataset includes multiple files covering different weather attributes for various cities. Each file contains time-series data on key meteorological factors, enabling in-depth analysis of weather patterns and their impact.

### Table Descriptions
1. **City_attributes.csv**
   - **Purpose:** Provides metadata for each city in the dataset.
   - **Columns:** City, Country, Latitude, Longitude
   - **Usage:** Helps in mapping cities geographically and performing location-based analyses.

2. **Humidity.csv**
   - **Purpose:** Contains hourly humidity levels for each city.
   - **Columns:** Datetime, City-wise humidity values
   - **Usage:** Analyze humidity trends, seasonal variations, and correlations with other factors.

3. **Pressure.csv**
   - **Purpose:** Provides hourly air pressure data per city.
   - **Columns:** Datetime, City-wise air pressure values
   - **Usage:** Study pressure patterns, predict weather changes, and analyze relationships with other attributes.

4. **Temperature.csv**
   - **Purpose:** Contains hourly temperature data for each city.
   - **Columns:** Datetime, City-wise temperature values
   - **Usage:** Examine temperature trends, heatwaves, cold spells, and their effects.

5. **Weather_description.csv**
   - **Purpose:** Provides textual weather descriptions per city on an hourly basis.
   - **Columns:** Datetime, City-wise weather descriptions (e.g., "clear sky," "rainy," etc.)
   - **Usage:** Understand qualitative weather aspects and analyze frequency of specific weather conditions.

6. **Wind_direction.csv**
   - **Purpose:** Contains hourly wind direction data for each city.
   - **Columns:** Datetime, City-wise wind direction values (in degrees)
   - **Usage:** Study wind patterns and their relationship with weather changes and environmental factors.

7. **Wind_speed.csv**
   - **Purpose:** Provides hourly wind speed data per city.
   - **Columns:** Datetime, City-wise wind speed values (in km/h or m/s)
   - **Usage:** Analyze wind patterns, predict hazards, and study its impact on daily life.

## MECE Breakdown
### **Mutually Exclusive Categories**
- **Geographical Analysis:** Latitude, Longitude, and clustering of cities
- **Weather Attributes:** Temperature, Humidity, Pressure, Wind Speed, Wind Direction
- **Time-based Patterns:** Seasonal trends, extreme weather events, and daily variations
- **Impact Analysis:** Effects on energy consumption, pollution dispersion, and human adaptation

### **Collectively Exhaustive Analysis**
- **City-level analysis:** Each city’s climate characteristics
- **Inter-attribute correlations:** Relationship between humidity and pressure, wind patterns, and weather impact
- **Seasonal and time-series analysis:** Identifying long-term patterns and anomalies
- **Predictive insights:** Recognizing extreme weather conditions and their consequences

## Exploratory Data Analysis (EDA) Questions
The following EDA questions will be addressed through SQL queries, Excel analytics, and Power BI visualizations:
1. Identifying cities at extreme latitudes and their climate impact.
2. Clustering cities with similar latitudes and longitudes and analyzing common factors.
3. Correlations between geographical location and weather attributes.
4. Identifying cities with the most frequent rainy weather and their seasonal patterns.
5. Relationship between humidity and air pressure and its impact on weather conditions.
6. Impact of wind direction on coastal cities' temperatures.
7. Identifying months with significant temperature fluctuations and their causes.
8. Detecting extreme weather events (storms, heatwaves) from time-series data.
9. Temperature trends in northern vs. southern hemisphere cities.
10. Effects of extreme cold and heat on cities and adaptation measures.
11. Investigating temperature anomalies and their correlations with external factors.
12. Impact of temperature on energy consumption patterns.
13. Wind direction’s influence on air quality and pollution dispersion.
14. Identifying cities prone to strong winds and their potential consequences.
15. Relationship between wind speed, direction, and weather-related events.

## Power BI Dashboard Insights
The Power BI dashboard will provide the following visual insights:
1. **Geographical Map:** Distribution of cities based on latitude and longitude.
2. **Bar Chart:** Top 10 countries with the highest number of cities in the dataset.
3. **Scatter Plot:** Latitude distribution across continents.
4. **Line Chart:** Temperature trends over time for selected cities.
5. **Heatmap:** Humidity variations across cities.
6. **Time-series Chart:** Wind speed vs. air pressure for a selected city.
7. **Overall Temperature Trends:** A dataset-wide temperature time-series visualization.
8. **Weather Condition Heatmap:** Busiest hours for different weather conditions.
9. **Radial Chart:** Wind speed variations over a 24-hour cycle.
10. **Comparison Chart:** Temperature variations between two selected cities.
11. **Country-wise Temperature Heatmap:** Temperature ranges across different countries.
12. **Bar Chart:** Cities with the highest and lowest average temperatures.
13. **Wind Rose Chart:** Prevailing wind directions for a selected city.
14. **Wind Speed Heatmap:** Average wind speeds across cities for different months.
15. **Scatter Plot:** Wind speed vs. air pressure for a selected city.

## How to Use This Repository
1. **Data Processing:** Use SQL and Excel for data cleaning, transformation, and exploratory analysis.
2. **Data Visualization:** Build dashboards using Power BI for insights.
3. **Analysis Interpretation:** Answer EDA and Power BI questions using derived insights.
4. **Reporting:** Summarize key findings and patterns in a structured format.

## Tools Used
- **SQL:** Data extraction, transformation, and correlation analysis.
- **Excel:** Initial EDA, data aggregation, and statistical analysis.
- **Power BI:** Advanced visualizations and interactive dashboards.

## Conclusion
This project aims to provide valuable insights into weather patterns, geographical correlations, and extreme weather events using SQL, Excel, and Power BI. The findings will help understand climate impacts, energy consumption patterns, and predictive weather trends.

---


