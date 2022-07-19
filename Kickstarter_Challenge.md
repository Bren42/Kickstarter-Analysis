# Kickstarter Campaign Outcomes

## Overview of Project
This project is designed to look into patterns of successful or failed kickstarter campaigns in an effort to drive future campaign success. Specifically we will be reviewing campaigns within the Theater segment with a focus on the Plays subcategory. The project will analyze whether funding or timeframes have an impact on whether a campaign is successful or not and help the client with future campaign planning.

### Purpose
Determine if there are any patterns of success or failure in relation to a campaigns specific launch window, or a campaigns funding range, in an effort to help our client with future campaign launches.

## Analysis and Challenges
The analysis began using a data set with a 7 year range of campaigns from 2011 to 2017. Our specific analysis in this case was targeted to Theater campaigns, specifically focused on the subcategory of plays. The analysis was trying to determine whether or not we could see any patterns that would act as drivers of success or failure. Two areas were reviewed during this analysis, launch date based outcomes, and funding goals. Launch date would allow us to see if there was any level of seasonality related to campaigns. Whereas funding goals would help us to see what pledge range was most likely to succceed,if any. 

 ## How we processed the analysis
The launch date analysis we gathered the data to look at each month within the year and examined the number of successful, failed, or cancelled campaigns within the the Theater/Plays categories. Using standard pivot data we were able to build a chart to more easily view the outcomes based on the time of year that they were launched. Where we could run into challenges is in the fact that we are looking at a narrow scope of data, some outcomes may be too general to be actionable. Another challenge is whether or not factors from either analysis overlap with one another and if that has any impact on our outcomes.

 In regard to the Outcomes based on Goals we needed to define funding ranges, in general we used ranges of 5,000 starting at 0 and stopping at 50,000, so that we could compartmentalize the data and get a better understanding as to whether a certain range produced more succesful campaigns. This was compared against the number of successful, failed, and cancelled campaigns in each range.

### Analysis of Outcomes Based on Launch Date

![Launch Date Outcomes](https://github.com/Bren42/Kickstarter-Analysis/blob/main/Resources/Theater_Based_Outcomes_vs_Launch.png)

 With the Launch date analysis there are a couple of items that present themselves upon evaluation. Out of 839 successful campaigns May and June stood out to have the highest success rate with 111, and 100 successful campaigns. However both of those months also had the highest amount of campaigns in total. May for example had a total of 166 campaigns with 111 successful, whereas the lowest month for campaigns launched, December, only had a total of 75 campaigns. 
 In an effort to make sure that volume alone was not skewing our outcomes we had to look at the percentage of success against the total campaigns to see if percentage of succesful campaigns aligned as well. What we found was that May was still the most successful month with a 67% success rate, June came in second with 65%, which followed in line with the volume outcomes as well. We also tested this against the lowest volume months,December which had the lowest volume also came in lowest percentage of success. So we have found that there is a pattern of seasonality for successful campaigns and that May and June have not only the highest volume of campaigns launched but also the highest percentage of success.
 ## Analysis of Outcomes based on Launch date, Failures

 ![Funding Goals Outcomes](https://github.com/Bren42/Kickstarter-Analysis/blob/main/Resources/Outcomes_vs_Goals.png)

 Funding goals outcomes were designed to see if the total overall goal impacted the campaigns success rate. What we found was that the highest rate of success seemed to fall between the less than 1000 range and the 1000 to 4999 range. We saw a steady decline in success rates after that point. It is worth noting that there is a spike in the success rate around 35000 t0 39000 range, however there were only 6 campaigns in this range making it a likely outlier.

 ### Final Summary of Outcomes based on Launch Date
 Based on what the data is telling us between success rates and failure rates the best time to launch a new campaign would be within the May and June timeframes, with the later part of the year, particularly November and December being the worst time to launch a campaign succesfully.

### Analysis of Outcomes Based Funding Goals
When analyzing the success rate of campaigns based on the funding goal we have found that the highest success rate, 76%, occurs in the lowest range of goals that require funding of 1000 or less> the second most successful range is the next lowest tier of 1000 to 4999 dollars. From that point success rates fall off as funding goals increase. There are two exceptions to the pattern of decreased success based on higher funding and those occur in the 35000 to 39999 range, and 40000 to 44999 range, which both increased to 67% success. However those seem like they could be skewed as they only have 6 and 3 total projects for each, the smaller sample may be impacting their outcomes. What we can conclude though is that your best chance for success will mean targeting funding goals to 5000 or less if you want to have a higher chance at success.

### Challenges and Difficulties Encountered
## Data Limitations
There are some limitations with the current data that do limit us from further researching more specific reasons a campaign may or may not succeed. We have country level data, but nothing more granular such as city, this could be impactful, it is possible that the specific location of the play impacts success. We also do not see in this data any of the backer goals typically associated with a Kickstarter campaign, do backer goals increase the odds of success? Another limitation of the data set, particularly in the Theater cateogry is genre, if we had the genre we could see if there were specific areas that were more likely to succeed.
## Alternative Analysis Areas
The are other areas in this data that we could chart to see if there are any other correlations. We could run launch data and funding data on other categories, or sub-categories to compare them and see if similar outcomes in seasonality and funding ranges apply as well. We could run analysis against the years as well to see if patterns may be emerging beyond the month data. 
## Results
The results are that if you are looking for the highest probability of success within the Theater/Plays segemnts of Kickstarter you would want to target your campaign to start around May or June and keep the requested funding to 5,000 dollars or less. With more data would could likely drill into this further and find more specific outcome drivers.
