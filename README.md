# 📊 Retail Profitability & Discount Impact Analysis – Power BI

![Dashboard Overview](dashboard-overview.png)

## 📌 Project Overview
This project analyzes retail sales performance using the Global Superstore dataset, with a focus on understanding how discount strategies impact profitability across markets, categories and sub-categories.

## 🎯 Business Problem
Retail leadership needed to determine whether aggressive discounting was driving sustainable revenue growth or eroding profit margins.

Key Questions:
- How do discount levels affect overall profit margin?
- Which markets generate high revenue but weak profitability?
- Are specific product categories structurally unprofitable?
- Does shipping cost contribute to margin erosion?

## 🧹 Data Preparation
- Cleaned transactional sales data using Power Query
- Created calculated profit and margin measures
- Developed discount band segmentation (0%, 1–10%, 11–20%, 21%+)
- Built structured data model with relationships
- Analyzed performance across time, markets, categories, sub-categories, and customers.
- Converted the findings into operational pricing recommendations.

## 📐 Data Modeling
- Fact Table: Clean Orders
- Date dimension table implemented
- DAX measures created for:
  - Total Sales
  - Total Profit
  - Profit Margin %
  - High Discount Revenue %
  - Shipping Cost Analysis
 
## 🛠 Tools Used
- Power BI Desktop
- DAX
- Power Query
- Data Modeling
- Data Visualization & Business Storytelling

## 📊 Analytical Pages

### 1️⃣ Overview
- Total Sales: $12.64M
- Overall Profit Margin: 11.6%
- High Discount Orders: 25%
- Revenue Growth Trend (2012–2015)

### 2️⃣ Discount Impact
- Profit margin drops sharply beyond 20% discount
- High discount band (>21%) generates negative margin (-42%)
- High discounts drive revenue concentration but destroy profitability

### 3️⃣ Product & Operational Risk
- Tables category structurally unprofitable (-8.5%)
- Shipping cost heavily impacts margin in bulky products
- Sub-category analysis reveals margin variability

### 4️⃣ Strategic Recommendations
- Implement governance controls for discounts above 20%
- Redesign pricing for loss-making categories
- Introduce profitability-based sales incentives
- Monitor high-discount exposure monthly

## 🔍 Key Insights

- Total sales reached approximately $12.64 million, but the overall profit margin was only 11.6%.
- Approximately 25% of orders were classified as high-discount orders in the project dashboard.
- Discounts above 20% produced an estimated -42% margin, showing that aggressive discounting destroyed value.
- The Tables category recorded an estimated -8.5% margin, indicating structural profitability weakness.
- Shipping cost placed additional pressure on bulky and low-margin products.
- Revenue growth alone was therefore an incomplete performance measure.

## Recommendations

- Require approval for discounts above 20%.
- Evaluate sales teams using profitable revenue and contribution margin, not sales value alone.
- Redesign pricing, sourcing and shipping rules for loss-making categories.
- Create monthly exception reporting for high-discount exposure.
- Review customer and product combinations that repeatedly generate losses.
- Test targeted promotions rather than applying broad discounts.

## Business Value

The analysis turns a commercial question into measurable controls. It demonstrates how BI can support pricing governance, incentive design, product strategy, operational cost management and executive decision-making.

## Limitations

- Global Superstore is a demonstration dataset.
- The analysis is descriptive and does not prove that discounts alone caused every margin outcome.
- Product cost, competitor pricing, customer lifetime value and promotion objectives are not fully modeled.
- Currency and market differences may limit direct comparison.

## Future Improvements

- Add customer profitability and lifetime-value analysis.
- Model price elasticity and promotion uplift.
- Separate gross margin from fulfillment and shipping contribution.
- Add scenario testing for proposed discount thresholds.
- Create automated discount-governance alerts.

Author

Jack Kisutsa
Business Analyst | Business Intelligence Analyst | Financial & Performance Analyst
