# E-commerce Website Sales and Performance Analysis

**Prepared by:** [Your Name]  
**Date:** [Today’s Date]

## Executive Summary

This project analyzes the sales and performance of an e-commerce website using Power BI and MySQL. Key insights and visualizations were created to help stakeholders understand customer behavior, product demand, and operational efficiencies, guiding strategic decision-making.

---

## Project Objectives and Scope

The analysis aimed to reveal trends and key performance indicators (KPIs) relevant to stakeholders, including data analysts, marketing, and operations teams. Key objectives included:

1. Tracking sales performance through KPIs such as total revenue, average order value, and customer purchase frequency.
2. Analyzing customer demographics and segmentation to support targeted marketing.
3. Identifying product demand patterns by category to optimize inventory management.
4. Assessing operational efficiency metrics, such as delivery times and freight costs, to improve service delivery.

The dataset spans approximately 2-3 years, focusing on general trends across various seasons.

---

## Data Sources and Preparation

### Data Sources:
- **Sales and Customer Databases**: Order history, product categories, customer profiles, and payment types.
- **Web Analytics**: Customer engagement and website traffic data.

### Data Preparation:
1. **Standardizing Location Names**: Created a lookup table for state abbreviations and full names using ChatGPT, enhancing Power BI maps via VLOOKUP.
2. **Categorizing Unclassified Products**: Labeled uncategorized products as "Others" to ensure completeness.
3. **Removing Invalid Payment Types**: Excluded payment records from canceled orders to maintain data quality.
4. **Correcting Typos and Translations**: Fixed inconsistencies such as untranslated terms.
5. **Eliminating Duplicates**: Streamlined datasets by removing redundant entries.
6. **Calculating State Distances**: Built a distance table using ChatGPT and MySQL for geographic insights.
7. **Transition to MySQL**: Improved processing efficiency for large datasets, enabling real-time updates in Power BI.

---

## Key Metrics and Analytical Approach

### Key Metrics:
- **Customer Lifetime Value (CLV)**: Evaluating long-term customer profitability.
- **Average Purchase Frequency**: Gauging customer return rates.
- **Average Delivery Time**: Assessing delivery efficiency.
- **Customer Count, Seller Count, and Total Order Value**: Providing a comprehensive view of business volume.

### Analytical Approach:
- **Time-Series Analysis**: Identifying sales trends and peak periods.
- **Customer Segmentation**: Based on location and purchasing habits.
- **Geographical Analysis**: Assessing how distance from São Paulo impacts sales, freight costs, and delivery times.

---

## Dashboard Pages and Descriptions

### 1. **Sales Performance Analysis**
   - **Visuals Included:**
     - Monthly revenue trends over the 2-3 year period.
     - Sales distribution by product category.
     - Average revenue per customer.
   - **Insights:**
     - Seasonal sales peaks were identified, averaging $136 per customer.
     - "Beauty and Health" emerged as the top-selling category.

### 2. **Geographical Analysis**
   - **Visuals Included:**
     - Total sales and shipping costs by state.
     - Average shipping cost by distance from São Paulo.
   - **Insights:**
     - São Paulo dominated in both sales and seller presence.
     - Shipping costs increase proportionally with distance, highlighting potential logistical inefficiencies.

### 3. **Order Lifecycle and Delivery Analysis**
   - **Visuals Included:**
     - On-time vs. late deliveries.
     - Average delivery times by state and hour.
     - Delivery performance benchmarks.
   - **Insights:**
     - 92.13% of orders were delivered on time.
     - Delivery delays were more frequent in states farther from São Paulo.

### 4. **Customer Insights**
   - **Visuals Included:**
     - Distribution of new vs. returning customers.
     - Payment method preferences.
     - Customer lifetime value (CLV) and purchase frequency.
   - **Insights:**
     - 93.62% of customers were new, indicating a need for better retention strategies.
     - Credit cards were the most commonly used payment method.

### 5. **Seller Insights**
   - **Visuals Included:**
     - Sales performance by seller ID and state.
     - Top-performing sellers by total sales value.
   - **Insights:**
     - Most sellers were concentrated in São Paulo and nearby states.
     - A small percentage of sellers accounted for a significant portion of total sales.

### 6. **Product Demand Analysis**
   - **Visuals Included:**
     - Sales by product category.
     - Contribution of each category to overall revenue.
   - **Insights:**
     - "Beauty and Health" was the leading category, followed by "Bed, Bath & Table."
     - Clear patterns emerged, indicating high demand for personal care and home essentials.

---

## Recommendations

- **Target Marketing**: Focus on the "Beauty and Health" category during peak periods.
- **Optimize Logistics**: Consider regional warehouses to reduce delivery times and costs.
- **Customer Retention**: Implement loyalty programs and personalized offers.
- **Credit Card Promotions**: Increase sales through credit card-based rewards or discounts.

---

## How to Navigate the Dashboard

Each section in this `README.md` corresponds to a screenshot in the repository. Refer to the screenshots for detailed visuals and supporting data analysis.

---

## Appendix

- **Data Sources**: Sales, customer databases, and web analytics.
- **Data Preparation**: Standardization, categorization, and distance calculations using MySQL and Power BI.
- **Tools Used**: Power BI for visualization, MySQL for data processing.

---

This project demonstrates a data-driven approach to e-commerce performance analysis, providing actionable insights for strategic decision-making.
