# Kickstarting with Excel

## Overview of Project

### The purpose of this analysis is to explore the relationships between launch dates and funding goals for the Theater category on the Kickstarter platform. This should help inform future project owners understand if the best time to launch their campaign. The analysis of goal amounts could help indicate what funding goal appeals to future backers in the Play category.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
The chart below looks at the outcomes of projects in the Theater parent category base on the month that the project launched.
![Graph of Theater Outcomes vs Launch](../main/resources/Theater_Outcomes_vs_Launch.png)
The chart indicates that May has the highest number of successful theater campaigns. This number decreases into the fall where October shows a slight increase but then things continue downward through the end of the year. This data shows that there is a large appetite for donors during summer months but it is less so in other seasons. If a theater project wanted to avoid being lost in the crowd, they may decide to avoid the busy summertimes. This may be a strategy, but they would need to research into further reasons why there are less projects in total during the winter months.

### Analysis of Outcomes Based on Goals
The chart below show the percentage of successful, failed, and canceled project for the Plays subcatagory.
![Charge of Outcomes Based on Goal](../main/resources/Outcomes_vs_Goals.png)
This indicates that projects with a low funding goal have a high success rate of funding but it quickly decreases until bottoming out at the $25K-$29K range. These projects in the $25k-$29K range are succesful only 20% of the time. Project with funding of under $15K and between $35K and $45K have over a 50% success rate. If I were to launch a campaign, I would either want to have a shoe string budget to capture those donors interested in the cheaper productions. Otherwise a modest budget of $35k to $45K would also have a high liklihood of funding. If the funding goal is over $45K there is a low chance that the project would be successful.

### Challenges and Difficulties Encountered
As I was creating the charts, I ran into a small problem when I noticed that my total count of projects did not match the sum of successful, failed, and canceled project. I had to dig into the data and used the filter capability in Excel to filter down to the items that I was trying to count with my COUNTIFS function. This is when I noticed that there was an outcome that I hadn't accounted for. The unexpected outcome were projects that were live when the data extract was taken. After updating the filters my counts matched so I was able to continue with my analysis.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
If someone wanted to have the best chances of successful funding their Theater campaign, they would want to launch in May. December has a near 50/50 split of successful and failed campaigns. This may mean that people running the campaigns are not interested in spending their holidays running a crowdfunding campaign.

- What can you conclude about the Outcomes based on Goals?
The funding goal appears to have a impact on the success rate. There appears to be a trough of success that bottoms out in the range of $25,000 to $29,999. I would concluded that donors are more willing to donate to plays that have a budget of $35,000 to $45,000. If the budget is lower, donors are less likely to support the play.


- What are some limitations of this dataset?
The dataset doesn't include any data on the users of Kickstarter. This may be helpfu in understanding the reasons why a person did or did not donate to a project. Other demographic information may help tell the store of what type of project a specific age, gener, metro area would support specific projects.

- What are some other possible tables and/or graphs that we could create?
I would be interested in investigating if the length of the campaign had any impact on the campaign outcomes. I would also be interested to see if more recent projects have a higher success rate. This may indicate that Kickstarter has become more trusted over the last couple of years.
