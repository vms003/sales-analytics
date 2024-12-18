# Sales Analytics Project
------------------------------------------------------------------------------------------------------------------------------------------------
## Overview
This project is a comprehensive Sales Analytics solution aimed at uncovering actionable insights from sales data. Leveraging Python, the project encompasses data cleaning, exploratory data analysis (EDA), visualization, and advanced analytics techniques such as customer segmentation and clustering. The goal is to provide a detailed understanding of sales trends, customer behavior, and seller performance, empowering businesses to make data-driven decisions.

---

## Key Features

### Data Cleaning
- Addressed missing values and removed duplicates.
- Standardized date formats for analysis.
- Combined datasets into a unified `final_order` DataFrame.

### Exploratory Data Analysis (EDA)
- Identified sales trends by order status, product categories, and time periods.
- Conducted revenue trend analysis and cohort analysis for customer retention.
- Assessed seller performance and customer purchase behavior.

### Seller Segmentation
- Categorized sellers into `Platinum`, `Gold`, `Silver`, and `Bronze` tiers based on revenue.
- Visualized seller distribution across segments.
- Highlighted top-performing sellers for targeted strategies.

### Customer Purchase Behavior Analysis
- Grouped customers by purchase frequency into `One-time`, `Occasional`, `Frequent`, and `Loyal Buyers`.
- Visualized purchase behaviors to identify loyalty trends.
- Listed top loyal customers for reward programs.

### Cross-Selling Opportunities
- Identified frequently purchased product combinations.
- Visualized the top 10 product pairings for cross-selling.
- Analyzed product categories for upsell potential.

### Payment Behavior Insights
- Analyzed and visualized the distribution of payment methods.
- Highlighted popular payment methods to streamline checkout experiences.

### Customer Satisfaction Analysis
- Assessed average ratings for product categories.
- Visualized product category ratings to highlight customer preferences and pain points.

### Customer Segmentation with K-Means Clustering
- Applied RFM (Recency, Frequency, Monetary) analysis.
- Clustered customers into actionable segments using K-Means.
- Provided detailed customer profiles for tailored marketing strategies.

---

## Technologies Used
- **Programming Language**: Python
- **Libraries**: pandas, numpy, matplotlib, seaborn, scikit-learn

---

## Project Structure
```
|-- CUSTOMERS.csv
|-- GEO_LOCATION.csv
|-- ORDER_ITEMs.csv
|-- ORDER_PAYMENTS.csv
|-- ORDER_PAYMENTS.csv
|-- ORDER_REVIEW_RATINGS.csv
|-- ORDERS.csv
|-- PRODUCTS.csv
|-- SELLERS.csv             
|-- sales_analytics.ipynb      # Python scripts for data processing and analysis
|-- README.md                  # Project documentation
|-- requirement.txt            # Required Libraries
```

---

## Results and Insights

### Seller Segmentation
- Sellers categorized into performance tiers (`Platinum`, `Gold`, `Silver`, `Bronze`).
- Top-performing sellers identified for strategic focus.

### Customer Insights
- Majority of customers are `One-time Buyers`, but loyal buyers contribute significantly to revenue.
- Detailed customer segments based on purchase behavior and RFM analysis.

### Cross-Selling Opportunities
- Discovered common product combinations, aiding cross-sell strategies.
- Insights into complementary product categories for upselling.

### Payment Behavior and Satisfaction
- Popular payment methods identified to optimize checkout experiences.
- Product category ratings analyzed to enhance customer satisfaction.

---

## How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/vms003/sales-analytics.git
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the analysis:
   - Open the Jupyter Notebooks sales_analytics.ipynb .
   - Execute cells sequentially to replicate the analysis.

---

## Future Enhancements
- Perform sentiment analysis on customer reviews for deeper insights.
- Automate the data pipeline for real-time analytics.
- Develop interactive dashboards using Tableau or Power BI.

---

## Author
**Viraj Suthar**
- **Email**: [virajsuthar2003@gmail.com](mailto:virajsuthar2003@gmail.com)
- **GitHub**: [https://github.com/vms003](https://github.com/vms003)
- **LinkedIn**: [https://www.linkedin.com/in/viraj-suthar-517445333/](https://www.linkedin.com/in/viraj-suthar-517445333/)

---
Feel free to reach out for collaboration, feedback, or inquiries!