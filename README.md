# Spend Attribution 

A collection of SQL queries for attributing marketing spend, calculating spend based metrics (CAC, LTV) and building dashboards.
The goal of the work in this repository was to provide a 'single source of truth' regarding spend and turn raw data to actionable insights.

## 📈 Focus Areas
* **Consolidation:** Aligning spend from multiple external sources in various formats into a single source of truth for performance measurement and budgetary reporting. 
* **Analysis:** Code for critical high-level metrics (CAC, LTV) to track the performance of spend across multiple channels and markets.  
* **Visualisation:** Scripts for various dashboards to visualise spend by acquisition channel, market, user type, vertical and more.

## 🛠 Technical Features
* **Data Normalization:** Standardized output from multiple sources using differing conventions, currencies and languages into a single, cohesive schema, ensuring 'apples-to-apples' comparisons.
* **Window Functions:** Leveraged to calculate cumulative spend, rolling averages, and running totals. This enabled longitudinal analysis of spend performance and trend identification over time.
* **Common Table Expressions:** Modular, highly readable, maintainable, and testable code for quality control and easier debugging.

## 💼 Business Impact
* **Budget Optimization:** Building a single source of truth transformed disparate spend into a granular view enabling precise 'spend vs performance' analysis across Marketing. 
* **Lifetime Value:** Developed a robust LTV model that empowered Marketing to pivot from short-term acquisition toward high-value cohorts and long-term revenue maximization.
* **Performance Attribution:** Creating a suite of performance metrics (CAC, CPB, CPP) to ensure marketing spend was consistently allocated to the highest-ROI segments.

