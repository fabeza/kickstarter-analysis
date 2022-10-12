# Kickstarting with Excel

## Overview of Project
### Our client Louise launched a crowdfunding campaign to fund her new theater play, "Fever," and came close to its goal. Now Louise needs more details from us to interpret the outcome of her campaign. We studied other crowdfunding initiatives in the entertainment sector to offer accurate conclusions. We determined the correlation between campaigns' outcomes, launch date, and funding goal.

## Analysis and Challenges
### Our team analyzed a data set of 4,115 crowdfunding fundraisers launched between 2009-2017 in various entertainment categories and countries and with varying funding goals (see [Kickstarter_Challenge](https://github.com/fabeza/kickstarter-analysis/blob/eb0d088fda78f611a69d8757cf67b3c65ee43036/Kickstarter_Challenge.xlsx.zip)). For this analysis, we have focused on fundraising campaigns for theater (1,369 campaigns), the dates these campaigns were launched, their funding goal, and their outcome (successful, failed, and canceled).

### Analysis of Outcomes Based on Launch Date
### As seen in the "Theater Outcomes Based on Launch Date" chart below, the majority of successful campaigns for theater performances were launched between May and July. The number starts declining by the end of the summer months. Additionally, we determined that December was the month with the fewer number of successful campaigns.

### ![Theater_Outcomes_vs_Launch](https://github.com/fabeza/kickstarter-analysis/blob/eb0d088fda78f611a69d8757cf67b3c65ee43036/Resources/Theater_Outcomes_vs_Launch.png)  

### You can find the pivot table used for this chart in the "Theater Outcomes Based on Launch Date” sheet in our [Kickstarter_Challenge](https://github.com/fabeza/kickstarter-analysis/blob/eb0d088fda78f611a69d8757cf67b3c65ee43036/Kickstarter_Challenge.xlsx.zip) file.

### Furthermore, the analysis shows that most failed campaigns launched in May, July, and October. Despite May and July being summer months, another factor may have caused these fundraisers to fail: their funding goal.

### Analysis of Outcomes Based on Goals
### The majority of successful theater play fundraisers reported in our study had a goal of less than or equal to $5,000. The chart below, "Outcomes Based on Goals," illustrates that the percentage of successful campaigns within that goal range is higher than that of failed campaigns. We can also observe a tendency for a higher percentage of campaign failure when the funding goal is higher. A few outliers in the data set need further analysis to determine the circumstances that made those campaigns with higher funding goals successful.

### ![Outcomes_vs_Goals](https://github.com/fabeza/kickstarter-analysis/blob/eb0d088fda78f611a69d8757cf67b3c65ee43036/Resources/Outcomes_vs_Goals.png)

### You can find the percentage calculations used for this chart in the “Outcomes Based on Goals” sheet in our [Kickstarter_Challenge](https://github.com/fabeza/kickstarter-analysis/blob/eb0d088fda78f611a69d8757cf67b3c65ee43036/Kickstarter_Challenge.xlsx.zip) file.

### Challenges and Difficulties Encountered
### Our analysis showed there are some contradictory campaigns. Some high-goal campaigns were successful, and some campaigns with lower goals were successful even though they launched in the fall and winter/holiday months. Further evaluation is needed to determine the drivers of success for those campaigns. Furthermore, we could remove the outliers, narrow our results to plays only, US only, and perform our analysis with funding goals more comparable to Louise’s fundraising campaign to make more accurate recommendations and conclusions. Additionally, the months with the highest number of successful campaigns are also the months with the highest number of failed campaigns. Further analysis is needed to explain this and if the correlation between outcome, launch date, and goal.

## Results

### Outcomes based on Launch Date Conclusions
### * May, June, July, and August (i.e. summer) are the months with the highest numbers of successful campaigns.
### * November and December (i.e. holiday season) are the months with the lowest number of successful campaigns.

### Outcomes based on Goals Conclusions
### * The lower the funding goal, the higher the percentage of a successful outcome and vice versa.
### * The lower the funding goal, the lower the percentage of a failed outcome and vice versa.

### Dataset Limitations
### * There are a few exceptions to the conclusions. It would be helpful to remove the irrelevant outliers to this analysis and study those campaigns that contradict the above-stated findings.
### * Having a pivot table and chart showing the correlation between funding goal and launch date would provide further details.
### * The analysis and charts would have been more accurate by filtering countries and subcategories for both. 
### * The data set could be more specific, including the channels used to launch the campaign and the target audience since some backers can donate thousands of dollars.

### Additional tables and/or graphs we could create
### * Outcomes based on goal and launch date
### * Average goal vs pledge for theater plays campaigns in the US
### * Outcomes based on Goals for theater plays-only and US-only
### * Outcomes based on the launch date for theater plays-only and US-only
### * Outcomes based on the duration of the campaign
### * Average donation based on funding goal
