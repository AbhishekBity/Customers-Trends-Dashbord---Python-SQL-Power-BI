# 📊 Customer Trends Dashboard – End-to-End Data Analytics Project

## 📌 Overview
This project demonstrates a complete data analytics lifecycle, transforming raw customer data into actionable business insights. Using **Python** for ETL, **MySQL** for deep-dive analysis, and **Power BI** for visualization, I analyzed customer behavior, revenue patterns, and subscription impact to drive data-informed decision-making.

---

## 🛠 Tools & Technologies
* **Python:** Pandas, SQLAlchemy (Data Cleaning, Imputation & Feature Engineering)
* **MySQL:** Advanced Querying (CTEs, Window Functions, Segmentation)
* **Power BI:** Interactive Dashboarding, DAX Measures, and KPI Tracking
* **Jupyter Notebook:** Exploratory Data Analysis (EDA)

---

## 🔄 Project Workflow

### 1️⃣ Data Loading & Exploration (Python)
The process began with an intensive EDA phase to understand distributions and identify data quality issues.
* **Initial Check:** Investigated 3,900+ records for null values and schema consistency.
* **Visualizing Data Structure:** Used `.info()` and `.describe()` to identify outliers in purchase amounts and ratings.

### 2️⃣ Data Cleaning & Feature Engineering
To ensure high-quality analysis, the following transformations were performed:
* **Smart Imputation:** Filled missing `Review Rating` values using the **median rating per product category** to maintain statistical accuracy.
* **Quantile Segmenting:** Created an `age_group` column using `pd.qcut` to ensure balanced demographic bins.
* **Frequency Mapping:** Converted categorical frequencies into a numerical `purchase_frequency_days` column for correlation analysis.
* **Deduplication:** Dropped redundant columns like `promo_code_used` after verifying a 100% correlation with `discount_applied`.


---

### 3️⃣ SQL Analysis (MySQL)
Cleaned data was migrated to a MySQL database for complex business querying. Key queries included:
* **Loyalty Segmentation:** Categorized customers as *New*, *Returning*, or *Loyal* based on purchase history.
* **Performance Ranking:** Used `ROW_NUMBER()` to identify the top 3 most purchased products within every category.
* **Subscription ROI:** Compared average spend between subscribers and non-subscribers.

---

### 4️⃣ Power BI Dashboard
Created a high-impact visual story to communicate findings to stakeholders:
* **Core KPIs:** Total Revenue ($233K), Average Purchase Value, and Avg Rating.
* **Sales Breakdown:** Visualized the dominance of the **Clothing** category ($104K revenue).
* **Demographic Insights:** Mapped revenue contribution across Age Groups and Genders.

---

## 📈 Key Insights
* **Revenue Leader:** The **Clothing** category generates the highest revenue, significantly outperforming Accessories and Footwear.
* **Subscription Value:** While only **27%** of the customer base is subscribed, they show higher retention and contribute significantly to stable revenue.
* **Demographic Focus:** **Adults** and **Middle-aged** segments are the highest spenders, providing a clear target for marketing campaigns.
* **Discount Sensitivity:** Discounts are a primary driver for purchase volume, especially in high-frequency categories.

---

## 🎯 Outcome
This project highlights a full-stack data proficiency:
* **Data Engineering:** Automating cleaning and feature creation.
* **Analytical Thinking:** Translating raw data into segmented customer tiers.
* **Visualization:** Creating "At-a-glance" intelligence for executive leadership.

---

## 📩 Contact Me
Let's connect! I am open to discussions regarding Data Analytics and Business Intelligence.

* **📧 Email:** [bityabhishekwork@gmail.com](bityabhishekwork@gmail.com)
* **🔗 LinkedIn:** [www.linkedin.com/in/abhishekbity](https://www.linkedin.com/in/abhishekbity)
