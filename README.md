## An Analysis of Kickstarter Campaigns
Performing analysis on Kickstarter data to uncover trends

## Overview of Project
#### An up-and-coming playwright wants to start a crowdfunding page to fund her play. She’s estimating a budget of over $10,000+ and wants to know the specific factors that make a campaign successful. This analysis aims to build a greater understanding of crowdfunding campaigns from start to finish and mirror other successful plays. I plan to explain how different campaigns fared in relation to their launch dates as well as their funding goals to provide the up-and-coming playwright with insights into 

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

#### To determine the Analysis of Outcomes Based on Launch Date, I created a pivot table with the “Category” and “Years” filters. I also sorted the appropriate fields in the columns, rows, and values section and filtered the columns to show “Successful,” “Failed,” and “Canceled.” I filtered the category to “Theater” and created the below line chart to visualize the relationship between outcomes and launch month.

![]()

### Analysis of Outcomes Based on Goals

#### To analyze the outcomes based on goals, I created a new excel sheet with the goal amounts, number of successful, failed, canceled, and total projects. I also determined the percentage of successful, failed, and canceled projects. I used the COUNTIF() function to populate the number of successful, failed and canceled campaigns by filtering with the “outcome,” goal amount, and the subcategory “plays” as the criteria. I used the SUM() function to populate the total projects and was able to determine the percentage of successful, failed, and canceled projects. The following line chart shows the goal amount ranges and the percentage of successful, failed and canceled campaigns.

![]()

### Challenges and Difficulties Encountered

#### Small changes to the filters or functions can have a signficant impact on the total numbers calculated, resulting in inaccurate results. For example:
##### - In the Theater Outcomes by Launch Date section, I had an extra column (live) and thought I may have incorrectly filtered the initial data. I then noticed I could further filter my pivot table and was successfully able to hide the live data.
##### - In the Outcomes based on Goals problem set, I had added ‘US’ as a part of the COUNTIFS function, which was not a required element and resulted in inaccurate project numbers and percentages. Removing ‘US’ from the function resolved the issue. 

## Results

#### What are two conclusions you can draw about the Outcomes based on Launch Date?

##### - One conclusion drawn from the data is that the most successful campaigns were launched in May (111), closely followed by June (100) and July (87).
##### - A second conclusion drawn from the data is that failed campaigns were also most likely to occur in May, however the range of months for failed campaigns was significantly smaller throughout the year (31-52).

#### What can you conclude about the Outcomes based on Goals?

##### - The most successful campaigns had a fundraising goal of $1,000 or less, with an approximately 76% success rate. Campaigns under $14999 were also more likely to succeed than fail, but with a much narrower success rate (54%). Surprisingly, campaigns between $35000 and $44999 were also more likely to succeed than fail with a 67% success rate, but the total number of projects in these two categories was far smaller than the total projects in the $9999 and under categories.

#### What are some limitations of this dataset?

##### - Additional data could provide more detailed insights into the most effective crowd sourcing campaigns. For example, if we had data regarding the subcategories for play types (e.g., genres) we may be able to better distinguish characteristics of the most successful campaigns.

#### What are some other possible tables and/or graphs that we could create?

##### - It might be helpful to look at the source of funding for possible tables and graphs. We have information on the number of donors and the average donations, but we have yet to examine if there is a correlation between these variable and successful, failed, or canceled campaigns. 

##### - I think we could also take a closer look at the deadline of goals and the percentage of funding raised. Were there any patterns regarding the funding timeline for campaigns that met their goals?



