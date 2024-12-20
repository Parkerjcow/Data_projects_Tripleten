# Manhattan Vacation Rental Market 

This was an independent project designed to showcase what I have learned about Advanced Spreadsheets. This project analyzes Airbnb listings in Manhattan, NYC to help a client decide what type of vacation rental property to invest in.

**Description:**

8 page spreadsheet
Includes organizational tabs, raw data (Hidden), processed data, data analysis, pivot tables, and bar charts.

## Process:

- Data Preparation: Filtering techniques were used to identify and clean inconsistencies within the Airbnb data. Irrelevant columns were hidden to maintain a focused analysis. Key functions such as PROPER, TRIM, IF, ISNUMBER, FIND, ROUND, SUMIF, VLOOKUP, CHOOSE, and WEEKDAY were employed for data tidying.
- Neighborhood Analysis: Identify the top-performing neighborhoods based on review frequency via Pivot Table.
- Property Size Analysis: Determine the optimal property sizes for each neighborhoodvia Pivot Table showcased with conditional formatting.
- Revenue Analysis: Calculate estimated annual revenue for the most attractive listings.
- Additional Optional Analysis: Perform Analysis through Pivot Tables for occupancy rates by day, price by super host status, check-in ratings by use of doormen, and price by review ratings.
- Data Visualization: Create clear and informative visualizations (charts) to present findings.
- Formatting and Organization: Ensure your analysis is well-formatted for ease of readability.
- Documentation: Create organizational sheets like an executive summary, table of contents, assumptions log, and change log.
Data

## The data was one Google spreadsheet file provided by TripleTen, Copy can be found [HERE](https://docs.google.com/spreadsheets/d/1WDoB2zXPS-7MgIK0kv7MgObjQP7JtJ-4YFrD4LkzLtM/edit?gid=1647054102#gid=1647054102):

- 'nyc_airbnb_data.csv': each row corresponds to one listing on Airbnb in September 2022
  - 'data_dictionary': summary of field titles seen in the file and its data type
  - 'listings': uniquely listings available with all available data
  - 'calendar': listings with upcoming availabilities and date-type data
  
Assumptions:

- Airbnb rentals are equivalent to the general short-term vacation rental market. 
- Only properties with a Minimum night requirement of 7 days or less were considered. 
- Properties with no reviews in the last 12 months were considered inactive. 
- Reviews reflect rental frequency, we used "number_of_reviews_ltm" to measure a listing's attractiveness. 
- Super luxury listings with prices greater than $1,321.21 were filtered from the analysis, 1% outlier. 
- Extremely low-priced listings of less than $85.28 were filtered from the analysis, 1% outlier. 
- Estimated Annual Revenue can be calculated by comparing averages for top listings. 
-"Building staff" equates to a Doorman -A listing of 9k can be excluded when examining price/review due to it being an extreme outlier.

**Findings and Recommendations:**

- The top recommended neighborhoods for vacation rentals are as follows: Lower East Side, Hell's Kitchen, Harlem, Midtown, Upper West Side, Chelsea, East Village, East Harlem, West Village, Upper East Side.
- The top rental size is 1 bedroom overall. Lower East Side properties should have 1-bedrooms to meet demand. Hell's Kitchen prefers 2 bedrooms and Midtown prefers Studio.
- The estimated annual revenue based on top listing characteristics is $69,957.
- Fridays have the highest occupancy rate out of the week, average occupancy is 86.4%.
- Instant bookings do have higher occupancy rates, statistically significant, average is 52%.
- Superhosts can charge higher prices, statistically significant, on average $334.
- Building with doormen gets better reviews, statistically significant, by 0.05 stars.
- Hosts can charge higher prices for higher review ratings.
