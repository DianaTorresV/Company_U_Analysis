



--------------------
# Project Unicorn
### Project Overview
This project investigates the low profitability of a fictitious company’s Central Region. By analyzing profit ratios across regions, states, and product categories, the project identifies underperforming areas and proposes strategies to improve profitability. It was developed as a practical exercise in data analysis using PostgresSQL, spreadsheets, and Tableau.

#### Motivation and Context

This project was conceived as a practical exercise to explore data analysis tools within the context of a fictitious company. Its primary goal was to conduct a rapid and straightforward dataset analysis to identify potential business improvements, even without extensive knowledge of the company’s operations. By focusing on profitability issues in a specific region, the project uncovers actionable insights and proposes targeted recommendations to address the root causes of low profitability in the Central Region. Serving as an introductory framework, this project provides a replicable approach for businesses or analysts to identify and resolve profitability challenges effectively.

#### Technologies Used

* _PostgresSQL_: Chosen for querying and analyzing large datasets due to its efficiency and flexibility in handling relational data.

* _Spreadsheets_: Used for detailed calculations, pivot tables, and visualization of specific metrics at a granular level.

* _Tableau_: Selected for creating interactive dashboards to visualize key metrics and share insights in an accessible format.

### Methodology
The process follows a hierarchical approach to pinpoint the root causes of profitability issues. By drilling down from region to state, then to category and product level, it ensures that recommendations are specific and actionable.

_Data Exploration_

* Initial queries and visualization of regional profit ratios to identify the weakest-performing region.

* Detailed analysis of sales, profit, and profit ratios across all regions.

_State-Level Analysis_

* Focus on Texas and Illinois, identified as the key contributors to low profitability in the Central Region.

* Examination of profit and loss patterns by product categories within these states.

_Category and Product Analysis_

* Review of major product categories such as Furniture and Office Supplies.

* Identification of underperforming products, particularly those with persistently negative profit ratios even without discounting.

_Strategy Development_

* Drafted actionable recommendations based on findings, focusing on discontinuation of unprofitable products and optimization of discounting practices.

### Key Findings

* _State-Level Insights_: Texas and Illinois drive Central Region losses, with negative profit ratios across several categories.

* _Category-Level Drivers_: Office Supplies and Furniture categories showed persistent losses, driven by excessive discounting.

* _Product-Level Analysis_: Identified 52 underperforming products in Office Supplies as strong discontinuation candidates.

* _Impact of Discounting_: Heavy discounting significantly reduced profitability, particularly in certain sub-categories.

### Recommendations
* _Discontinue unprofitable products_: In the Office Supplies category, discontinue the 52 products that have a persistently negative profit ratio, even when no discounts are applied, and that have sales of less than $2,000 over the analysis period. These products are strong candidates for discontinuation because they show limited market demand.

  Apply the same product-level analysis to the Furniture category to identify all products with low sales and persistently negative profit ratios, even when discounts are removed. These should also be considered for discontinuation.

* _Optimise and target discount adjustments_: Re-evaluate and optimise heavily discounted Office Supplies and heavily discounted Furniture subcategories, in particular Furnishing. Focus on selectively reducing or eliminating discounts on products that demonstrate potential profitability without discounting. Priority should be given to categories or sub-categories where small adjustments could yield significant profit improvements.

* _Clarify the source of discounting_: Determine whether current discounting practices are market driven or internally driven by sales targets that may be damaging the business. Reviewing internal sales policies and aligning them with profitability targets is essential to ensure sustainable performance.

* _Continuous monitoring_: Implementation of dashboards to continuously track profit ratios, sales performance and the impact of rebates at product level. This will enable the company to proactively identify and address underperforming products before they have an impact on the overall profitability of the business.
  
### Conclusion

In order to restore profitability in the Central Zone, it is essential to eliminate deep discounting and discontinue underperforming products. By targeting those sub-categories and products with persistently negative profit margins and low sales volumes, the company will be able to reduce its losses and improve its performance. Optimisation of the discount strategy, particularly in furniture and office supplies, will be key to the return to profitability. To ensure that future profitability challenges can be quickly identified and addressed, a data-driven continuous monitoring system should be implemented.

#### Challenges and Limitations

* _Time Constraints_: Limited to one week of analysis, restricting deeper dives into some aspects of the data.

* _Fictitious Data_: Context and assumptions are based solely on the dataset without real-world validation.

* _Complexity of Discount Analysis_: Challenges in isolating the exact impact of discounting practices due to overlapping factors.


#### References

* SQL Queries:
  
  https://colab.research.google.com/drive/1BtzHB0649UzFd8pGfxqWOssTfcXWJ3L5?usp=sharing
* Spreadsheet Analysis:
  
  https://docs.google.com/spreadsheets/d/1t2Th2hqrbr0LfBoY63BFFdnzPH4CiR9JTuq6VzqFwac/edit?gid=1131846199#gid=1131846199
* Slides:
  
  https://docs.google.com/presentation/d/1hDdZUHvMmpCBGz6T6ISRlxW5HK_6FVJL/edit?usp=sharing&ouid=107263931505166667487&rtpof=true&sd=true
* Tableau:
  
  https://public.tableau.com/views/UnicornProject-Masterschool/Dashboard1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link


#### Project Team
* Diana Torres
* Marcella Valente
* Victoria Cobbah

---


