📊 Customer Behavior Analysis

End-to-end Data Analytics Project showcasing customer shopping behavior insights using Python, SQL, and Power BI.

📌 Overview

This repository contains an end-to-end analytics project that:

Loads and explores customer data

Performs data cleaning and analysis in Python

Runs analytical SQL queries on a PostgreSQL server

Builds an interactive business dashboard in Power BI

Produces a report and professional PPT using Gamma

The goal is to convert raw customer data into actionable insights and visual storytelling, demonstrating the essential skills of a Data Analyst. 
GitHub

🗂️ Dataset

File: customer_shopping_behavior.csv.xlsx 
GitHub

This dataset contains structured customer shopping records — such as customer IDs, purchase history, demographics, and transaction details — used to analyze buying patterns, preferences, and engagement.

🛠 Tools & Technologies
Purpose	Tools
Data Loading & Analysis	Python (Pandas, NumPy)
Exploratory Data Analysis	Matplotlib, Seaborn
SQL Queries	PostgreSQL
Dashboard & Visual Reporting	Power BI
Presentation	Gamma
🚀 Project Steps
1️⃣ Data Loading (Python)

Load dataset into Python using Pandas

Inspect columns, data types, and missing values

Initial overview of distribution and contents

2️⃣ Exploratory Data Analysis (EDA)

Visualize key metrics (e.g., purchase distribution, customer segments)

Spot trends, outliers, and relationships between variables

Generate insights that inform deeper analysis

3️⃣ Data Cleaning & Transformation

Handle missing or inconsistent values

Remove duplicates and fix formatting issues

Create derived fields if needed (e.g., total spend, frequency)

4️⃣ SQL Analysis (PostgreSQL)

Load cleaned data into PostgreSQL

Use queries.sql to perform advanced SQL analytics:

Aggregations (totals, averages)

Segment-wise analysis

Time-based performance

Filtering for business insights 
GitHub

5️⃣ Power BI Dashboard

Build an interactive dashboard using customer_behavior_dashbord.pbix

Include visuals like:

Key performance metrics

Trend charts

Customer segment breakdowns

Filter controls for exploration 
GitHub

6️⃣ Report & Presentation

Summarize findings in a clear PDF/Gamma presentation

Highlight business insights, patterns, and recommendations

Focus on conveying actionable insights to stakeholders

📊 Dashboard Highlights

The Power BI dashboard includes:

Interactive KPIs to monitor customer trends

Category-wise comparisons

Time series of purchase activity

Filterable segments for deeper drilling down

These enable business users to quickly understand performance and behavior.

📈 Results & Insights

This project reveals:

Patterns in customer purchases

Trends across demographic segments

High-value customer insights

Data-driven business suggestions for marketing and retention

Each deliverable supports stakeholder-ready insights and actionable decisions.

📦 Repository Structure
├── LICENSE
├── README.md
├── customer.ipynb                          # Python analysis notebook
├── customer_behavior_dashbord.pbix        # Power BI dashboard file
├── customer_shopping_behavior.csv.xlsx    # Dataset
└── queries.sql                            # SQL analysis scripts
``` :contentReference[oaicite:5]{index=5}

---

## ▶️ How to Run

### Requirements

Install dependencies:

```bash
pip install pandas numpy matplotlib seaborn sqlalchemy psycopg2

Python Notebook

Open customer.ipynb in Jupyter Notebook or VS Code

Load the dataset

Run each cell to perform analysis and visualizations

SQL Queries

Import cleaned data into PostgreSQL

Run queries from queries.sql in your PostgreSQL client

Export results for further use

Power BI Dashboard

Open customer_behavior_dashbord.pbix in Power BI Desktop

Connect the data source (PostgreSQL or imported file)

Refresh and interact with the visuals

Presentation

Use your exported dashboard visuals and insights to complete your Gamma presentation or PPT

🧠 Key Takeaways

By completing this project, you demonstrate:

✔ Full analytics lifecycle: data → insight → visualization
✔ Hands-on experience with Python, SQL, Power BI
✔ Ability to tell a data story with business impact
✔ Recruiter-ready portfolio example

👤 Author

Sourav Bhardwaj
Aspiring Data Analyst | Python | SQL | Power BI
