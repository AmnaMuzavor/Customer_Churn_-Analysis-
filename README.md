 Customer Shopping Behavior Analysis

Overview

This project analyzes customer shopping behavior using data from **3,900 purchases** across different product categories.

The main goal was to understand customer spending patterns, product preferences, subscription behavior, discounts, and customer segments.

I worked through the project using **Python for data cleaning and exploration, PostgreSQL for SQL analysis, and Power BI for the final dashboard**.


📊 Dataset

The dataset contains **3,900 rows and 18 columns**.

Some of the main information includes:

* Customer age, gender and location
* Subscription status
* Product and category information
* Purchase amount
* Season, size and color
* Discount usage
* Previous purchases
* Purchase frequency
* Review ratings
* Shipping type

There were **37 missing values in the Review Rating column**, which were handled during data cleaning.



 🛠️ Tools Used

Python – Data cleaning and exploratory data analysis
Pandas – Data manipulation
PostgreSQL – SQL analysis
Power BI – Interactive dashboard
GitHub – Project documentation



 🔄 Project Workflow

1. Data Loading & Exploration

I started by loading the dataset into Python using Pandas.

I used `info()` and `describe()` to understand the structure of the dataset and get an initial overview of the data.

2. Data Cleaning

I cleaned and prepared the data before moving into the analysis.

This included:

* Checking for missing values
* Filling missing review ratings using the median rating for each product category
* Renaming columns using snake_case
* Creating an `age_group` column
* Creating a `purchase_frequency_days` column
* Checking for redundant columns
* Removing `promo_code_used` after comparing it with `discount_applied`

The cleaned data was then connected to PostgreSQL for SQL analysis.

3. SQL Analysis

I used PostgreSQL to answer different business questions about customer purchases and revenue.

The analysis included:

1. Revenue by gender
2. High-spending customers who used discounts
3. Top 5 products based on average rating
4. Standard vs. Express shipping comparison
5. Subscribers vs. non-subscribers
6. Products with the highest percentage of discounted purchases
7. Customer segmentation into New, Returning and Loyal
8. Top 3 products in each category
9. Repeat buyers and subscription behavior
10. Revenue by age group

4. Power BI Dashboard

I used Power BI to turn the analysis into an interactive dashboard.

The dashboard focuses on:

* Customer and revenue overview
* Customer segmentation
* Product performance
* Subscription behavior
* Discount usage
* Age-group analysis
* Shipping analysis





💡 Key Business Recommendations

Based on the analysis, some of the main recommendations were:

Boost subscriptions by offering exclusive benefits to subscribers.
Encourage customer loyalty by rewarding repeat buyers.
Review the discount strategy to balance increased sales with profitability.
Promote top-rated and best-selling products in marketing campaigns.
Use age-group and customer insights  for more targeted marketing.



📂 Project Structure


Customer-Shopping-Behavior-Analysis/
│
├── data/
│   └── customer_shopping_behavior.csv
│
├── python/
│   └── data_analysis.ipynb
│
├── sql/
│   └── customer_shopping_behavior.sql
│
├── powerbi/
│   └── customer_shopping_behavior.pbix
│
├── report/
│   └── Customer Shopping Behavior Analysis.pdf
│
└── README.md

▶️ How to Run

 Python

Install the required libraries:


pip install pandas numpy matplotlib seaborn


Open the Jupyter Notebook in the `python` folder and run the notebook to reproduce the data exploration and cleaning steps.

 PostgreSQL

1. Create a PostgreSQL database.
2. Import the cleaned dataset.
3. Open the SQL file from the `sql` folder.
4. Run the queries to reproduce the analysis.

Power BI

Open the `.pbix` file using **Power BI Desktop**.

If required, update the data source and refresh the dashboard.



 📚 Skills Practiced

Through this project, I practiced:

* Data Cleaning
* Exploratory Data Analysis
* Python
* Pandas
* PostgreSQL
* SQL
* Customer Segmentation
* Business Analysis
* Power BI
* Data Visualization
* Data Storytelling



👩‍💻 Author

Amna Muzavor

Data Analytics | Python | SQL | Power BI


