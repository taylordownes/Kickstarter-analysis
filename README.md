# Kickstarting with Excel

## Overview of Project

### The purpose of this project is to give Louise a report on how different campaigns perform in relation to their launch dates and funding goals using the kickstarter data set.

## Analysis and Challenges

### To conduct the analysis for theater campaign outcomes based on launch date I created a column in the kickstarter data to extract the year using the YEAR() function in excel. Once the year data was generated, I inserted a pivot table with filters for “parent category” and “years” with the months of the year as columns associated to the count of outcomes for each labeled outcome option. Once the pivot table was generated, I create a line chart to visualize the trends for theater outcomes based on launch date shown below.

# ![alt tag]<https://github.com/taylordownes/Kickstarter-analysis/blob/main/Resources/Theater_Outcomes_vs_Launch.png>![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/84201614/121591562-449e4a80-c9ff-11eb-9454-5b782bf9f640.png)


### To conduct the analysis for theater campaign outcomes based on fundraising goal, I created a new sheet and added appropriate headers for goals, numbers, and percentages of successful, failed, and canceled campaigns. Using the COUNTIFS() function in excel, I calculated the corresponding numbers and percentages of the outcomes based on the goals from the kickstarter data provided. Once the data was complete, I inserted a line chart to visualize the outcomes based on goals as shown below.

### As visualized by the pivot tables and charts, the data has various trends that can make it difficult to draw specific conclusions. For example, the campaign outcomes based on goals chart has a steady decline until it reaches around $35,000 to $50,000 in fundraising goals. This prevents us from confirming a stronger result in successful campaigns under $20,000. A larger sample size could help make the trend more apparent and help to visualize a stronger decline.

## Results

-The line chart of theater outcomes based on launch date shows that campaigns launched in May and June appear to be the most successful. We can also see high numbers of failed campaigns were launched in May and October and less campaigns failed in September, November, December, and January. Based on the kickstarter data, launching a theater fundraising campaign in May or June appears to be the most successful and November – January appears to be less successful.

- The line chart of outcomes based on goals shows that the most successful campaigns have fundraising goals around $20,000 or less. There is also a peak of successful campaigns with fundraising goals between $35,000 to $50,000. We can also see that theater campaigns with fundraising goals over $50,000 have higher chances at failing. Based on the kickstarter data, the most successful campaigns have a fundraising goal of $20,000 or less.

- Some limitations on this data analysis could include the sample size and location. A larger sample size could help trends become more apparent or uncover new trends that do not exist in this particular dataset. The location could also be narrowed down to target a more accurate and specific sample size. It is also important to consider room for error as the data collected could have been under or over estimated.

- In terms of additional analysis, we could look at analyzing campaign outcomes based on country to see if that would impact Louise’s desired results on theater fundraising campaigns. We could also add more variables such as “fundraising method” to compare the successful campaigns to their method of fundraising.
