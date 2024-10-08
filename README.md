# Credit Card Financial Dashboard

### Objective
The Credit Card Financial Dashboard is a comprehensive Power BI project designed to provide real-time insights into key performance metrics and trends of credit card operations. The dashboard enables stakeholders to monitor and analyze credit card usage and related data effectively.

### Project Features
1. Import Data: Data was imported into a PostgreSQL database.
2. Power BI Connection: Connected Power BI to the PostgreSQL database for seamless data retrieval.
3. Data Cleaning & Preprocessing: Performed data cleaning and preprocessing to ensure data quality.
4. DAX Queries: Utilized DAX (Data Analysis Expressions) queries to add analytical capabilities.
5. Interactive Dashboards: Created 2 interactive dashboards to visualize important metrics and trends.

### Steps Involved
1. Import Data into PostgreSQL
The credit card transactional data was imported into a PostgreSQL database. This involved:
   1. Setting up the database schema for efficient data storage.
   2. Loading data into PostgreSQL for real-time insights.
2. Connect Power BI to PostgreSQL
   1. Established a connection between Power BI and the PostgreSQL database for seamless data retrieval.
   2. Configured Power BI to auto-refresh, ensuring stakeholders view up-to-date data.
3. Data Cleaning & Preprocessing
   1. Applied data cleaning techniques such as handling missing values, correcting data types, and standardizing fields.
   2. Preprocessed data to aggregate weekly metrics, enabling more accurate and efficient reporting.
4. DAX Queries
   1. Created DAX measures for calculating important metrics such as revenue, weekly revenue, and income and age group.
   2. Developed calculated columns for further analysis.
6. Interactive Dashboards
Developed two interactive dashboards that provided:
   1. Credit Card Customer Report: The Credit Card Customer Report dashboard provides an overview of total transactions, total revenue, and average spend per transaction to analyze customer spending behavior. It includes a Customer Satisfaction Ratio, showing the percentage of satisfied customers. Revenue is visualized across different age groups, job categories, and top states, identifying key contributors to overall performance. An Expenditure Type Analysis highlights spending patterns across categories like groceries and travel. Finally, the dashboard segments data by gender, showing differences in revenue contributions and spending trends between male and female customers.
   2. Credit Card Financial Report: The Credit Card Financial Report dashboard presents key metrics such as total revenue, earnings from interest, and total transaction count, providing a clear overview of financial performance. It features interactive slicers that allow users to filter data by quarter, week, and gender segmentation for more granular analysis. Additionally, the dashboard highlights revenue by card category and includes a week-over-week revenue comparison, enabling stakeholders to track financial trends and performance over time.
