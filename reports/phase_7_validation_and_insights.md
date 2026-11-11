# Phase 7: Validation, Insights, and Business Recommendations

## 1. Project Overview

This project analyzes retail sales, product profitability, customer behavior, store performance, and geographic performance using the Global Electronics Retailer dataset.

Python was used for data cleaning, exploratory data analysis, and KPI calculations, while Tableau was used to develop interactive dashboards.

## 2. Validation Methodology

Python calculations were compared with Tableau dashboard results using consistent filters, date ranges, and metric definitions.

Validation covered:

- Total revenue, gross profit, and gross margin
- Distinct orders and units sold
- Average order value
- Revenue by month, category, product, store, and customer

The headline KPIs were confirmed to be consistent between Python and Tableau.

## 3. Key Findings

### Revenue Growth and Decline

- **Observation:** Revenue increased through 2019, followed by a substantial decline in 2020.
- **Evidence:** Revenue increased from $6.95M in 2016 to $18.26M in 2019, then declined to $9.29M in 2020. December 2019 recorded the highest monthly revenue of $2.48M.

### Leading Product Categories and Brands

- **Observation:** Computers is the highest-revenue category, and Adventure Works is the leading brand.
- **Evidence:** Computers generated $19.30M in revenue, while Adventure Works generated $11.85M.

### Product Profitability

- **Observation:** Product 444 is the highest gross-profit contributor among the displayed products, while several desktop PC products have relatively low gross margins.
- **Evidence:** Product 444 generated $337,986 in gross profit. Identified lower-margin products have approximately 49.02% gross margins, compared with the overall gross margin of approximately 58.58%.

### Geographic and Store Performance

- **Observation:** The United States is the leading geographic market, and the online channel is a major revenue contributor.
- **Evidence:** The United States generated $23.76M in revenue. Online generated $11.40M in revenue and $6.67M in gross profit. Store 55 was the highest-performing physical store among those displayed, with $1.42M revenue and $830,551.75 gross profit.

### Customer Revenue Concentration

- **Observation:** A relatively small group of active customers contributes a substantial share of revenue.
- **Evidence:** The top 10% of active customers contributed 35.98% of revenue, while the top 100 customers contributed 5.53%. Of 15,266 customer records, 11,887 customers had recorded sales.

## 4. Business Recommendations

- **Understand the 2020 revenue decline:** Revenue fell from $18.26M in 2019 to $9.29M in 2020. The COVID-19 pandemic may have contributed to this decline by affecting customer demand and store operations, although the available data cannot confirm the exact cause. Reviewing monthly trends, regions, and sales channels can help identify where the largest changes occurred.
- **Improve product profitability:** Review the pricing and cost structures of products with gross margins of approximately 49.02%, compared with the overall margin of 58.58%. These products may benefit from revised pricing, supplier negotiations, or more focused promotions.
- **Build on the strongest segments:** Continue investing in Computers, Adventure Works, and the United States, which generated $19.30M, $11.85M, and $23.76M in revenue, respectively. Their performance should be evaluated using revenue, gross profit, and gross margin rather than revenue alone.
- **Balance online and physical-store sales:** Analyze the online channel separately from physical stores, since online sales generated $11.40M in revenue. Store comparisons should also take operating costs, store size, and local demand into account.
- **Strengthen customer retention:** Since the top 10% of active customers generated 35.98% of revenue, targeted loyalty offers and personalized follow-up could help retain these high-value customers while broadening the wider customer base.

## 5. Limitations and Assumptions

- **Listed prices versus actual sales:** Revenue uses listed USD unit prices and quantities. Discounts, refunds, returns, and taxes may not be represented.
- **Gross profit versus net profit:** Gross profit subtracts product costs only and excludes other operating expenses.
- **Missing delivery dates:** Missing delivery dates affect Online Store records (StoreKey 0), limiting online delivery-time analysis. Physical store delivery dates are present.
- **Partial final year:** The 2021 dataset ends in February and is not directly comparable with complete years.
- **Store performance:** Revenue differences do not necessarily indicate store efficiency because operating costs, store size, and foot traffic are not fully available.
- **Dimension records without sales:** Some customer and store records do not appear in the Sales table during the observed period. These records were retained; their absence indicates no recorded sales in the available data.
- **Currency assumptions:** Core metrics use listed USD product prices and costs. Transaction-currency conversion requires validated exchange-rate direction and business definitions.

## 6. Conclusion

Overall, the business performed strongly through 2019 before experiencing a significant revenue decline in 2020. The COVID-19 pandemic may have played a role by affecting customer demand and store operations, but the available data does not provide enough evidence to confirm it as the sole cause. Computers, Adventure Works, the United States, and the online channel remain important sources of revenue and should continue to receive focused attention.

The analysis also highlights opportunities to improve margins on lower-performing products and strengthen relationships with high-value customers. By tracking changes in revenue, profitability, sales channels, and customer behavior, the business can make better-informed decisions and respond more effectively to future market disruptions. These conclusions should be considered alongside the limitations of the available data.
