# Kickstarting with Excel

## Overview of Project
The Purpose of this analysis is to help our client, Louise, determine the best course of action for implementing her Kickstarter campaign. Louise wants to launch a Kickstarter campaign to fund her new play, Fever. She has an estimated budget of $10,000, and wants to know if there are any specific factors that can determine whether or not a campaign will be successful or not. 

## Analysis and Challenges
In this analysis, two areas were looked at as possible reasons a Kickstarter might, or might not be successful. The first relationship that was analyzed was if the launch date of the Kickstarter campaign had any effect on the outcome, and the second was if the goal amount. 
### Analysis of Outcomes Based on Launch Date
In this analysis I created a pivot table from the Kickstarter data, made the table filterable by parent catagory and years, added outcomes to columns, outcomes to the sum values, and date created to my rows. I then re-arranged the columns so successful was first. I deslected "live" as an outcome so it was not displayed. the row labels were then grouped to show months of the year. the parent category was then filtered to only show theater projects. The chart that was created from this is below:
![Theater Outcomes VS Launch Date](https://github.com/tylersojka/kickstarter-analysis/blob/master/Theater_Outcomes_vs_Launch.png)
### Analysis of Outcomes Based on Goals
![Theater Outcomes VS Goal](https://github.com/tylersojka/kickstarter-analysis/blob/master/Outcomes_vs_Goals.png)

### Challenges and Difficulties Encountered
The largest challenge with this analysis was simply learning how to efficiently use excel to make pivot tables. This challenge was easily overcome with practice. The task of matching the data with that of the example was also a challenge. In the outcomes based on goals part of the analysis, I Intuitively wanted to find the percentage successful/failed plays out of the total number of Kickstarter campaigns, not out of the only plays sample. The last challenge was the tediousness of altering the countifs function for each of the separate goal ranges.
## Results

- ### Conclusions about the Outcomes based on Launch Date
1. From on the analysis of the outcomes based on launch date, it is clearly obvious that for Louise, who wants to launch a Kickstarter campaign to fund her play, the best time of the year to start her campaign would be in May. The number of successful theater Kickstarter campaigns peaks in May, followed by a steady decline of successful plays for the rest of the year. This also coincides with the peak in percentage of successful theater Kickstarter campaigns. 
2. The second biggest factor she needs to take into consideration is when to not produce her play. As you can see in the analysis, December is by far the worst month for successful play campaigns. December boasts the lowest number of successful plays, along with the lowest percent of successful plays. 
3. **Conclusions: From the analysis of outcomes based on launch date, Louise should try and launch her campaign in May, and should defiantly not launch her campaign in December.**
- ### Conclusions about the Outcomes based on Goals
The analysis of outcomes based on goals was less conclusive. Louise has a budget of $10,000, which puts her chances of success, based on the analysis, at around 54%. The easiest way to bump her into a higher percentage, would be to cut her budget by more than half to put her in the $1,000-$4,999 range with a 73% success rate. 
- ### Limitations of this dataset
This dataset would have been even nicer with more recent data. The current cut off was 2017, meaning about 3 years of data more closely correlated to recent social climates is missing. 
- ### Other possible tables and/or graphs that we could create
1. An additional chart and table that would be useful would be the percentages of failed/successful campaigns based on launch date. The chart we had designed with just the numbers of successful/failed campaigns happened to line up pretty closely with the percentages, but a good visual would have been nice.
2. I would have liked to see if the campaign being a staff pick had any effect on it being successful or not.



