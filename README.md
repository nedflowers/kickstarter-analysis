# Kickstarter Campaign Outcomes

## Overview of Project
    Analyzed Kickstarter Crowdfunding Data to determine outcome of theater campaigns as to their launch dates and campaign goals.
       -  More specifically, I wanted to find if there was any relation between a campaign's probability of success in relation to their launch dates and campaign goals.

## Analysis and Challenges
 
### Analysis of Outcomes Based on Launch Date
    I began the analysis by comparing successful, failed, and canceled Kickstarter campaign numbers. To accomplish this, I created a table with Kickstarter's campaign information from the years 2009 through 2017. Then, I assigned the table to read back values reflecting the total failed, successful, and canceled campaign numbers, per month, for the afore-mentioned years. Please see corresponding line chart below:
      
      ![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/95272294/146709522-2d6dac78-719e-4750-9236-84e6679e8018.png)


    As can be inferred from the chart, theater campaign fundraisers, that launched in May, appear to be more successful than in any other month. In fact, through the data, we can determine 63% of campaigns launched in May achieved their goal. In comparison, December campaigns performed poorly, with only a 49% success rate, and one of the higher failure rates at 47%. The only month which saw an even higher number of failing campaigns is October. However, it is worthy to note, although October saw the largest number of failing campaigns at 50, it was also not the best month for success, as only 65 out of 115 campaigns made it. 

### Analysis of Outcomes Based on Goals
    First, I grouped the data based on their goal amount by dollar-amount ranges. Within these ranges, Kickstarter projects are grouped again by numerical values of successful, failed, and canceled projects. Next, the value for the successful, failed, and canceled projects is divided, respectively, by the total number of projects in each range of dollar-amount goals. This gave me the percentage of successful, failed, and canceled projects, which were used to chart the following:

         
        ![Outcomes_vs_Goals](https://user-images.githubusercontent.com/95272294/146709546-34e6e30f-2c9e-43d5-9ffe-6c8b8b15cafc.png)

    
    The chart tells me the percentage of successful projects mirrors the percentage of those failed. Based on the data, campaign goals with less than 1000 dollars were most successful. Conversely, campaigns with goals equaling less than 1000 were least likely to fail. Campaigns within the 45000 to 49999 dollar-range performed the poorest at 100% failure rate and 0% success rate. 

### Challenges and Difficulties Encountered

    In my analysis of outcomes based on goals, I found the outcomes of successful and failed projects mirror each other. Due to our third category, percentage of projects canceled, being consistently zero, the outcome percentages will always equal 100%. With only two categories, each holds 50% of the goals, therefore giving no room to a third category. Meaning, we could come to the same conclusion with only one line chart detailing either percentage of successful or percentage of failed campaigns. this presents a difficulty because it leads me to believe data may be skewed, as we are only able to compare one data point, to its exact opposite, and we already know these categories should oppose each other.   

## Results

- One conclusion I can infer about Outcomes based on Launch Date is projects launched in May are most likely to reach their goal. On the other hand, in December success and failure rates differed by only 2 campaigns. Although the failure rate in December is not as high as that in October or May, I must also look at the success rate, and it's the lowest all year. This marks my second conclusion. A campaign rolled out in December is least likely to succeed, and likely to fail. 

- Based on Outcomes of Campaigns, I can conclude campaigns with goals of less than 1000 are most likely to succeed, and least likely to fail. 

- One limitation of this data set is sample size. If I had more information for additional years, I could run the same formulas, and, perhaps, in adding more variables, find more distinct patterns within Outcomes Based on Goals. Along the same lines, the data collection took place from 2009-2017. Considering it has been almost five years since the end of 2017, the dataset may not be the most accurate representation of data, as it has aged. Additionally, I know the COVID-19 pandemic has changed the way people invest and donate money. It would be interesting to know how donations for Theater campaigns have evolved. Are people donating more money to theater to keep the art alive? Perhaps, people are investing less in plays, as the pandemic makes hosting large indoor events difficult.

- I could create a line chart comparing campaign launch dates, by month, like we have, but include other categories besides theater. This could show if there is a bias in the Outcomes vs Launch Dates chart. Additionally, we could make a bar graph with total amount pledged per category. The chart would be helpful to determine a more precise dollar-amount for a successful Theater campaign.


