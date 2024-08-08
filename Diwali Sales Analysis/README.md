# Introduction
The primary objective of this project is to analyze hotel bookings data to uncover patterns and trends. This includes examining cancellation rates, average daily rates, and the impact of various factors on booking behavior.

# Dataset
The dataset used in this project is a CSV file named `hotel_bookings 2.csv`. It contains information about hotel bookings, including details such as hotel type, lead time, arrival date, number of adults and children, booking status, and more.

# EDA and Data Cleaning
The following steps were performed during EDA and data cleaning:

1.Loaded the dataset and displayed basic information.
2.Converted the reservation_status_date column to datetime format.
3.Examined unique values in object-type columns.
4.Identified and removed columns with a high number of missing values (company and agent).
5.Dropped rows with missing values in the country column.
6.Removed outliers in the adr (average daily rate) column.
7.Verified that the dataset was clean and ready for analysis.

# Data Analysis and Visualization
Key analyses and visualizations performed include:

1.Calculating and visualizing the percentage of cancelled and non-cancelled reservations.
2.Comparing cancellation rates between resort hotels and city hotels.
3.Analyzing the effect of average daily rates on reservation cancellations.
4.Examining monthly reservation and cancellation patterns.
5.Identifying top countries with the highest cancellation rates.
6.Analyzing the distribution of market segments and their impact on cancellations.
# Conclusion
The analysis revealed several interesting insights about hotel booking patterns and cancellation behavior. For example, city hotels had a higher cancellation rate compared to resort hotels, and certain market segments were more prone to cancellations.
