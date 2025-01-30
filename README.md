# AtliQ Hotels Exploratory Data Analysis

## Project Overview
The AtliQ Hotels Exploratory Data Analysis (EDA) project focuses on analyzing hotel booking data to derive actionable insights for business decision-making. The project leverages multiple datasets containing details about dates, hotels, rooms, and bookings to explore patterns, trends, and relationships within the data. By conducting EDA, the project aims to uncover key factors affecting hotel bookings, revenue generation, and customer satisfaction.

## Objective
The main objectives of this project are:
- Perform comprehensive exploratory data analysis (EDA) on the hotel booking data.
- Identify trends and patterns in booking success, room occupancy, revenue generation, and customer ratings.
- Explore the relationships between different variables such as booking date, room categories, hotel properties, and booking platforms.
- Derive insights that can help in improving operational strategies for the AtliQ Hotels brand.

## Data Used
The following datasets are used for this analysis:
- **dim_date.csv**: Contains date-related information, including the date, month-year, week number, and day type.
- **dim_hotels.csv**: Contains hotel property details such as property ID, name, category, and city.
- **dim_rooms.csv**: Provides details about room occupancy percentage, room ID, and room class.
- **fact_aggregated_bookings.csv**: Includes aggregated booking data, with details on check-in dates, room categories, successful bookings, and capacity.
- **fact_bookings.csv**: Contains booking-specific data, including booking dates, check-in and checkout dates, number of guests, room categories, booking platform, ratings given, booking status, and revenue.

## Methodology
The methodology used in this project involves:
1. **Data Preprocessing**: Cleaning and transforming the raw data to handle missing values, incorrect entries, and data type conversions.
2. **Data Exploration**: Visualizing key relationships in the data using Python libraries such as Matplotlib and Seaborn. The focus is on visualizations like histograms, bar charts, and scatter plots.
3. **Correlation Analysis**: Identifying correlations between key variables such as revenue, booking status, room occupancy, and customer ratings.
4. **Insights Generation**: Based on the analysis, deriving insights into booking trends, successful booking factors, and potential areas for business optimization.

## Results
The key findings from the EDA include:
- Patterns in booking success rates and occupancy percentages across different room categories.
- Insights into revenue generation, with a clear indication of the most profitable booking platforms and room categories.
- Identification of peak booking times and days, which can help optimize pricing strategies and promotional campaigns.
- Correlation between customer ratings and booking success, indicating areas for improvement in guest experience.
