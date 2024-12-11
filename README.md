# Credit Card Financial Dashboard

### Objective
The Credit Card Financial Dashboard is a comprehensive Power BI project designed to provide real-time insights into key performance metrics and trends of credit card operations. The dashboard enables stakeholders to monitor and analyze credit card usage and related data effectively.

### Project Features
1. Import Data: Data was imported into a PostgreSQL database.
2. Power BI Connection: Connected Power BI to the PostgreSQL database for seamless data retrieval.
3. Data Cleaning & Preprocessing: Performed data cleaning and preprocessing to ensure data quality.
4. DAX Queries: Utilized DAX (Data Analysis Expressions) queries to add analytical capabilities.
5. Interactive Dashboards: Created 2 interactive dashboards to visualize important metrics and trends.

### Tools & Technologies Used
1. PostgreSQL - Imported data into Database
2. pgAdmin - To Clean Data with SQL & Perform some fundamental analysis
3. Power BI - To Visualize Data 

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
5. Design Interactive Dashboards.

### Dashboards
#### 1. Credit Card Transaction Report Dashboard
This dashboard emphasizes financial performance:
- **Key Metrics**: Total revenue, transaction count, and interest earned.
- **Revenue Breakdown**:
   - By card category, job category, education level, and expenditure types.
   - Highlights quarterly revenue and transaction trends.
- **Payment Methods**: Demonstrates that 64% of revenue comes from swipe transactions.
- **Interactive Features**: Filters by gender, quarter, card category, and income group, enabling dynamic exploration of financial trends.
#### 2. Credit Card Customer Report Dashboard
This dashboard focuses on customer-centric insights:
- **Key Metrics**:  Total transactions, average spend per transaction, and overall satisfaction ratio.
- **Revenue Breakdown**:
   - Weekly Revenue Trends: Displays revenue week by week on a line graph, segmented by male and female customers.
   - Distribution of revenue by age group, job category, income group, and marital status.
   - Breakdown of top-performing states contributing to revenue.
- **Expenditure Types**: Highlights spending trends across categories like bills and entertainment.
- **Interactive Features**: Allows filtering by gender, week, quarter, and card usage method, providing granular insights into customer behavior.
#### 3. Client Demographics Dashboard
This dashboard provides insights into the distribution of clients across the U.S.:
- **Client Distribution**: Visualizes client numbers across states using an interactive map, highlighting regional trends.
- **Demographic Insights**: Offers an overview of client demographics and their geographical spread.
- **Interactive Features**: Includes filters for state and number of clients, enabling detailed analysis.
