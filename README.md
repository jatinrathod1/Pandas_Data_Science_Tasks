---

# Sales Data Analysis Using Python (Pandas & Matplotlib)

This repository contains a project focused on solving real-world data science problems using **Python Pandas** and **Python Matplotlib**. The project analyzes 12 months' worth of sales data from an electronics store to answer key business questions.

## Project Overview

The data comprises hundreds of thousands of purchases, broken down by:
- **Month**
- **Product type**
- **Cost**
- **Purchase address**, and more.

We use this dataset to perform data cleaning, manipulation, and visualization in order to provide business insights. The analysis is broken down into several tasks and questions aimed at understanding customer behavior and improving business performance.

---

## Table of Contents
1. [Data Cleaning](#data-cleaning)
2. [Business Questions Explored](#business-questions-explored)
3. [Tools and Libraries](#tools-and-libraries)
4. [Setup and Installation](#setup-and-installation)
5. [Results and Visualizations](#results-and-visualizations)

---

## Data Cleaning

Before analyzing the data, we clean it to ensure accuracy and consistency. This includes:

- **Dropping NaN values** from the DataFrame.
- **Removing rows based on a condition**, such as invalid or incomplete data entries.
- **Changing column types** to ensure correct data formats using `to_numeric`, `to_datetime`, and `astype` methods.

These tasks help in preparing the data for further analysis.

---

## Business Questions Explored

Once the data is cleaned, we explore five high-level business questions:

1. **What was the best month for sales?**  
   *How much was earned in that month?*
   
2. **Which city sold the most products?**  
   *Why did it perform better than others?*
   
3. **What time of day should we display advertisements to maximize product sales?**  
   *Identify the time period with the highest customer activity.*

4. **What products are most often sold together?**  
   *Are there any patterns of products frequently bought together?*

5. **Which product sold the most, and why?**  
   *Analyze the factors behind the best-selling product.*

---

## Tools and Libraries

This project utilizes the following Python libraries:

- **Pandas**: For data cleaning, manipulation, and analysis.
- **Matplotlib**: For creating visualizations, including bar charts and line graphs.

---

## Results and Visualizations

To answer the business questions, the following key methods and techniques were used:

- **Concatenating multiple CSV files**: Merged 12 months of sales data using `pd.concat`.
- **Adding new columns**: Extracted useful information from existing columns, such as splitting purchase addresses to get city names.
- **String parsing**: Created new columns by parsing cells as strings.
- **Using the `.apply()` method**: Applied custom functions to analyze patterns and conditions.
- **GroupBy operations**: Aggregated data to find total sales by month, city, and product.
- **Visualizations**: Plotted various bar charts and line graphs using **Matplotlib** to showcase the trends and insights.

---
