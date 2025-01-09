# Banking Campaign Analysis Power BI project
## Introduction
An exploratory data analysis project where we will analyze the results from a banking campaign and take a look at factors affecting the likelihood of the campaign's success. We want to find the biggest predictors of success of the campaign and use that to determine what factors the bank should focus on to maximise the success of future campaigns.
## Tools used
- SQL: The tool I used to retrieve the useful columns from the riginal dataset
- SQL Server: The chosen database management system
- Power BI ETL: Tool used to clean, transform and load the data 
- Power BI data visualization: What I used to create the dashboard visual 
## The Analysis
Here are some of the key insights I extratcted from the data that are visible in the dashboard:

### 1. Overall Success and Failures
The majority of customers contacted during the campaign did not result in a success, as seen in the "Number of Contacted Customers" bar.
The successes (shown in lighter green) are significantly smaller than the failures, suggesting room for improvement in targeting or approach.

### 2. Success by Employment Variation Rate (Emp Var Rate)
Successes peak at a negative employment variation rate (-2).
As the employment variation rate approaches 0 or goes positive, the number of successes declines significantly.
Insight: Negative employment variation rates might indicate favorable economic conditions for this campaign’s target audience.

### 3. Success by Education Level
Customers with university degrees have the highest success rate (38.08%), followed by high school graduates (23.51%).
Other educational groups, such as "Basic Education (9Y, 4Y, 6Y)" and "Professional Courses," show comparatively lower success rates.
Insight: The campaign is more effective with higher-educated individuals, so targeting university graduates may yield better results.

### 4. Success by Previous Contacts
Customers who were contacted twice previously had the highest number of successes.
Customers contacted once or more than three times show fewer successes.
Insight: A sweet spot exists at two previous contacts, suggesting over-contacting may reduce effectiveness, and under-contacting misses opportunities.

### 5. Success by Month and CPI (Consumer Price Index)
Successes were highest in March and April and declined in subsequent months, with a notable drop in July.
The Average CPI trend line doesn’t strongly correlate with the number of successes, but high CPIs in April and September align with increased campaign success.
Insight: Campaign timing plays a role, with early-year campaigns (March-April) being more successful. July campaigns may need review.

## Conclusions
Based on these insights here are some recommendations on what factors the company should focus on to maximse the success of future camapigns:

- 1.Target Audience: Focus on customers with university degrees or high school education for higher campaign efficiency.
- 2.Optimal Contact Frequency: Limit contact attempts to two, as over-contacting reduces effectiveness.
- 3.Timing: Prioritize campaigns early in the year (March-April) and explore why July campaigns are less successful.
- 4.Emp Var Rate: Consider leveraging negative employment variation rates in your strategy for targeting audiences.
