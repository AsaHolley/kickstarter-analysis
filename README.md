# Kickstarting with Excel

## Overview of Project
This project utilizes data from Kickstarter campaigns across the world that looks into types, size, dates, and success rates of various campaigns. For this particular project we are looking at theater plays Kickstarters. 
### Purpose
The purpose of this project is gain insights into how different theater paly campaigns fared in relation to their launch dates and their fundraising goals. 
## Analysis and Challenges
To perform this analysis the provided kickstart data a pivot table was created with the data filtered by the theater category. The data was grouped by outcome (failed, successful, and live) in columns and by month in rows. The following chart is the result of the pivot table analysis. 

Analysis of Outcomes Based on Launch Date [kickstarter-analysis](https://github.com/AsaHolley/kickstarter-analysis/blob/main/Outcomes_vs_Goals.png) 

A second analysis was conducted using tables built on COUNTIFS forumlas to group successful, failed, and canceled plays in columns by their funding goals divided into 12 different traunches (from >$1,000 to <$50,000). The following chart is the result of the analysis

Analysis of Outcomes vs. initial Fundraising Goals
[kickstarter-analysis](https://github.com/AsaHolley/kickstarter-analysis/blob/main/Theater_Outcomes_vs_Launch.png) 


### Challenges and Difficulties Encountered
This particualr analysis did not present any specific challenges or difficulties due largely to the fact the data set did not require a significant amount of cleaning or formatting changes. A possible challenge could be deciding what is an outlier because of how much the funding and fundraising goals vary. Another issue is that to do more complex analysis on Kickstarter campaigns this data set may not be sufficient and more detailed data could be needed. 

## Results

**What are two conclusions you can draw about the Outcomes based on Launch Date?**
A first conclusion that can be drawn from outcomes based on launch date is that the success rate of campaigns is the highest in the spring and summer, and in particular, the moths of May and June. A second conclusion is that October in a particularly bad month for Kickstarter campaigns as there is a spike in failures. The overall the failure rate, however, is significantly smaller than the success rate for plays throughout the year. 

**What can you conclude about the Outcomes based on Goals?**
The biggest conclusion that can be made on the outcomes based on goal analysis is that those Kickstarter’s that utilize a smaller initial goal are on average more successful than those with lofty goals. Although the trend starts to reversion around the $35,000 to $45,000 mark. There may be a number of factors that contribute to this phenomenon and more research is warranted. 
 
 **What are some limitations of this dataset?**
The data set does not take into many external factors that make a campaign effective. In particualr there is no information on marketing efforts of individual campaigns that could have major impact on their success and funds raised. There is no information on the exact cities within countries where the campaigns where located, which would make a huge difference in who generous patrons are. 

**What are some other possible tables and/or graphs that we could create?**
Campaign launch date in relation to fundraising goals could be an interesting analysis. Also, country of original vs. success rate and time of the year could result in new insights. Looking at the types of theater productions that yielded the most donations could be a simple and effective analysis.
