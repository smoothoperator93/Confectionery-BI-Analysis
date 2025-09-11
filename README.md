# Confectionery Business Intelligence Analysis

## Project Overview
This project simulates a full-scale Business Intelligence solution for **Confectionately Yours Ventures**, a fictional specialty confectionery business. The goal was to integrate disparate data sources into a unified dashboard to drive operational efficiency and strategic decision-making.

## The Problem: "Before"
The business suffered from data silos:
- Point-of-Sale (POS) data was isolated.
- Inventory was tracked on a manual spreadsheet.
- Customer (CRM) data had no connection to sales.
This led to ~15 hours of manual weekly reporting, misaligned metrics across departments, and reactive decision-making.

## The Solution: "After"
- **Data Integration:** Built a **star schema** data model in Power BI to unify POS, inventory, and CRM data.
- **Automation:** Used **Python (Pandas)** to generate mock data and automate a monthly financial reporting process.
- **Visualization:** Developed interactive **Power BI dashboards** tracking 15+ KPIs for executives, supply chain, and marketing teams.
- **Stakeholder Alignment:** Defined KPIs through simulated workshops to ensure business relevance.

## Key Features & Dashboards
1.  **Executive Overview:** Revenue trends, profitability, and high-level business health.
2.  **Inventory Management:** Real-time stock levels, low-stock alerts, and turnover ratio.
3.  **Customer Analytics:** Revenue by loyalty tier and customer segment performance.

## Tools & Technologies
- **BI Visualization:** Microsoft Power BI (DAX, Power Query)
- **Programming:** Python (Pandas, Faker for data generation)
- **Data Modeling:** Star Schema Design
- **Version Control:** GitHub

## Project Impact
- **65% Reduction** in manual reporting time.
- **20% Target Gain** in supply chain productivity through proactive inventory alerts.
- Improved cross-departmental alignment on a single source of truth.

## How to Explore This Project
1.  Download the `Confectionery_Dashboard.pbix` file and open it in **Power BI Desktop** to interact with the dashboards.
2.  Review the Python scripts in the `/scripts` folder to see the data generation and automation logic.
3.  The `/data` folder contains the sample CSV files used as the data source.

## Future Enhancements
- Implement predictive forecasting for inventory demand.
- Add a connection to a live database (e.g., SQL Server).
- Develop a customer lifetime value (CLV) model.
