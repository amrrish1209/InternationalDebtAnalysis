# International_Debt_Analysis 

International Debt Analysis project developed using **Python**, **Streamlit**, and **PostgreSQL**. This project focuses on analyzing global debt data, identifying country-wise debt distribution, indicator-based financial trends, and generating interactive analytics dashboards.

---

#  Implementation Details

## 1. Database Architecture (PostgreSQL)

I designed a structured relational database schema optimized for financial analysis and large-scale debt records.

### Key Implementations
- **Relational Schema:** Built a centralized debt analysis table containing country details, debt indicators, yearly financial records, and debt values.
- **Data Integrity:** Applied proper data types, constraints, and validations for handling numeric debt values and country-specific information.
- **Optimized Queries:** Used aggregation queries, ranking functions, subqueries, and window functions for advanced financial analysis.

---

#  Database Analysis & SQL Logic

To generate meaningful insights from the debt dataset:

### SQL Features Implemented
- **Aggregation Queries**
  - Total Debt
  - Average Debt
  - Global Contribution Percentage
  - Indicator-wise Debt Trends

- **Window Functions**
  - `RANK()`
  - `SUM() OVER()`
  - Partition-based ranking analysis

### Advanced SQL Analysis
- Top countries contributing highest debt
- Most dominant indicators for each country
- Global debt contribution percentage
- Debt categorization (High / Medium / Low)
- Cumulative debt analysis
- Indicator comparison against global averages

---

#  Application Features (Streamlit)

I developed an interactive analytical dashboard for exploring international debt statistics.

## Dashboard Features
- Interactive filtering for countries and indicators
- Country-wise debt analysis
- Indicator-wise debt comparison
- Global debt contribution analysis
- Top debt ranking system

---

#  Visual Analytics

The dashboard includes:
- Bar Charts for Top Debt Countries
- Pie Charts for Global Contribution
- Debt Trend Analysis Graphs
- Comparative Indicator Visualizations

---

#  Advanced Analytics & Reporting

## KPI Metrics
- Total Global Debt
- Average Debt
- Highest Debt Country
- Highest Contributing Indicator

## SQL Query Explorer
- Integrated SQL query execution system
- Predefined complex analytical queries
- Real-time analysis results

## Insights Generated
- Countries contributing more than 5% of global debt
- Indicators with highest average debt
- Debt difference between maximum and minimum values
- Country ranking based on total debt

---

#  Technologies Used

- Python
- Pandas
- NumPy
- SQL
- PostgreSQL
- SQLAlchemy
- Streamlit
- Plotly Express

---

#  Conclusion

This project demonstrates practical implementation of data analytics, database management, and dashboard development for large-scale international financial datasets.

The system provides meaningful insights into:
- Global debt distribution
- Country-wise debt patterns
- Financial indicator performance
- Comparative debt analytics

through advanced SQL analytics and interactive visualizations.

---
