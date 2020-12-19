# Kickstarting with Excel

## Overview of Project

### Purpose

#### The purpose of this analysis is to help Louise determine the best conditions for her Kickstarter. We want to help her determine the most appropriate goal and the start month so that she can have a successful outcome. Currently, Louise is estimating her Kickstarer goal to be over $10,000; with the gathered data and our analysis, we will determine if her goal is achievable or not.

## Analysis and Challenges

### For our analysis, we created two different Tables. One contains the Launch Dates and Outcomes data and the other contains Goals and  Outcomes data. From each Table, we created two Line Charts, Theater_Outcomes_vs_Launch that displays the effects of Launch Date and Outcomes_vs_Goals which displays the effects of Goal amount. (Both charts can be found in the Resources folder). Each Line Chart visualizes the Goal range and the Launch Month for the Successful, Failed, and Canceled Kickstarters. 


### Analysis of Outcomes Based on Launch Date

#### Based on the Theater_Outcomes_vs_Launch Line Chart, the Kickstarters with the most Successful outcomes were launched in the months of  May, June, and July. May produced both the most successful and failed Kickstarters. November had the least failed Kicksarters, but produced less than half Successful Kickstarters compared to May. Though October had 0 Canceled Kickstaeters, it was only the 8th month to produce the most Successful outcomes. A piece of information that could be beneficial to add to the Outcomes Based on Launch Date sheet is the percentage of Successful, Failed, and Canceled Kickstarters for each month. This would help us quickly understand that although May produced the most Failed outcomes, it was still the most successful month over all.

### Analysis of Outcomes Based on Goals 

#### From our Outcomes_vs_Goals Line Chart we can see that there is a downward Success trend from goals that are less than $1,000 to goals that are in the $25000 - $29,000 range. There is a slight upward trend for goals ranging $30,000 - $39,000; however the most successful Kickstarters had a goal of Less Than $1,000. Additionally, there is only a 3% change between the most successful goal range (Less Than $1000) and the 2nd most successful goal range ($1,000 - $4,999). The goal range of  $45,000 - $49,000 had both the highest rate of Failed outcomes and the lowest rate of Successful ones.

### Challenges and Difficulties Encountered

#### One of the major challenges encountered was dealing with the date data. Initially, when the data was downloaded the dates were all Unix time stamps which are difficult to understand. This data had to be converted to MM/DD/YY format with a formula I was unfamiliar with. 

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

Louise should Launch her Kickstarter on the months of May, June, or July, with May having the most successful outcomes. 

Louise should avoid launching her Kickstarter in the month of December as it produced the least amount of successful outcomes.


- What can you conclude about the Outcomes based on Goals?

Louise's goal range should be between $5000 and $9999

The lower the outcome, the most likely it is to have a Successful outcome. However, there is only a 3% change between the most successful range (Less than $1,000) and the 2nd most successful range ($1,000 to $4,999); therefore, the 2nd most successful range should be highly considered. 
 
- What are some limitations of this dataset?

This data came all from one website, it is possible that other websites hosted only or more Kickstarters with a similar goal range to Louise's, $10000; therefore, they would provide us with more relavent information on how to launch a successful Kickstarter without having to lower her goal/budget. 

- What are some other possible tables and/or graphs that we could create?

Another possible graph is one displaying Outcome Based on Duration to determine if the length of the Kickstarter matters. If the length (days) correlates with the success of the Kickstarter, we can suggest an End Month to Louise in addition to the Launch Month.

We can create a table that shows the Count of different donation ranges for the Successful Kickstarters in order for Louise to determined a donation goal range. Sometimes donors do not know how much to donate and providing (or at least Louise knowing this number) a suggested donation range can be beneficial.