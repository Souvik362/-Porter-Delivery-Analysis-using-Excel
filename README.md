**Data Overview**
The dataset used in this project is sourced from Kaggle:
Porter Delivery Time Estimation Dataset https://www.kaggle.com/datasets/ranitsarkar01/porter-delivery-time-estimation 

Project drive link:  https://drive.google.com/drive/folders/1boT5LJ5erbwHjfP6Cb9OtarDMzid9GEh?usp=sharing 

**Key Data Columns:**

market_id: Market identifier for each restaurant.
created_at: Timestamp when the order was placed.
actual_delivery_time: Timestamp when the order was delivered.
store_primary_category: Category of the restaurant.
order_protocol: The method through which the order was placed (e.g., Porter, call, third-party).
total_items_subtotal: Final price of the order.
num_distinct_items: Number of distinct items in the order.
total_onshift_partners: Number of delivery partners on duty at the time of the order.
total_busy_partners: Number of delivery partners already attending to other tasks.
total_outstanding_orders: Number of orders pending fulfillment at the time of the order.

**Excel Analysis Process**

The analysis is conducted using the provided Excel workbook, which contains the following sheets:

Raw Data: Contains the original dataset as received, with columns for order details, timestamps, and various performance metrics.
Data Cleaning: Includes steps taken to clean and preprocess the data, such as handling missing values, converting timestamps, and generating new calculated columns (e.g., delivery duration, peak hours).
Pivot Tables: Used to summarize key metrics such as average delivery time by market, store category, or order protocol.
Charts and Visualizations: Includes graphs like bar charts, line graphs, and histograms that visualize delivery trends, peak hours, and day-of-week performance.
Analysis: Insights and key findings are presented in a separate sheet with detailed analysis on performance metrics, correlations, and recommendations.

**Key Analysis Insights**

Order Volume by Market: Identified high-demand markets, helping optimize resource allocation and marketing strategies.
Delivery Time by Store Category: Analysis of delivery times across different restaurant categories highlighted areas requiring operational improvements.
Peak Hours and Days: Analysis of the peak times for orders enabled recommendations for optimized staffing and partner scheduling during busy periods.
Efficiency of Delivery Protocols: Identified which order protocols are linked to faster delivery times, informing potential areas for training or technology upgrades.
Impact of Partner Availability: Analyzed how the number of busy vs. on-shift partners impacts delivery time and provided recommendations for better partner scheduling during peak hours.


If you've done the Porter Delivery Optimization Project in Excel and now want to create a README.md file for your GitHub repository, the structure will be slightly different. Since the analysis is done using Excel rather than code, the focus will be on explaining the Excel-based approach, the datasets used, and how others can interact with your files.

Here's an updated README.md tailored for your Excel-based project:

Porter Delivery Optimization Project
Overview
Porter Delivery is a rapidly growing food delivery service facing challenges with delivery times, negatively impacting customer satisfaction. This project analyzes delivery data in Excel to identify key factors that influence delivery times and recommends actionable solutions to optimize delivery operations and improve customer satisfaction.

Problem Statement
The goal of this project is to analyze and optimize delivery times while maintaining service quality. By examining various aspects of the delivery process, the project aims to uncover bottlenecks and inefficiencies that can be addressed to improve delivery performance.

Key areas of focus:

Analyze delivery times across different markets, store categories, and time periods.
Identify correlations between variables like order volume, number of items, and partner availability.
Provide recommendations based on data insights to optimize the delivery process.
Data Overview
The dataset used in this project is sourced from Kaggle:
Porter Delivery Time Estimation Dataset

Key Data Columns:
market_id: Market identifier for each restaurant.
created_at: Timestamp when the order was placed.
actual_delivery_time: Timestamp when the order was delivered.
store_primary_category: Category of the restaurant.
order_protocol: The method through which the order was placed (e.g., Porter, call, third-party).
total_items_subtotal: Final price of the order.
num_distinct_items: Number of distinct items in the order.
total_onshift_partners: Number of delivery partners on duty at the time of the order.
total_busy_partners: Number of delivery partners already attending to other tasks.
total_outstanding_orders: Number of orders pending fulfillment at the time of the order.
Excel Analysis Process
The analysis is conducted using the provided Excel workbook, which contains the following sheets:

Raw Data: Contains the original dataset as received, with columns for order details, timestamps, and various performance metrics.
Data Cleaning: Includes steps taken to clean and preprocess the data, such as handling missing values, converting timestamps, and generating new calculated columns (e.g., delivery duration, peak hours).
Pivot Tables: Used to summarize key metrics such as average delivery time by market, store category, or order protocol.
Charts and Visualizations: Includes graphs like bar charts, line graphs, and histograms that visualize delivery trends, peak hours, and day-of-week performance.
Analysis: Insights and key findings are presented in a separate sheet with detailed analysis on performance metrics, correlations, and recommendations.
Key Analysis Insights
Order Volume by Market: Identified high-demand markets, helping optimize resource allocation and marketing strategies.
Delivery Time by Store Category: Analysis of delivery times across different restaurant categories highlighted areas requiring operational improvements.
Peak Hours and Days: Analysis of the peak times for orders enabled recommendations for optimized staffing and partner scheduling during busy periods.
Efficiency of Delivery Protocols: Identified which order protocols are linked to faster delivery times, informing potential areas for training or technology upgrades.
Impact of Partner Availability: Analyzed how the number of busy vs. on-shift partners impacts delivery time and provided recommendations for better partner scheduling during peak hours.
How to Use the Excel File
1. Download the Excel File
Download the Excel file from this repository to your local machine.
2. Open the Workbook
Open the Excel workbook in any version of Excel or Excel-compatible software.
The workbook contains multiple sheets for data cleaning, pivot tables, and analysis.
3. Review Key Metrics
Data Cleaning: Review the steps taken to clean and preprocess the data.
Pivot Tables: Check the pivot tables to explore average delivery times, order volume distribution, and more.
Charts & Visuals: Use the visualizations to quickly understand trends in delivery performance.
4. Explore the Insights
Check the "Analysis" sheet for detailed insights and recommendations based on the analysis.
Contributing
Contributions are welcome! If you have suggestions for improving the analysis or additional insights to share, feel free to fork the repository, make updates, and submit a pull request.


**Acknowledgments**

Porter Delivery for providing real-world data.
Kaggle for hosting the dataset.
Microsoft Excel for being the tool used for data analysis and visualization.

Notes:
This project leverages Excel to conduct data cleaning, analysis, and visualization. It provides valuable insights into delivery performance and operational inefficiencies.
The insights generated from this analysis can guide operational improvements, including partner scheduling, resource allocation, and marketing strategies.
