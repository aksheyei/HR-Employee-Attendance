# Attendance Data Analysis (2022-2023)

A comprehensive data analytics project designed to track, visualize, and analyze attendance patterns over the 2022-2023 period. This repository contains the data transformations and interactive dashboard files built to extract actionable insights from raw attendance records.

## Project Overview
This project transforms raw daily tracking data into an interactive reporting system. The primary goal is to identify attendance trends, monitor presence/absence percentages, and highlight temporal variations across different months and demographic segments. 

## Data Source
* **Primary Dataset:** The analysis is driven by the foundational dataset `Attendance-Sheet-2022-2023.xlsx`.
* **Format:** The data includes detailed daily logs encompassing dates, personnel IDs, and status codes (Present, Absent, Leave, etc.).

## Tech Stack
* **Data Cleaning & Transformation:** Advanced Excel (Power Query) and Python (Pandas) for handling missing entries and standardizing formats.
* **Data Modeling & Visualization:** Microsoft Power BI. The data model utilizes a structured schema to connect date tables with the primary fact table.
* **Languages:** DAX (Data Analysis Expressions) for creating custom measures and KPIs.

## Key Features & Metrics
The interactive Power BI dashboard provides the following analytical views:
* **Overall Attendance Rate:** Calculates the macro-level presence percentage across the entire 2022-2023 timeline.
* **Monthly Trend Analysis:** Visualizes fluctuations in attendance to identify seasonal patterns or specific periods with high absentee rates.
* **Leave Categorization:** Breaks down absences into specific categories (e.g., sick leave, short leave, unexcused).
* **Individual Performance:** Slicer-driven views allowing users to filter metrics down to the individual level to track specific attendance records.

## Repository Contents
* `/data`: Contains the foundational `Attendance-Sheet-2022-2023.xlsx` dataset. *(Note: Ensure any PII is anonymized before uploading this file to a public repo).*
* `/dashboard`: Contains the primary `HR Dashboard.pbix` Power BI report file featuring the interactive visuals, custom data model, and schema structures.
* `/scripts`: Any Python or Excel macro scripts used during the initial ETL phase.

## Setup & Usage
1. Clone this repository to your local machine.
2. Ensure you have **Microsoft Power BI Desktop** installed to view the interactive dashboard.
3. Open `HR Dashboard.pbix` located in the `/dashboard` directory.
4. If prompted to refresh the data source, point the data source settings to the local path of the `Attendance-Sheet-2022-2023.xlsx` file.
