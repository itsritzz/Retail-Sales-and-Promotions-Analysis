# Retail Sales and Promotions Analysis with Tableau
## Introduction
Retail promotions play a crucial role in driving sales, serving as strategic tools to boost consumer purchasing. However, while promotional campaigns often lead to increased sales volume, they also come at the cost of reduced prices. Therefore, it's imperative for retailers and companies to assess the effectiveness of promotions beyond short-term volume increases, focusing on their impact on profit margins and long-term sales. Our session today delves into evaluating the true effectiveness of sales promotions, leveraging insights to inform smarter, data-driven marketing strategies.

---

## Objective
Our objective is to gain an essential understanding of sales promotions' impact on sales volume and profitability in a cost-conscious era. We aim to decode the relationship between promotion expenditure and sales increase, identify the precise moments when investments yield significant returns, analyze promotional trends and patterns to address underlying challenges, and establish a pathway to a profitable, data-informed future in retail marketing.

---

## Data Breakdown: Understanding Columns, Descriptions, and Overall Complexity
- **Dataset Overview:**
  - Number of Rows: 134,908
  - Number of Columns: 41+
  - Companies: 5
  - Categories: 3
  - Sub Categories: 4
  - Types of Promos: 2
- **Key Columns:**
  - Actual Quantity: Sales volume post-promotion.
  - Actual Average Price: Price after promotion.
  - Average Sales Value: Calculated as Product 1 and 2.
  - Baseline Average Price: Pre-promotion price.
  - Baseline Quantity: Sales volume pre-promotion.
  - Baseline Revenue: Calculated from Metrics 4 and 5.
  - Average Unit Uplift: Change in sales volume due to promotion.
  - Baseline Profit: Profit before the promotion.
  - Incremental Profit: Additional profit earned from the promotion.
  - Promotional Investment: Funds allocated for the promotion.
  - Return on Investment (ROI): Percentage of profit from investment.

---

## Data Preprocessing
- **Handled Duplicated Columns:**
  1. ActualAvgPrice (Promo-level) - Avg_Price (Promo-level)
  2. Date - Max_Date - Min_Date
  3. Lift (Promo-level) - PromoLift(%) (Promo-level)
  4. Unit volume - Unit volume2 (Promo-level) - Unit volume2 (Promo-level)2
- **Handled Outliers**
- **Feature Engineering:**
  1. Normalization of ROI: Weighted ROI adjusts for sales volume differences, ensuring fair comparisons.
  2. Comparative Analysis: Enables evaluation across products, brands, or categories for identifying top performers.
  3. Strategic Decision Making: Guides resource allocation and future promotion planning.

---

## Visualizations

### 1. Company vs Products Sold
- **Insights:**
  - Company III: High product count (70K+) suggests potential market leadership or successful sales strategy during promotions.
  - Company I and Company IV: Moderate product counts (14K+ and 40K+) indicate stable market presence and potentially loyal customer bases.
  - Companies II and V: Low product counts highlight opportunities for market expansion or increased promotional efforts.

### 2. Promo ROI
- **Insights:**
  - Company III's Strategy Concerns: ROI decline from 10.9 to -70.9 indicates ineffective promotions, urging a strategic overhaul to reverse the trend.
  - Company V's Seasonal Performance: ROI peak at 116.8 followed by a dip to 6.2 suggests potential over-reliance on seasonal campaigns, highlighting the need for year-round promotional stability.
  - Company I and Company IV's Performance: Company I shows ROI improvement by 2015 Q1, indicating a potential strategic shift or improved market conditions. Company IV maintains generally positive ROI except in 2015 Q1, demonstrating an effective promotional strategy with room for stability improvement.

### 3. Product Ranking Based on Profit
- **Insights:**
  - Company III's Product Variability: High profit variability suggests inconsistent performance or diverse product success levels.
  - Company I's Losses: Several products incurring substantial losses indicate a need for critical review or strategy adjustment.

### 4. Product Sales & Investment Analysis
- **Insights:**
  - Sales Volume vs. ROI: High sales volumes don't always mean high ROI, indicating varying profitability across products.
  - Company V's Efficient Promotions: Certain products from Company V show strong ROI, highlighting efficient promotions. In contrast, some items from Companies I and III demonstrate lower ROI, suggesting less effective or costlier promotions.
  - ROI Variability Within Companies: Variability in ROI within a company signifies differing strategic impacts per product. Company V's high ROI products could serve as benchmarks for promotional efficiency.

### 5. Average Sale Based on Promo Type
- **Insights:**
  - Type 1 Promotions: Sharp fluctuations in average sales indicate strong but inconsistent impact, with peaks suggesting significant responsiveness during certain months.
  - Type 2 Promotions: Stable average sales over time suggest a consistent but more modest influence compared to Type 1 promotions.

---

## Conclusion
- **Sales Promotion Impact:** Essential comprehension of how promotions affect volume and profit, critical for budget optimization.
- **Promotional Investment Relationship:** Unveiled correlation between investment and sales upsurge, highlighting Type 1 and Type 2 promotions' effectiveness in peak and regular sales periods.
- **Profitable Promotional Spending:** Identified instances of lucrative promotional investments, drawing insights from Company V's high-ROI strategies.
- **ROI Analysis for Strategy Refinement:** Analyzed ROI variations for strategic enhancements, particularly valuable for refining strategies, such as those of Company III.

---

## Tableau Dashboard View
[Click here to check out Dashboard](https://public.tableau.com/app/profile/ritesh.kumar.singh2841/viz/RetailSalesAnalysis_17122533156900/Dashboard)

---

Feel free to reach out for further details or inquiries.
