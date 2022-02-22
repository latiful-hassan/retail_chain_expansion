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
- Blended the two data sets

**Analysis & Insights**

-
