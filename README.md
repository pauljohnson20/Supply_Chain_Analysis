# Supply_Chain_Analysis

### Table of Contents:
- [Project Overview](#project-overview)
- [Business Objective](#business-objective)
- [Data Source](#data-source)
- [Tools Used](#tools-used)
- [Data Understanding](#data-understanding)
- [KPIs](#kpis)
- [Data Cleaning](#data-cleaning)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Data Analysis (Tableau Visuals)](#data-analysis-tableau-visuals)
- [Project Insights](#project-insights)
- [Recommendations](#recommendations)
- [How to Use This Report](#how-to-use-this-report)
- [Contact](#contact)

### Project Overview:
This project focuses on analyzing the supply chain performance using a Tableau dashboard. The dashboard presents key metrics such as customer sales, quantity, lead time, and delivery performance. Filters allow users to explore data by year, quarter, or month and analyze top products.

### Business Objective:
Supply chain inefficiencies, such as late deliveries and high lead times, can significantly affect customer satisfaction and operational costs. This analysis aims to provide insights into these inefficiencies and help identify areas for improvement. The goal is to optimize processes and reduce operational costs.

### Data Source:
The data is provided in a CSV file format, containing detailed records related to supply chain operations.
[Download Dataset](https://www.kaggle.com/datasets/shashwatwork/dataco-smart-supply-chain-for-big-data-analysis)

### Tools Used:
  - Python
  - SQL
  - Tableau

### Data Understanding:
The dataset consists of 180,519 records across 53 columns, capturing essential details related to orders, customers, sales, shipping modes, and delivery statuses.

### KPIs:
  1. Total customers, total sales, quantity shipped, average shipping days, late deliveries
  2. Lead time distribution by region
  3. Late delivery percentage for each region and lead time
  4. Shipping mode efficiency
  5. Overall sales by department
  6. Loss over profit percentage
  7. Top N products by profit and loss
  8. Sales and number of customers by country
  9. Profit and loss by discount range
  10. Interactive dashboard [View Dashboard](https://github.com/user-attachments/assets/f1c5f4e0-28ee-4adc-83a5-512b4bbf6e6c)

### Data Cleaning:
  - Connected MySQL database to Python for data extraction and manipulation
  - Created structured tables from raw CSV data in MySQL
  - Removed unwanted columns that were not relevant for analysis
  - Ensured data consistency and accuracy before visualization in Tableau

### Exploratory Data Analysis:
  - **Shipping Mode Delay Patterns:** First Class and Second Class shipping modes show significantly high late delivery rates, with 95% and 76% respectively.
  - **Delivery Status Distribution:** Over 50% of total orders are delivered late, while on-time and advance deliveries contribute around 20% each. Shipping cancellations are relatively low at 5%.
  - **Lead Time Impact:** Extremely short (1 day) and long (5–6 days) lead times have the highest late delivery percentages, despite contributing less to overall orders.
  - **Geographical Customer Distribution:** More than 65% of customers are concentrated in the USA, France, and Mexico, indicating high regional engagement.
  - **Departmental Order Volume:** Fan Shop, Apparel, and Golf departments account for over 80% of total orders, highlighting them as major contributors.

### Data Analysis (Tableau Visuals):
Tableau is used for interactive visualizations, including:
  - Card views for key metrics (customers, sales, quantity, average shipping days, and late delivery).
  - Filters for dynamic analysis (select year/quarter/month, top N products).
  - Lead time analysis by region with tooltips showing delivery status.
  - Bar charts for shipping mode vs total orders, department vs total orders, and product profitability.
  - Map visualization for sales and customer distribution.

Snap of Supply Chain Analysis Dashboard

![Image](https://github.com/user-attachments/assets/f1c5f4e0-28ee-4adc-83a5-512b4bbf6e6c)

### Project Insights:
  - **First Class Shipping Mode is Highly Inefficient:** Almost all First Class orders result in late delivery, affecting customer satisfaction.
  - **Lead Time Extremes Correlate with Delays:** Both very short and very long lead times are strongly associated with late deliveries.
  - **Losses Are High Relative to Profits:** All products show over 45% loss compared to their profits, suggesting inefficiencies in pricing or cost management.
  - **Order Distribution is Skewed by Geography:** A majority of orders and customers are localized to three countries, creating regional dependencies.
  - **Top Departments Drive Sales:** A small number of departments generate the bulk of the orders, offering clear targets for focused improvements.

### Recommendations:
  - **Optimize or Limit First Class Shipping:** Due to high late delivery rates, reevaluate the use of First Class shipping or improve logistics under that mode.
  - **Reassess Lead Time Strategies:** Avoid extremely short or long lead times which contribute disproportionately to late deliveries.
  - **Investigate High Loss Ratios:** Conduct a deep dive into pricing, procurement, and operational costs to reduce the loss-to-profit percentage.
  - **Expand Customer Base Regionally:** Explore marketing or expansion strategies in underrepresented countries to reduce geographic risk.
  - **Prioritize High-Volume Departments:** Focus on process improvements and promotions in Fan Shop, Apparel, and Golf to maximize impact on sales and delivery performance.

### How to Use This Report:
  - Apply Filters:
      - Use dropdowns to filter by Year, Quarter, or Month.
      - Select multiple periods with the secondary filter.
      - Filter top N products (up to 20) for focused analysis.
  - Check Key Metrics:
      - View KPIs for Customers, Sales, Quantity, Shipping Days, and Late Deliveries.
      - Quickly gauge overall supply chain performance.
  - Lead Time Insights:
      - Analyze Lead Time by Region for total orders, late deliveries, and delay %.
      - Spot inefficiencies based on lead time patterns.
  - Category Performance:
      - Compare Shipping Modes and Departments by total orders.
      - Use color-coded delivery status and tooltips for more detail.
  - Profitability & Geography:
      - Review Product Profitability vs Discount Range and Loss-to-Profit %.
      - Use map view to see Sales and Customer Count by Country.

### Contact:
For further information or inquiries regarding this project, feel free to reach out:
  - Email     : pauljohnson2094@gmail.com
  - LinkedIn  : www.linkedin.com/in/pauljohnson2094
  - GitHub    : https://github.com/pauljohnson20
