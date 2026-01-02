# 🛍️ The Look - E-Commerce Year-End Analysis

### 📊 Project Overview
This project focuses on analyzing customer behavior, sales performance, and operational challenges for "The Look," a fictional e-commerce clothing brand. The goal was to uncover profitability trends, identify churn risks, and optimize marketing spend using data-driven insights.

Using **DBT** for data transformation and **Power BI** for visualization, we processed raw sales data to create a comprehensive year-end report.

---

### 🛠️ Tech Stack & Tools
* **Data Warehouse:** Google BigQuery (The Look Dataset)
* **Transformation:** DBT (Data Build Tool)
* **Visualization:** Power BI
* **Analysis:** SQL, Data Modeling

---

### 💡 Key Findings & Insights

Based on the analysis of the 2019-2025 data projection:

#### 1. Profitability & Growth
* **Exponential Growth:** The company shows a significant profit spike starting in 2024, with a strong upward trend compared to previous periods.
* **Top Categories:** While "Outerwear & Coats" generates the highest total profit, niche categories like **Socks** (+78.7%) and **Maternity** (+75.8%) showed the highest year-over-year growth rates.

#### 2. Customer Acquisition & Demographics
* **Primary Channels:** **Email** and **Adwords** are the dominant channels for acquiring new customers, significantly outperforming organic search and social media.
* **Best Customers:** The **Middle-Aged (Orta Yaşlı)** segment generates the highest profit per user, followed closely by the Adult segment.
* **Retention:** The Repeat Purchase Rate is currently **37.52%**, with an average of 337 days between purchases.

#### 3. Operational Challenges (Returns & Cancellations)
* **High Risk Products:** "Intimates" and "Jeans" categories suffer from the highest volume of cancellations and returns.
* **Root Cause Analysis:** Specific traffic sources (e.g., Facebook) combined with specific geographies (e.g., Shanghai) showed higher-than-average order cancellation rates (approx. 17.5%).

#### 4. Geographic Performance
* **Top Markets:** **China** is by far the most profitable market (~478K profit), followed by the **United States** (~315K) and **Brazil** (~204K).
* **Strategic Hubs:** Key cities driving revenue include Shanghai, Beijing, and New York.

---

### 📷 Dashboard Visuals

#### Profitability & Product Trends
*(Analysis of profit margin by category and year-over-year growth)*

#### Customer Segmentation
*(Breakdown of customer value by age, gender, and acquisition channel)*

#### Geographic Distribution
*(Map visualization showing high-value regions in Asia and the Americas)*

---

### 🚀 Future Recommendations
1.  **Reduce Churn:** Investigate the high return rates in the "Intimates" category; consider sizing guide improvements.
2.  **Targeting:** Shift marketing budget towards **Email campaigns** targeting the "Middle-Aged" demographic, as they have the highest ROI.
3.  **Expansion:** Double down on the Chinese market logistics to support the high demand in Shanghai and Beijing.
