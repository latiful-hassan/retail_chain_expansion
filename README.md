# retail_chain_expansion
**Context**
- An Austrailian retail chain operating in the *'Clothing Retailing'* is current running in New South Wales
- The Board of Directors is considering an expansion into one of the following states
  * Queenslands
  * Victoria
  * Western Austrailia

**Task**
- Assess the business environments for the industry in question in each of the three states and present the findings

**Techniques & Process**

- First I pivot the data in *competitor_research* for a more machine friendly format:

![](https://github.com/latiful-hassan/retail_chain_expansion/blob/main/retail_chain_expansion_screenshots/pivot_competitor_research.png)

- I then created a box-plot on *'Net Profit Margin'* against *'State'*:

![](https://github.com/latiful-hassan/retail_chain_expansion/blob/main/retail_chain_expansion_screenshots/box_plot.png)

- Cleaned *retail_turnover_by_state_and_subgroup_raw* 
- Added a **Data Source Filter** for 2010 before pivoting and splitting the data to reduce processing time (will un-do before analysis)
- After removing the previous data source filter, I added one that filters for only *'Clothing Retailing'*
- Added another data source filter for dates (2000 onwards)
- Filtered for the states in question
- Created a graph showing the *'Turnover'* by *'State'*:

![](https://github.com/latiful-hassan/retail_chain_expansion/blob/main/retail_chain_expansion_screenshots/industry_analysis.png)

- Cleaned *austrailian_demographics_raw* in Excel
- Split and pivoted the data in Tableau
- Added a data course filter for *'Persons'* as we are assuming shopping habits are equal for men and women for this investigation
- Blended the two data sets on Year and Quarter
- Added a data source filter for March
- Created a calculated field to work out *'Sales per Capita'*: <br/>
 SUM([Turnover $M])/SUM([Data1 (austrailian_demographics_cleaned)].[Population]) * 100000000

![](https://github.com/latiful-hassan/retail_chain_expansion/blob/main/retail_chain_expansion_screenshots/sales_per_capita.png)

- Added **Forecast** for 3 years, ignoring 0 values:

![](https://github.com/latiful-hassan/retail_chain_expansion/blob/main/retail_chain_expansion_screenshots/sales_per_capita_forecasted.png)

**Report**

- The report is in **Story** form, please see *retail_chain_expansion_report*

**Analysis & Insights**

- Taking a glance at the box-plot on Competitor Research, we see that Victoria has tighter variance and a higher upper range than both Queensland and Western Austrailia despite Net Profit Margins being similar
- The Industry Analysis shows up-ward trend in all regions, however, this is not taking into account the population
- The Sales per Capita graph confirms that there is growth only in the existing New South Wales region as well as Victoria
- In conclusion, Victoria is reccomended as an expansion opportunity as there is greater potential for future growth
