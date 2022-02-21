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

- Cleaned *retail_turnover_by_state_and_subgroup_raw* by removing unnecessary data
- Added a **Data Source Filter** for 2010 before pivoting and splitting the data to reduce processing time (will un-do before analysis)
- After removing the previous data source filter, I added one that filters for only *'Clothing Retailing'* as that is the subject of this analysis and another that filters the dates so we are working with data from 2000 onwards
- Created a graph showing the *'Turnover'* by *'State'*:

![](https://github.com/latiful-hassan/retail_chain_expansion/blob/main/retail_chain_expansion_screenshots/industry_analysis.png)

-

**Analysis & Insights**

-
