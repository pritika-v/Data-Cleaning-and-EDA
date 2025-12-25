**Retail Sales Data Cleaning & Exploratory Data Analysis (EDA)
Project Overview**

This project focuses on performing comprehensive data cleaning and exploratory data analysis (EDA) on a retail sales dataset.
The objective is to prepare a clean, analysis-ready dataset and uncover meaningful business insights using statistical summaries and visualizations.
Objectives
Clean the raw dataset by handling missing values, duplicates, and inconsistencies
Ensure logical and business-relevant data integrity
Perform exploratory data analysis to understand sales patterns
Visualize key trends and relationships
Derive actionable business insights from the data

**Data Cleaning Steps**

The following data cleaning steps were performed:
Removal of duplicate records
Handling missing values:
Quantity filled using median
Item names filled with "Unknown"
Price per Unit and Total Spent derived using business logic
Discount Applied handled carefully to avoid incorrect assumptions
Data type corrections (dates, numerical, categorical variables)
Logical consistency checks (e.g., Quantity > 0, valid Total Spent)

Feature engineering:
Extraction of transaction month from date
Ordered categorical months (January–December)
The cleaned dataset was validated to ensure no missing values and no duplicates.

**Exploratory Data Analysis (EDA)**

The EDA includes the following visualizations and analyses:
Monthly Revenue Trend
Analyzes seasonal patterns in sales across the year
Top Product Categories by Sales
Identifies high-revenue product categories
Payment Method Distribution
Examines customer payment preferences
Location-wise Sales Performance
Compares in-store and online revenue contribution
Top 5 Items by Average Sales Value
Highlights high-value items per transaction
Correlation Analysis
Studies relationships between Price per Unit, Quantity, and Total Spent

**Key Business Insights**

Sales exhibit seasonal trends, with peak performance at the beginning and end of the year
Essential goods and household categories contribute significantly to total revenue
Both online and in-store channels are important, with online sales slightly higher
Customers actively use both cash and digital payment methods
Quantity sold has a stronger impact on total revenue than price alone

**Tools & Technologies Used**

Python
Pandas – data manipulation and cleaning
Matplotlib / Seaborn – data visualization
Google Colab – development environment
