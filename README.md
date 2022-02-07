### Mini-Project-1 (Power BI) Overview

This is a _Mini Group Project 1_ which consist of 5 members (Evan, Grace, Michelle, Desmond & Pauline). <br>
Our Team came in Top 2 for this _Mini Group Project 1_ <br>
[Click here to view the badge](https://www.credly.com/badges/6785ca33-25fe-4782-ba36-1c4ee530864d/public_url)

Roles for this Mini-Project-1 <br>
Evan - extract / cleaning up of the raw data, dashboard designing, model relationship mapping <br>
Grace - extract / cleaning up of the raw data <br>
Michelle - anaylzing the clean up data / create/input formula <br>
Desmond - anaylzing the clean up data <br>
Pauline - anaylzing the clean up data / create/input formula / dashboard designing <br>

#### Introduction - Global Automotive Seating Company
- Major supplier of seating systems for automobiles across the world with 200+ seat manufacturing plants in 30+ countries
- 25million cars equipped annually

#### Business Problem
- The automotive seating manufacturing company profits have been declining over time beacause of the steep increase in plants operating costs
- Lack of visibility in theproduction process such as machine downtime, products defect rate, etc. Is leading to ineffective operational process in turn increasing costs

#### Mini Project 1 questions 
1 - Calculate the below listed KPIs(measures_ using DAX <br>
2 - Create charts to track the overall trend of the above calculated metrics over the given time period. Also, create a KPI card highlighting the overall values for each KPIs across the given time period in the data <br>
3 - Create list of filters at t op of the dashboard to filter for the above designed metrics <br>
4 - Is there a correlation between (i) total production and scrap pieces produced, (ii) total production and rework pieces? what is the magnitude of correlation? <br>


#### Mini Project 1 Answers
1 - Calculate the below listed KPIs(measures_ using DAX <br>

Machine Utilization - Formula: (ProductionFBE - ScrapFBE) / ProductionFBE Theoretical <br>
Right First Time - Formula: (ProductionFBE - ScrapFBE - ReworkFBE) / ProductionFBE <br>
Scrap Rate - Formula: (ScrapFBE / ProductionFBE) <br>
Rework Rate - Formula: (ReworkFBE / ProductionFBE) <br>
Downtime Minutes - Formula: Sum of downtime value (in secs) <br>
Production Pieces - Formula: Count of total item produced <br>

2 - Create charts to track the overall trend of the above calculated metrics over the given time period. Also, create a KPI card highlighting the overall values for each KPIs across the given time period in the data <br>

*Refer to the dashboard* 
[Click here to view dashboard](https://github.com/YuriEvan/Mini-Project-1/blob/main/DBA06%20-%20Group%208_Mini%20Assignment%201.pdf)


3 - Create list of filters at t op of the dashboard to filter for the above designed metrics <br>

*Refer to the dashboard*
[Click here to view dashboard](https://github.com/YuriEvan/Mini-Project-1/blob/main/DBA06%20-%20Group%208_Mini%20Assignment%201.pdf)


4 - Is there a correlation between (i) total production and scrap pieces produced, (ii) total production and rework pieces? what is the magnitude of correlation? <br>

*Refer to the dashboard*
[Click here to view dashboard](https://github.com/YuriEvan/Mini-Project-1/blob/main/DBA06%20-%20Group%208_Mini%20Assignment%201.pdf)

5 - Appendix <br>

*Please take note that you may have to download the file to view, as the file is too big to be viewed on GitHub*
[Click here to view data of the dashboard](https://github.com/YuriEvan/Mini-Project-1/blob/main/PowerBI-Data/DBA06%20-%20Group%208_Mini%20Assignment%201.pbix)
