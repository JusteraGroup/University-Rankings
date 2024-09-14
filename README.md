# University Ranking Data Analytics Dashboard

## Overview

This Power BI project provides a detailed analysis of university rankings, with the goal of visualizing and interpreting ranking data to offer insights into university performance. The dashboard is designed to identify trends and assist stakeholders in making informed decisions.

## Tools Used

- **Excel**
- **Power BI**
- **Power Query**
- **DAX Query**
- **API**
- **Python Script**

## Cleaning and Analyzing the Data

1. **Data Import**: Imported university ranking data from various sources.
2. **Data Automation**: Utilized Python scripts to automate the data extraction and preprocessing tasks via APIs.
   - Times Higher Education API call link: [THE API](https://www.timeshighereducation.com/sites/default/files/the_data_rankings/world_university_rankings_2024_0__91239a4509dc50911f1949984e3fb8c5.json)
   - QS Rankings API call links:
     - [QS API 1](https://www.topuniversities.com/rankings/endpoint?nid=3897789&page=0&items_per_page=1500)
     - [QS API 2](https://topuniversities.com/rankings/endpoint?nid=3897789&page=0&items_per_page=1500&tab=indicators&region=&countries=&cities=&search=f&star=&sort_by=rank&order_by=asc&program_type=)
   - CWUR: [World University Rankings 2023 | Global 2000 List](https://cwur.org/2023)
   - Shanghai Ranking Consultancy: [ARWU Rankings](https://www.shanghairanking.com/rankings/arwu/2023)
   - QS Subject API: [QS Subject API](https://topuniversities.com/rankings/endpoint?nid=3948167&page=&items_per_page=2000&tab=indicators&region=&countries=&cities=&star=&sort_by=rank&order_by=asc&program_type=&loggedincache=5923738-1716979978425)
3. **Data Merging**: Consolidated datasets to combine rankings, criteria scores, and other relevant information.
4. **Data Cleaning**:
   - Removed duplicates
   - Renamed columns for clarity
   - Adjusted data types to ensure consistency
5. **Parameter Creation**: Created parameters to filter data based on specific conditions such as year, region, and ranking category.
6. **Data Loading**: Loaded and applied the cleaned data into Power BI.

## Exploring and Manipulating Data

Utilized DAX queries to manipulate and analyze data, providing insights for visualization and identifying key areas for improvement. Created measures and columns using DAX functions like `COUNT`, `SUM`, `CALCULATE`, `IF`, `SWITCH`, `DIVIDE`, and date-time functions to enhance dashboard KPIs.

## About The Dashboard

The dashboard offers comprehensive insights into university rankings, showcasing overall performance, regional trends, and analysis across various criteria.

1. **Developed Dashboard**: Presents overall rankings, regional performance, and trend analysis.
2. **Analysis Parameters**: Includes academic reputation, employer reputation, faculty/student ratio, and more.
3. **KPIs Created Using DAX**:
   - Top Universities: Lists universities consistently ranking in the top 10.
   - Regional Analysis: Highlights the number of top-ranked universities by region.
   - Trend Analysis: Shows changes in university rankings over multiple years.
   - Criteria Breakdown: Evaluates performance across different ranking criteria.
4. **Visualization Charts**:
   - **Bar Charts**: Displaying top universities and their rankings.
   - **Maps**: Showing the geographical distribution of universities.
   - **Line Charts**: Illustrating trends over time.
   - **Tables**: Providing detailed rankings with various criteria.

## Usage

To explore the University Ranking Dashboard, follow these steps:

1. Download the `University_Ranking_May_2024.pbix` file.
2. Open the file using Power BI Desktop.
3. Connect the file to your data source or use the provided sample dataset.
4. Interact with various visuals and filters to explore different aspects of the university ranking data.

## Feature Improvements

1. **Interactive Filters**: Add more interactive filters for users to customize views based on criteria like region, university type, etc.
2. **Advanced Analytics**: Incorporate predictive analytics to forecast future rankings based on current data trends.
3. **Enhanced Visuals**: Use advanced Power BI visualizations for more intuitive data presentation.
4. **Data Sources Integration**: Integrate additional data sources such as student reviews or employment outcomes.
5. **Performance Optimization**: Improve the performance of the dashboard by optimizing data models and reducing load times.
6. **Mobile Optimization**: Ensure the dashboard is fully functional and user-friendly on mobile devices.
7. **User Annotations**: Allow users to add notes or annotations to specific data points for better context sharing.

