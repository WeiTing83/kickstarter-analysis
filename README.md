# Kickstarting with Excel
  
## Overview of Project
    Louise achieved her fundraising goal within a short period of time and she would like to understand how different campaign outcomes would get 
    impacted by launch dates and funding goals.

### Purpose
    We want to know how the campaign outcomes would get impacted by launch dates and funding goals.

## Analysis and Challenges
    Following the instruction, I step by step to analyze the data. If I’m not familiar with formulas, I click hint and watch the Video. Then,
    understand how to use the formulas and go back to figure out how to apply into my project. After I finish the data analysis, I double check 
    the result using another way. Like deliverable 2, I used pivot table and group goal to confirm the calculation result in my new sheet to see 
    if they are matched. The most challenge part is to establish this report since I never use markdown before. I did google it and figured out 
    how to use the markdown to preview the result.

### Analysis of Outcomes Based on Launch Date  
![Theater_Outcomes_vs_Launch](https://github.com/WeiTing83/kickstarter-analysis/blob/main/resource/Theater_Outcomes_vs_Launch.png)
### Analysis of Outcomes Based on Goals
![Outcomes_vs_Goals](https://github.com/WeiTing83/kickstarter-analysis/blob/main/resource/Outcomes_vs_Goals.png)
## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
   
    1.In summer (May, June and July), there are more activities so they also had more successful cases. Thus, in summer, theater fundraise goal 
      is easier to be achieved. But the average of failed cases is 41+-10 and it seems like it is very consistent through 12 months.

    2.However, this result didn’t consider different sample size. If we considering the sample size, it is easier successful in May and easier failed in Dec. 

- What can you conclude about the Outcomes based on Goals?
  
    1.Outcomes of goal above $25000, its result is lack of credibility due to smaller sample size.

    2.In the goal between $1-25000, higher goal tend to fail easily.  Within this range, Goal value and percentage of failure are positively correlation. 
      Goal value and percentage of success are negative correlation.

- What are some limitations of this dataset?
  
  	1.The outcomes of goal above $25000, its result is lack of credibility due to smaller sample    
      size.

    2.Theater Outcomes Based on Launch Date can’t exactly describe which month is easier successful  
      or failed due to different sample sizes.

- What are some other possible tables and/or graphs that we could create?
  
    1.The outcomes versus how many dates to perform this case (Deadline-launch date)

    2.We should do data comparison based on the same country because different countries have different currency values.
    
    3.Base on different sample size, Theater_Outcomes_vs_Launch.png should be converted to ratio [(successful/grade total, failed/grade total) vs. launch date.]
