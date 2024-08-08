# Introduction
The primary objective of this project is to analyze hotel bookings data to uncover patterns and trends. This includes examining cancellation rates, average daily rates, and the impact of various factors on booking behavior.

# Dataset
The dataset used in this project is a CSV file named `hotel_bookings 2.csv`. It contains information about hotel bookings, including details such as hotel type, lead time, arrival date, number of adults and children, booking status, and more.

# EDA and Data Cleaning
The following steps were performed during EDA and data cleaning:

Loaded the dataset and displayed basic information.
Converted the reservation_status_date column to datetime format.
Examined unique values in object-type columns.
Identified and removed columns with a high number of missing values (company and agent).
Dropped rows with missing values in the country column.
Removed outliers in the adr (average daily rate) column.
Verified that the dataset was clean and ready for analysis.
Data Analysis and Visualization
Key analyses and visualizations performed include:

Calculating and visualizing the percentage of cancelled and non-cancelled reservations.
Comparing cancellation rates between resort hotels and city hotels.
Analyzing the effect of average daily rates on reservation cancellations.
Examining monthly reservation and cancellation patterns.
Identifying top countries with the highest cancellation rates.
Analyzing the distribution of market segments and their impact on cancellations.
Conclusion
The analysis revealed several interesting insights about hotel booking patterns and cancellation behavior. For example, city hotels had a higher cancellation rate compared to resort hotels, and certain market segments were more prone to cancellations.
