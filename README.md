# Hospital HCAHPS Scores

Capstone Project for Daytime Data Analytics Cohort 16 program at NAshville Software School

## Table of Contents
    *[Canva Presentation]
    *[Motivation]
    *[Questions]
    *[Normalizing the Data]
    *[Problems and Hurdles]
    *[Technologies Used]
    *[Data Sources]
    *[Conclusions]

## Canva Presentation
    Link: https://www.canva.com/design/DAGwEwt0H3s/y0_fZp9SoHZDNLUhnf9-7A/view?utm_content=DAGwEwt0H3s&utm_campaign=designshare&utm_medium=link2&utm_source=uniquelinks&utlId=h1b26768a73


## Motivation
With 20 years of experience in healthcare as a nurse, I witnessed firsthand the significant challenges hospitals faced during the COVID-19 pandemic. These included a sharp increase in patient volume, extended working hours for nursing staff, and a shift toward triage-based medical management.

Motivated by these experiences, I conducted research to examine whether HCAHPS scores in Tennessee hospitals declined, improved, or remained stable during the pandemic. I also explored whether the state's population growth and the simultaneous decrease in nursing workforce numbers had a measurable impact on these scores. My analysis focused exclusively on Tennessee hospitals, using data from 2017 to 2024, including HCAHPS scores, population trends, and labor statistics.

## Questions 
1) Did HCAHPS scores rise, decline, or remain consistent during the COVID-19 pandemic?
2) Which specific HCAHPS categories were most affected during the pandemic?
3) Did population growth and a decrease in nursing staff impact HCAHPS scores in Tennessee?

## Normalizing the Data 
I utilized data from 2017 to 2024 to develop multiple DataFrames representing HCAHPS scores across various categories for all hospitals in Tennessee. I also analyzed population growth trends within the state during the same period. Workforce data was filtered to isolate registered nurses (RNs), licensed practical nurses (LPNs), orderlies, and technicians employed specifically in hospital settings.

## Problems and Hurdles
To qualify for an HCAHPS star rating, hospitals must receive a minimum number of returned patient surveys during the reporting period. Several hospitals did not meet this threshold and were excluded from the analysis. Only hospitals with valid star ratings were included, and their scores were averaged to calculate the statewide HCAHPS category averages for Tennessee.

## Technologies Used
1) Python / Pandas - Used for exploratory data analysis, data cleaning, and visualizations

2) Power BI - Used to build interactive dashboards and present findings

3) Canva - Used for creating the final project presentation

## Data Sources
1) Center for Medicare and Medicaid Services 
    https://data.cms.gov/provider-data/archived-data/hospitals#2018-annual-files
2) U.S. Bureau of Labor Statistics - OEWS data tables
    https://www.bls.gov/oes/current/oes_research_estimates.htm
3) U.S. Department of Census 
    https://data.census.gov/table

## Conclusion
The analysis revealed that HCAHPS scores were already trending downward prior to the COVID-19 pandemic. However, the pandemic accelerated this decline across multiple categories, followed by a partial recovery in later years. Additionally, the data showed a correlation between a reduction in nurses per capita and lower HCAHPS scores, suggesting that staffing shortages may have negatively impacted patient experiences in Tennessee hospitals.



