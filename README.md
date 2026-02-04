# Business Sales Analysis Project (EDA)

## 📌 Project Overview
This project focuses on performing **end-to-end Exploratory Data Analysis (EDA)** on a business sales dataset to understand product performance, category-wise revenue distribution, pricing behavior, and sales patterns.

The objective of this analysis is to extract **data-driven business insights** that can help in decision-making related to product strategy, pricing, and revenue optimization.

---

## 📂 Dataset Description
The dataset contains transactional sales data with the following key attributes:

- **Order_ID** – Unique identifier for each order  
- **Product** – Name of the product  
- **Category** – Product category (Electronics, Accessories, Unknown)  
- **Quantity** – Number of units sold  
- **Price_per_Unit** – Price of a single unit  
- **Total_Sale** – Total revenue generated per order  

The dataset includes missing values and category inconsistencies to simulate **real-world data quality challenges**.

---

## 🛠 Tools & Libraries Used
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  

---

## 🔍 Key Analysis Steps

### 1️⃣ Data Cleaning & Validation
- Identified and handled missing values logically  
- Standardized product categories to remove inconsistencies  
- Validated numerical relationships such as `Total_Sale = Quantity × Price_per_Unit`  
- Ensured clean and reliable data before analysis  

### 2️⃣ Category-Level Sales Performance
- Compared total revenue and quantities sold across categories  
- Identified dominant revenue-generating categories  

### 3️⃣ Product-Level Sales Analysis
- Analyzed top-performing products based on total sales  
- Evaluated product contribution to overall revenue  

### 4️⃣ Pricing vs Quantity Relationship
- Studied the relationship between product price and quantity sold  
- Used correlation analysis and scatter plots to understand pricing sensitivity  

### 5️⃣ Revenue Contribution Analysis
- Examined how revenue is distributed across products and categories  
- Identified revenue concentration risks  

### 6️⃣ Distribution Analysis
- Analyzed the distribution of:
  - Price per unit  
  - Quantity sold  
  - Total sale value  
- Used histograms and boxplots to understand spread, skewness, and order behavior  

### 7️⃣ Feature Engineering
- Created new interpretable features such as price categories and quantity types  
- Enhanced analytical depth without unnecessary complexity  

---

## 📊 Key Business Insights

- Accessories outperform electronics across all key metrics, including average price per unit, quantity sold, and total sales, making them the primary revenue driver.
- Higher sales volume combined with higher average pricing enables accessories to contribute more significantly to total revenue.
- Accessories show strong customer demand even at relatively higher price points.
- Revenue is heavily concentrated in the accessories category, indicating dependency risk.
- Electronics contribute comparatively lower revenue due to reduced sales volume, suggesting potential improvement opportunities.
- Laptop and Headphones are the best-performing products in terms of revenue contribution.
- Products classified under the Unknown category contribute minimally and can be discontinued or replaced.
- Most revenue comes from low-to-medium quantity orders, with few high-quantity bulk orders.
- Cheaper products contribute less to total revenue, indicating a customer preference for mid-to-high priced products.
- Optimizing the product mix by focusing on high-performing accessories while improving pricing or demand strategies for electronics can help balance revenue distribution.

---

## ⚠️ Limitations
- The dataset does not include customer-level or time-based information.
- Analysis is limited to product, pricing, and category performance.
- Customer retention and trend analysis could not be performed.

---

## 🚀 Future Scope
- Incorporate customer data to analyze repeat purchases and customer segmentation  
- Add time-series data to study seasonal trends and growth patterns  
- Extend analysis into predictive modeling after sufficient historical data  

---

## 📎 Conclusion
This project demonstrates a structured approach to data analysis by combining data cleaning, visualization, and business reasoning. The focus remains on extracting meaningful insights rather than applying unnecessary complexity.

---

👤 **Author**: Pranay Jha  
