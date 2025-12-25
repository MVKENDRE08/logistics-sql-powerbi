# 📦 Logistics Operations Analysis (SQL & Power BI)

# 📌 Project Overview

This project analyzes real-world logistics and transportation data (2022–2024) to evaluate operational performance across drivers, trips, routes, fuel costs, and revenue.
The objective was to simulate a real data analyst workflow — starting from raw CSV files, validating data quality in SQL, performing structured analysis, and presenting insights through a Power BI dashboard.

## 🗂️ Dataset Description

The dataset represents end-to-end logistics operations and includes:

- drivers.csv – Driver demographics and employment details

- trucks.csv – Fleet and equipment information

- loads.csv – Shipment bookings and revenue data

- trips.csv – Trip execution and performance metrics

- fuel_purchases.csv – Fuel transaction records

- delivery_events.csv – Pickup and delivery timestamps

All CSV files were imported into SQL Server using the Import Data Wizard.

## 🛠️ Tools Used

- SQL Server / SSMS

- SQL (Joins, Subqueries, CASE statements, Window Functions)

- Power BI (KPI cards, trends, route and terminal analysis)

# 🔍 Project Workflow

## 1️⃣ Data Loading & Validation

- Imported multiple CSV files into SQL Server

- Validated record counts to ensure no data loss

- Identified orphan records using NOT EXISTS checks

## 2️⃣ Data Cleaning

- Handled missing revenue values

- Flagged cancelled loads for exclusion from performance analysis

- Identified potential data quality issues without deleting records

## 3️⃣ Data Analysis (SQL)

- Analyzed driver workload and revenue contribution

- Calculated average fuel cost per trip using subqueries

- Evaluated delivery punctuality using timestamp comparisons

- Categorized trip efficiency using CASE logic

- Ranked drivers and identified top performers using window functions

## 4️⃣ Visualization (Power BI)

- Built KPI cards for revenue, trips, and drivers

- Analyzed revenue trends over time

- Identified top revenue-generating routes

- Visualized driver distribution by terminal

## 📊 Key Business Questions Answered

- Which drivers contribute most to trip volume and revenue?

- Which routes generate the highest revenue?

- What is the average fuel cost per trip?

- How is the driver workforce distributed across terminals?

- How does revenue trend over time?

## 📈 Key Insights

- Revenue remained stable over time, indicating consistent operational performance

- A small number of routes contributed a significant share of total revenue

- Driver contribution varied significantly by terminal and workload

- Average fuel cost per trip provided a realistic operational efficiency benchmark

## ✅ Skills Demonstrated

- SQL-based data validation and quality checks

- Multi-table joins and subqueries for aggregation

- Business classification using CASE statements

- Window functions for ranking and running totals

- Translating SQL analysis into clear Power BI visuals

- Business-focused interpretation of operational data

