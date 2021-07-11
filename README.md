# Kickstarter Campaign Analysis
## Overview and Purpose ###
This project was to analyze how the theater campaign was impacted based launch dates and funding goals. Analysis was performed on the success, failure and cancelation of Theatre outcomes over time and financial outcomes base on goals for the category of plays.
The project's purpose was to understand what period of time had the most significant impact on the success, failure and cancelation of Theater and within the category of plays, which financial goal was more closely met.

## Analysis and Challenges ###
Challenges with this project included having to manipulate a dataset developed as part of previous work.  Prior to beginning the Kickstarter Challenge, the file was used for learning basic Excel functions in previous lessons.  Not knowing this and having already had basic excel knowledge, I did not develop the file as needed however had to go back and develop it to meet the requirements of the deliverable. 
 
![Image1.PNG](https://github.com/Wildernessbob218/Kickstarter_Analysis/blob/main/Resources)


### Analysis and results of Outcomes Based on Launch Date ###
After reviewing the Outcomes vs launch date, it is clear that the majority of the Theater outcomes were successful between May, June and July while the failure of the outcomes and cancelations remained relatively stable throughout the year.
The November and December saw the lowest success rates which is most likely a result of most major holidays taking place during this time.

![Theater_Outcomes_Vs_Launch.png](https://github.com/Wildernessbob218/Kickstarter_Analysis/blob/main/Resources)

### Analysis and results of Outcomes Based on Goals ###
When analyzing plays, it is clear the highest quantity of successful campaigns fell below the amount of $5,000 or less however most of the project took place within this range as well. There appears to be a slight correlation with successful campaigns and the funding goal of less than $5,000 and between the range of $35,000 and $45,000.

![Outcomes_vs_Goals.png](https://github.com/Wildernessbob218/Kickstarter_Analysis/blob/main/Resources)

### Challenges, Limitations and Difficulties Encountered ###
Challenges with this dataset included what was already stated above in addition to getting the syntax correct when calculating counts using multiple criteria.  This took a bit of error checking to make sure that the cell references were 100% accurate. An example of one of these complicated countif statements is shown below.

=COUNTIFS(Data!$D:$D, ">=15000",Data!$D:$D, "<=19999",Data!$F:$F, "failed",Data!$N:$N, "theater/plays")

Limitations with this dataset include a lack of breakdown by geographic region and/or major metropolitan area of the county indicated.  If this data was present, additional detailed analysis could be performed to determine if there is a regional impact on the campaigns. 

This data could be gathered easily and prove to the useful for more targeted analysis and understanding of the campaign impact.

Additional analysis could be performed to compare the number of live outcomes in relation to successful, failed and canceled to project the potential impact on these when they complete.

