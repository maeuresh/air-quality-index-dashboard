# Air Quality Index Dashboard
### Dashboard Link: https://app.powerbi.com/view?r=eyJrIjoiMzVjM2M3ZTMtNmRlZi00YjlkLWE4YTEtZmYzMmFiM2UwYmE0IiwidCI6ImY1YTFjNzJkLTEyZmUtNDIyZS04ODZmLTcxNmM5ZDBjZGE4NSJ9

## Problem Statement
This dashboard provides a comprehensive overview of air quality across various cities in India. It enables government agencies, environmentalists, and the public to track and analyze the air quality in real-time. The dashboard highlights the most and least polluted cities, and provides trends over time to understand how air quality is evolving. By visualizing this data, it becomes easier to identify areas with critical pollution levels and to focus efforts on reducing harmful pollutants.

Key metrics such as the average levels of CO, NO, SO2, and PM2.5 are displayed prominently, allowing for quick assessment of the air quality in different regions. The data helps in understanding the spatial distribution of pollution and can aid in the formulation of policies to combat air pollution.

### Steps Followed
- Step 1: Load data into Power BI Desktop, the dataset is a CSV file containing AQI data for various cities across India.
- Step 2: In Power Query Editor, enable "Column Distribution," "Column Quality," and "Column Profile" under the Data Preview section.
- Step 3: Ensure column profiling is based on the entire dataset by selecting "Column profiling based on the entire dataset."
- Step 4: Analyze the dataset for any errors or empty values, particularly focusing on pollutants like CO, NO, SO2, and PM2.5.
- Step 5: Handle missing data where necessary. For example, null values were omitted when calculating average AQI values for specific cities.
- Step 6: Apply a theme to the report under the View tab to maintain a consistent and visually appealing design.
- Step 7: Add visual filters (slicers) for city selection, allowing users to view data for specific locations or compare different cities.
- Step 8: Add card visuals to display key metrics such as the average levels of CO, NO, SO2, and PM2.5 across the selected cities.
- Step 9: Create bar charts to highlight the top 3 most polluted and least polluted cities, allowing for easy comparison.
- Step 10: Plot the AQI trend over time using a line chart to show how air quality has changed from 2015 to 2020.
- Step 11: Use a map visual to provide a geographical overview of AQI across different cities, making it easier to identify pollution hotspots.
- Step 12: Add text boxes and shapes to enhance the visual design and provide context where necessary.
- Step 13: Publish the report to Power BI Service for easy access and sharing with stakeholders.

# Insights
The dashboard provides the following key insights:

### [1] Top 3 Most Polluted Cities
- Ahmedabad: 452.12 AQI
- Delhi: 259.49 AQI
- Patna: 240.78 AQI
- These cities have critically high pollution levels and require immediate attention.

### [2] Top 3 Least Polluted Cities
- Coimbatore: 73.02 AQI
- Shillong: 53.80 AQI
- Aizawl: 34.77 AQI
These cities have relatively low pollution levels, making them safer in terms of air quality.

### [3] Average Pollutant Levels
- CO: 2.25
- NO: 17.57
- SO2: 14.53
- PM 2.5: 67.45
These averages provide a snapshot of the general air quality across the monitored cities.

### [4] AQI Trend Overview (2015-2020)
- There is a visible decline in AQI levels over the years, indicating a decrease of air quality over the years.

### [5] Area-wise AQI Overview
- The geographical map provides an easy way to identify which regions of India are most affected by poor air quality.

# Snapshot of Dashboard
![dashboard](https://github.com/user-attachments/assets/a41453da-5021-47e3-a4b2-d34cabf33405)
