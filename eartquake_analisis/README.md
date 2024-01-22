## Earthquakes Analysis with Python
### Overview
This Python script analyzes earthquake data using various data processing and visualization libraries. The dataset used is sourced from 'earthquakes_2023_global.csv'. The script covers data cleaning, feature engineering, and visualization to gain insights into earthquake patterns.

### Libraries Used
- **pandas**: Data manipulation and analysis
- **numpy**: Mathematical functions
- **matplotlib** and seaborn: Data visualization
- **geopy**, **folium**, **geopandas**: Geospatial data manipulation and visualization
### Data Cleaning and Feature Engineering
- **Date-Time Conversion**: Convert 'time' and 'updated' columns to datetime format.
- **Duplicate Removal**: Remove duplicate entries from the dataset.
-** Data Type Optimization**: Optimize data types to reduce memory usage.
- **Fill Missing Values**: Fill missing values in 'nst' column with 0.
- **Place Parsing**: Parse 'place' column to extract region, distance to earthquake, and country.
### Data Visualizations
1. Monthly Earthquake Frequency:

   - Histogram displaying earthquake frequency by month.
   - Log scale used for better visibility.
2. Magnitude Distribution:

    - Histogram and kernel density plot illustrating the distribution of earthquake magnitudes.
    - Line plot depicting how magnitude varies across different months.
3. Magnitude Distribution with 0 Stations Reported:

    - Histogram showcasing the distribution of earthquake magnitudes when 0 stations reported.
4. Station Coverage vs. Minimum Distance to Event:

    - Scatter plot demonstrating the exponential distribution of station coverage based on the minimum distance to the earthquake event.
### Insights
 - Earthquake frequency tends to increase during certain months.
- Magnitude distribution follows a normal distribution, with a higher frequency of weak earthquakes.
- The script provides insights into earthquake magnitudes when no stations reported.
- Station coverage is demonstrated through a scatter plot against the minimum distance to the event.
### Instructions
- Ensure the required libraries are installed (pip install pandas numpy matplotlib seaborn geopy folium geopandas).
- Download the earthquake dataset ('earthquakes_2023_global.csv') and update the file path accordingly.
- Run the script to generate visualizations and gain insights into earthquake patterns.
- Feel free to explore and customize the script based on your specific requirements and dataset characteristics.