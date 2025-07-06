# Tackling Returns: Insights for Reducing Superstore Order Returns 

## Overview 
The purpose was to prepare an analysis for the CEO to help them understand what is causing customers to return their orders and how to reduce the volume of returned orders. The project uncovered what's driving customer returns and how to reduce the return rate to protect profits.

![Returns Dashboard](https://github.com/Parkerjcow/Data_projects_Tripleten/blob/Tackling-Returns-Insights-for-Reducing-Superstore-Order-Returns/Evaluating%20Returns.png?raw=true)

**Data**
- The data was one Excel spreadsheet file:
  - 'Superstore.xls': each row corresponds to one product sold; sheets were LEFT JOIN'd
  - 'orders': details all fields for each ordered item
  - 'returns': details all fields for each returned item

## Key Insights
1. Returns Are the Primary Driver of Profit Loss
   - Returned purchases represent a significant drag on profitability.
   - Negative profits correlate directly with higher return volumes.

2. High Return Rates in Technology Category
   - The Technology category recorded the highest return rate among all departments.
   - Suggests a need for quality control or clearer product expectations in this category.

3. Repeat Returners
   - Several individual customers had a 100% return rate, pointing to possible abuse or poor product/customer alignment.

4. Geographic Variation
   - Return rates varied by state and sub-category, indicating that regional product preferences or service expectations may play a role.

5. Seasonal Patterns
   - Certain months exhibited higher return volumes, highlighting a potential for seasonal return trends.

6. Low-Selling Products Still Returned
   - Some of the lowest-selling products had a 100% return rate, suggesting inventory or product relevance issues.

## Analytical Process
- Combined orders and returns tables using a LEFT JOIN.
- Created interactive dashboards and visuals in Tableau to explore trends by:
   - Product category
   - Region
   - Time period
   - Customer-level return behavior

- Built a 9-page Tableau Story to communicate findings and recommendations to stakeholders.

# Recommendations
- Investigate the Technology category for fulfillment, quality, or misalignment issues.
- Identify and monitor high-return customers to apply stricter pre-screening.
- Optimize seasonal inventory and marketing strategies during high-return periods.
- Consider regional feedback to better align product offerings with customer expectations.


