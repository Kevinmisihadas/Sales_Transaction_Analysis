Sales Transaction Analysis & Interactive Power BI Dashboard

Project Overview

This project is an interactive sales analysis dashboard developed using Microsoft Power BI. The main aim of the project is to understand sales performance and present useful business insights in a simple and interactive way.

The project started with a sales transaction dataset containing information about customers, products, countries, payment methods, quantities, prices, and transaction dates. The data was first cleaned and organized, and then structured into a fact table and dimension tables.

After preparing the data, I built an interactive Power BI dashboard using DAX measures and different visualizations. The dashboard allows users to explore sales performance from different perspectives, including products, customers, countries, payment methods, and time periods.

Project Objectives

• Analyze overall sales performance
• Track total sales and number of transactions
• Analyze the quantity of products sold
• Calculate average order value and average unit price
• Compare sales across product categories
• Analyze sales across different countries
• Understand customer activity
• Analyze payment method preferences
• Identify sales trends over time
• Create an interactive and easy-to-use dashboard
• Provide detailed analysis using drill-through pages

Tools Used

• Microsoft Power BI – Dashboard development and data visualization
• Power Query – Data cleaning and transformation
• DAX – Creating measures and calculations
• Microsoft Excel – Initial data preparation
• GitHub – Project documentation and version control

Data Model

I used a star-schema approach to organize the data and make the analysis easier.

Fact_Transactions

The fact table contains the main transaction-level information such as sales, quantity, dates, and the keys connecting it to the dimension tables.

Dimension Tables

• Dim_Customer – Contains customer-related information
• Dim_Product – Contains product and category information
• Dim_Country – Contains country-related information
• Dim_Payment – Contains payment method information
• Dim_Date – Contains date-related information used for time-based analysis

The dimension tables are connected to the fact table through their respective keys.

DAX Measures

I created explicit DAX measures for the main calculations used in the dashboard.

The main measures include:

• Total Sales
• Total Transactions
• Total Quantity
• Average Order Value
• Average Unit Price

These measures are used across different visuals and automatically respond to the selected filters and slicers.

Dashboard

The dashboard was divided into multiple pages, with each page focusing on a particular aspect of the sales data.

Home Page

The Home page acts as the starting point of the report. I designed it with a modern look and included navigation to the different sections of the dashboard.

Sales Overview

This page provides a quick summary of the overall sales performance. It includes KPI cards and charts to show important metrics and sales patterns.

The page covers:

• Total Sales
• Total Transactions
• Total Quantity
• Average Order Value
• Average Unit Price
• Sales trends
• Product category performance
• Country-wise sales
• Payment method distribution

Product & Country Analysis

This page focuses on comparing sales across product categories and countries. It helps identify which categories perform better and how sales are distributed across different countries.

Time & Trend Analysis

This page focuses on understanding how sales change over time. The Dim_Date table is used to analyze sales by year, quarter, and month.

Customer & Payment Analysis

This page provides a closer look at customer activity and payment methods. It helps understand customer-level information and how customers complete their transactions.

Interactive Features

To make the dashboard more useful and easier to explore, I added several interactive features.

• Slicers
• Page navigation
• Cross-filtering
• Interactive charts
• Drill-through
• Back navigation
• Dynamic DAX measures

The slicers allow users to filter the dashboard based on fields such as year, country, product category, and payment method.

Drill-Through

Drill-through was added to provide more detailed information without making the main dashboard too crowded.

Customer Details

Users can select a customer and move to a dedicated customer details page to view more focused information.

Product Details

Users can also select a product category and move to a dedicated product details page for further analysis.

A back button is provided on the drill-through pages to return to the previous dashboard page.

Dashboard Design

I designed the dashboard using a modern purple-themed style with a dark background and glass-style elements. The same visual style was maintained across the different pages to make the report look consistent.

The dashboard uses a 16:9 page layout and includes clear headings, KPI cards, charts, slicers, and navigation elements.

The main focus of the design was to keep the dashboard clean, professional, and easy to understand while still making it visually appealing.

What I Learned

Through this project, I gained practical experience in:

• Cleaning and transforming data using Power Query
• Creating fact and dimension tables
• Building a star-schema data model
• Creating relationships between tables
• Writing DAX measures
• Creating interactive Power BI dashboards
• Selecting appropriate visualizations
• Using slicers and cross-filtering
• Creating page navigation
• Implementing drill-through functionality
• Designing a consistent dashboard theme
• Presenting data in a simple and business-friendly way

