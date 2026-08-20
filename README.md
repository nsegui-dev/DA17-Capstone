Executive Summary
This capstone project will examine housing market trends across selected Middle Tennessee counties, including Williamson, Maury, Davidson, Rutherford, Sumner, and Wilson. The project will analyze how home prices, population growth, building permits, household income, and unemployment relate to housing market growth and development opportunities. The goal is to determine which counties are growing the fastest, what factors appear to drive home price appreciation, and whether new residential construction is keeping pace with demand. This project aligns with the capstone requirement to use multiple datasets, clean and merge data, and answer three to four focused data questions. 

Motivation
I chose this project because the Tennessee housing market is closely connected to both my career and my personal life. I work in the construction industry, partnering with residential home builders throughout Middle Tennessee, where I regularly see how economic conditions, population growth, and housing demand influence development decisions. As demand for new homes continues to change, builders must evaluate where to invest based on market trends rather than intuition alone. As a homeowner, I have also experienced how changes in home values, mortgage rates, and local economic conditions impact long-term financial decisions. Through this project, I hope to use data to better understand the factors driving growth across Middle Tennessee counties and identify which areas present the greatest opportunities for future residential development.

 Data Question
Main question: What economic and demographic factors are most strongly associated with housing market growth across selected Middle Tennessee counties?
 Supporting questions:
 1. Which selected Tennessee counties experienced the strongest home price appreciation from 2020–2025? 
2. How does population growth relate to home price appreciation across these counties?
 3. Are residential building permits keeping pace with population growth and housing demand?
 4. Which counties appear to offer the strongest opportunities for future residential development based on home prices, income, unemployment, population growth, and construction activity? 

Minimum Viable Product (MVP)
The final project will be presented as a Power BI or Tableau dashboard, supported by a short presentation. The intended audience will be residential builders, homeowners, developers, and local stakeholders interested in understanding housing trends in Middle Tennessee. The dashboard will include county-level comparisons, time-series charts, maps, and ranking visuals. Possible visuals include a Tennessee county map, home price trend lines, population growth comparisons, building permits per 1,000 residents, unemployment and income trends. This aligns with the proposal template’s expectation that the MVP describe the final capstone format, visualizations, analysis presentation, and audience. 

Data Sources
U.S. Census Building Permits Survey 
Residential building permit activity https://www.census.gov/construction/bps/

Federal Housing Finance Agency House Price Index 
Home price appreciation and housing market trends 
https://www.fhfa.gov/data/house-price-index 

Census County Population 
Data: Downloadable county population estimates 
County Population Totals and Components of Change: 2020-2025

BLS Local Area Unemployment Statistics 
County unemployment rates 
https://www.bls.gov/lau/ 

Known Issues and Challenges
A major challenge will be merging datasets from different sources because they may use different county names, FIPS codes, date formats, and time periods. Some datasets may be monthly while others are annual, so I will need to aggregate or align the data by year. Another challenge may be missing values for certain counties or years. To manage this, I will document all cleaning steps, use consistent county identifiers, create calculated fields such as home price growth percentage and permits per 1,000 residents, and clearly explain any limitations in the final presentation. The proposal template specifically asks for known data-cleaning steps and anticipated project challenges, so this section will help show upfront planning. 

Python will be used to gather the data from all sources, merge it all into a usable data frame, clean the data as needed, and standardize variables such as FIPS codes, addresses, county names, and zip codes.  Once this data has been cleaned and analyzed using Python, it will be transferred over to a visualization using either Power BI or Tableau to create an appealing presentation that will make the information more easily digestible to the intended audience.
