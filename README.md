## 🧠 RFM Customer Segmentation & Demographic-Geographic Insights

This project applies **RFM (Recency, Frequency, Monetary)** analysis to a customer dataset and enhances the segmentation with **demographic** (age, gender, income, marital status, occupation) and **geographic** (country, region) attributes. The goal is to generate actionable customer insights for marketing and retention strategies.

---

## 📌 Project Description

We use RFM analysis to segment customers into behavior-based groups (like Champions, At Risk, etc.) and then overlay it with demographics and geography to better understand **who** our customers are, **where** they come from, and **how** they behave. This helps in **targeted marketing**, **churn prediction**, and **resource allocation**.

---

## 🔧 Tools Used

- Python (Pandas, Seaborn, Plotly, Matplotlib)
- Power BI (for dashboards)
- Excel (data cleaning & summaries)
- Jupyter Notebook (EDA & feature engineering)

---

## 🎯 Key RFM Segments

- **Champions**: Frequent & recent buyers, top spenders
- **Loyal Customers**: High frequency, decent spending
- **Potential Loyalists**: Recent buyers, mid-frequency
- **At Risk**: High spenders but no recent activity
- **Hibernating**: Inactive for long, low spenders

---

## 📊 Demographic Insights

- **Gender Split**: 50% Male, 50% Female – No significant difference in spending
- **Marital Status**: 50% Married, 50% Single – Equal distribution across segments
- **Age Group**:
  - Spending behavior is uniform across age groups
  - No group shows significantly higher churn
- **Income vs Spend**: Lower income groups spend nearly the same as higher income ones → Indicates strong product-market fit or pricing strategy
- **Occupation**: Segments show balanced distribution across job types

**Visualizations**:
- Bar chart: Age group vs RFM Segment count (X: Age group, Y: Number of customers)
- Boxplot: Income vs Monetary Value (X: Occupation, Y: Spend)
- Donut Charts: Gender / Marital Status distribution across segments

---

## 🌍 Geographic Insights

### 🌎 Country-Wise Distribution

| Country        | Customers | Total Spend |
|----------------|-----------|-------------|
| United States  | ~60,000   | Highest     |
| Australia      | ~40,000   | High        |
| United Kingdom | ~30,000   | High        |
| France         | ~20,000   | Moderate    |
| Germany        | ~15,000   | Moderate    |
| Canada         | ~10,000   | Lowest      |

- **US dominates** in both customers and total monetary value
- **UK & Germany** show strong European presence
- **Room for growth** in France, Canada, and Scandinavian countries

### 🗺️ Regional Map Visuals (Europe)

- **Left Map**: Customer count by country (X: Country, Y: No. of customers)
- **Right Map**: Total monetary value (X: Country, Y: Total spend)
- UK and Germany show the **darkest blue shades**, indicating high customer and revenue density

---

## 📌 Business Takeaways

- **Top Market**: United States (highest customers + revenue)
- **High Opportunity Zones**: France, Belgium, Netherlands
- **Stable Segments**: Even demographic split helps universal campaigns
- **RFM-Aided Targeting**: Use high-CLV segments like Champions & Loyalists for upselling and brand advocacy

 
