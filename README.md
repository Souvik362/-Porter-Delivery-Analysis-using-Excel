**Porter Delivery Optimization Project**

**Overview**

Porter Delivery is a growing food delivery service facing challenges with delivery times. This project analyzes delivery data using Excel to identify key factors influencing delivery times and recommends strategies to optimize operations and improve customer satisfaction.

**Problem Statement**

The aim of this project is to analyze and optimize delivery times by examining order volume, partner availability, and operational inefficiencies. The goal is to improve delivery performance while maintaining service quality.

**Data Overview**

The dataset comes from the Porter Delivery Time Estimation Dataset on Kaggle, and contains the following key columns:

market_id: Identifier for each restaurant

created_at: Timestamp when the order was placed

actual_delivery_time: Timestamp when the order was delivered

store_primary_category: Restaurant category

order_protocol: Method used for the order (Porter, call, third-party)

total_items_subtotal: Final price of the order

num_distinct_items: Number of distinct items in the order

total_onshift_partners: Number of delivery partners on duty

total_busy_partners: Number of delivery partners attending other tasks

total_outstanding_orders: Number of pending orders

**Analysis Process**

The analysis is done in Excel using the following steps:

Raw Data: Contains the original dataset.

Data Cleaning: Handles missing values, converts timestamps, and generates new calculated columns (e.g., delivery duration, peak hours).

Pivot Tables: Summarizes key metrics such as average delivery time and order volume.

Charts & Visualizations: Graphs displaying delivery trends, peak hours, and performance by day of the week.

Analysis: Detailed insights and recommendations based on the analysis.

**Key Insights**

Order Volume by Market: Identified high-demand markets for optimized resource allocation.

Delivery Time by Store Category: Highlighted restaurant categories requiring operational improvements.

Peak Hours and Days: Suggested staffing optimizations based on peak order times.

Efficiency of Delivery Protocols: Identified which protocols contribute to faster deliveries.

Impact of Partner Availability: Provided recommendations for partner scheduling during peak times.

**How to Use**

Download the Excel File: Get the Excel file from this repository.

Open the Workbook: Open the file in Excel or compatible software.

Explore the Data: Check sheets for cleaned data, pivot tables, charts, and analysis insights.

**Contributing**

Feel free to fork this repository, suggest improvements, and submit pull requests for updates or additional insights.

**Acknowledgments**

Porter Delivery for providing the dataset

Kaggle for hosting the dataset

Microsoft Excel for being the primary analysis tool
