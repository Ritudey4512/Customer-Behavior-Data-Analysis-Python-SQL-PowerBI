# 🛍️ Customer Shopping Behavior Analysis

## 📌 Project Overview

The **Customer Shopping Behavior Analysis** project focuses on analyzing customer purchasing patterns, preferences, and subscription behavior using Python, SQL, and Power BI.

The objective is to transform raw transactional data into meaningful business insights that help organizations understand customer behavior, improve customer retention, and make data-driven decisions.

## 📊 Dataset

- **Total Records:** 3,900 purchases
- **Total Columns:** 18
- **Missing Values:** 37 values in the Review Rating column

### Key Attributes
- Customer demographics (Age, Gender, Location)
- Purchase details (Item, Category, Purchase Amount)
- Shopping behavior (Discount, Subscription Status)
- Shipping preferences
- Review Ratings and Purchase Frequency

## 🛠️ Tools & Technologies

| Tool | Purpose |
|---|---|
| Python | Data analysis and preprocessing |
| Pandas, NumPy | Data manipulation |
| Matplotlib, Seaborn | Exploratory data visualization |
| PostgreSQL | Database management and SQL analysis |
| Power BI | Interactive dashboard development |
| Gamma | Project presentation |
| Jupyter Notebook | Python development environment |

## 🔄 Project Workflow

### 1. Data Loading
- Imported the dataset using Pandas.
- Examined the dataset structure and dimensions.

### 2. Exploratory Data Analysis (EDA)
- Used `info()` and `describe()` for initial exploration.
- Analyzed customer demographics and purchasing patterns.
- Identified missing values and potential inconsistencies.

### 3. Data Cleaning & Preprocessing
- Handled missing Review Rating values using category-wise median imputation.
- Standardized column names using snake_case.
- Created age groups for customer segmentation.
- Derived purchase frequency features.
- Removed redundant columns.

### 4. SQL Analysis using PostgreSQL

Performed SQL queries to answer important business questions:

1. Revenue comparison by gender.
2. Identification of high-spending discount users.
3. Top 5 products based on customer ratings.
4. Comparison of Standard and Express shipping.
5. Subscriber vs. non-subscriber purchasing behavior.
6. Products with the highest percentage of discounted purchases.
7. Customer segmentation into New, Returning, and Loyal.
8. Top 3 most purchased products in each category.
9. Relationship between repeat purchases and subscriptions.
10. Revenue contribution by age group.

### 5. Power BI Dashboard

Developed an interactive dashboard to visualize customer shopping behavior.

**Dashboard Highlights:**
- Total number of customers
- Average purchase amount
- Average review rating
- Customer subscription distribution
- Revenue and sales by product category
- Revenue and sales by age group

The dashboard includes interactive filters for subscription status, gender, category, and shipping type.

### 6. Project Report & Presentation

- Prepared a project report documenting the analysis process and findings.
- Created a presentation using Gamma to communicate the project workflow and business insights.

## 📈 Key Results & Business Insights

The analysis provides insights into:

- Customer purchasing patterns and product preferences.
- Revenue contribution across different product categories.
- Differences between subscribers and non-subscribers.
- Customer spending behavior across age groups.
- The relationship between discounts, shipping preferences, and purchases.

## 💡 Business Recommendations

- **Boost Subscriptions:** Encourage customers to subscribe through exclusive benefits.
- **Customer Loyalty Programs:** Reward repeat customers to improve retention.
- **Discount Optimization:** Evaluate discount strategies while maintaining profitability.
- **Product Positioning:** Promote popular and highly rated products.
- **Targeted Marketing:** Focus marketing campaigns on valuable customer segments.

## ⚙️ How to Run the Project

### Step 1: Clone the Repository

```bash
git clone <your-repository-link>
```

### Step 2: Navigate to the Project Directory

```bash
cd Customer-Shopping-Behavior-Analysis
```

### Step 3: Install Dependencies

```bash
pip install pandas numpy matplotlib seaborn sqlalchemy psycopg2-binary
```

### Step 4: Run Python Analysis

Open the Jupyter Notebook:

```bash
jupyter notebook
```

Run the notebook cells to perform data cleaning, EDA, and preprocessing.

### Step 5: Run SQL Queries

- Set up a PostgreSQL database.
- Import the cleaned dataset.
- Execute the SQL scripts to reproduce the business analysis.

### Step 6: Explore the Dashboard

Open the Power BI `.pbix` file in Power BI Desktop to explore the interactive dashboard.

## 📁 Project Structure

```text
Customer-Shopping-Behavior-Analysis/
│
├── ProblemDocument/
|   └── Business Problem Document.pdf
├── Dataset/
│   └── customer_shopping_behavior.csv
│
├── Python/
│   └── Customer_Shopping_Behavior.ipynb
│
├── SQL/
│   └── Customer_Behavior_SQL_Queries.sql
│
├── Dashboard/
│   └── customer_behavior_dashboard.pbix
│
├── Report/
│   └── Customer Shopping Behavior Analysis.pdf
│
├── Presentation/
│   └── Customer-Shopping-Behavior.pptx
│
└── README.md
```

## 🎯 Conclusion

This project demonstrates an end-to-end data analytics workflow, starting from raw data preparation and exploratory analysis to SQL-based business insights and interactive Power BI visualization.

It highlights the importance of data-driven decision-making in understanding customer behavior, identifying business opportunities, and improving overall business performance.

---

**Skills Demonstrated:** Python | Data Cleaning | EDA | SQL | PostgreSQL | Power BI | Data Visualization | Business Analytics
