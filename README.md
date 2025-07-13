**Overview**
This Power BI dashboard analyzes a marketing campaign dataset from Kaggle. It covers insights across products, channels, demographics, and campaign performance to understand customer behavior, channel effectiveness, and campaign response.

**Dashboard Visuals & Insights**
**Customer Responses Over Time**
* Visual: Line Chart
* Purpose: To observe how customer responses evolved over time based on Dt_Customer.
* Insight: Peaks indicate stronger engagement or campaign rollouts.

**2. % by Purchase Channel**
* Visual: Donut Chart
* Purpose: Shows distribution of purchases made through Web, Store, Catalog, Deal, etc.
* Insight: Web and Store purchases dominate, indicating preferred customer touchpoints.

**3. Store vs Web Purchases**
* Visual: Bar Chart
* Purpose: Compare online vs offline behavior.
* Insight: High web purchases highlight the importance of online shopping experience.

**4. Education vs Customer Count**
* Visual: Bar Chart
* Purpose: Distribution of customers across education levels.
* Insight: Majority hold Graduation and Master's degrees.

**5. Age Group Distribution**
* Visual: Bar Chart (Age binned into groups)
* Purpose: Helps segment users by life stage.
* Insight: Customers aged 30–45 form the largest group.

**6. Spending Breakdown by Product and Education**
* Visual: Stacked Column Chart
* Purpose: Correlate spending behavior with education level.
* Insight: Higher education levels spend more on luxury (Wines, Gold).

**7. Total Spend per Product**
* Visual: Bar Chart
* Purpose: Identify high revenue-generating products.
* Insight: Wines and Meat dominate product-wise sales.

**8. Campaign Acceptance by Income**
* Visual: Bar Chart
* Purpose: Relationship between income and campaign success.
* Insight: Higher-income groups are more responsive.

**9. Campaign-wise Customer Acceptance**
* Visual: Bar Chart
* Purpose: Show number of acceptances per campaign.
* Insight: Campaign 4 had the highest engagement.

**10. Overall Campaign Response**
* Visual: Donut Chart
* Purpose: Displays Response column (1 = Yes, 0 = No)
* Insight: Response rate ~15%, scope for improvement.

**11. 34M Card (Total Amount Spent)**
* Visual: KPI Card
* Purpose: Shows total spend across all customers.

**12. Customer Distribution by Marital Status**
* Visual: Donut Chart
* Purpose: Understand relationship status demographics.
* Insight: Majority customers are married or living together.

**Data Transformations Done**
* Calculated Column: Age from Year_Birth
* Unpivoted: Product columns and Purchase Channel columns
* Grouped: Age into bins (e.g. 18–25, 26–35)
* New Measure: Amount_Spent as total of all Mnt* columns
* Renamed Columns: For readability (e.g. NumWebPurchases → WebPurchase)

**Suggestions & Business Insights**
* Invest in Campaign 4: It shows highest customer acceptance.
* Target Graduates aged 30–45: They form the largest spend group.
* Enhance online experience: Web Purchases dominate; UX investments will pay off.
* Introduce targeted loyalty program: High income segments respond more.

