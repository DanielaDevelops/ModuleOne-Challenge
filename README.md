# An Analysis of Kickstarter Campaigns
Analyzing Kickstarter Campaign data to uncover trends and generate insights into how different factors influence campaign outcomes. These findings will be presented using charts and graphs to provide Louise with essential information at a glance. Visualizations aid in uncovering a link or trend within a dataset, but depict the findings in a simple, user-friendly way.

To access the first part of the analysis that was completed throughout the course of Module One, please go here: https://github.com/danidevelops/kickstarter-analysis

## Analysis and Challenges
**Analysis:** Louise’s play Fever came close to its fundraising goal in a short amount of time. Now, she wants to know how different campaigns fared in relation to their launch dates and their funding goals.

**Challenges:** In completing this analysis, some challenges that I encountered was the ability to read the data for what it was, in order to help Louise with her success in her production, "Fever". After running multiple analysis, such as creating pivot tables and graphs to present the data to compare it against itself/previous data created. The information started to make sense, and it was a lot simpler to assist Louise in her decision to move forward with her production and to make her aware of what metrics she should look out for. 

## Analysis Results 
To determine if other Kickstarter campaigns were able to come close to their fundrasing goals in a short amount of time, two main factors were analyzed:

  1. Outcomes Based on Launch Date
  2. Outcomes Based on Goals
  
### Part One: Analyzing Outcomes Based on Launch Date for Theater Parent Category  
The line graph below tells us a few important factors that will help Louise in her campaigning. 
![Outcomes Based on Launch Date](https://github.com/danidevelops/ModuleOne-Challenge/blob/master/Theater_Outcomes_vs_Launch.png)

**Observations:** 
* The length of the campaign and its' launch date do play an important role in campaign success.
    - May and June are the best months to launch Theater campaigns
    - December is the worst month to launch 
    
**Recommendations:** 
* Louise should launch her campaign in May or June to maximize her chances of being successful. 
    
### Part Two: Analyzing Outcomes Based on Goals for Plays Subcategory
The line graph below, visualizes the percentage of successful/failed/canceled campaigns based on their fundraising goals.
![Outcomes Based on Goals](https://github.com/danidevelops/ModuleOne-Challenge/blob/master/Outcomes_vs_Goals.png)
*This figure is helpful in visualizing how **Too High** of a goal or **Too Low** of a goal may impact the outcome of a campaign. In order to see this information more clearly, take a look at the Box and Whisker Plot below*

Louise was looking at musicals in Europe. The box plot includes helpful information to Louise, in order for her to start her next endeavor. 
![Box and Whisker Plot - GB](https://github.com/danidevelops/ModuleOne-Challenge/blob/master/Box%26WhiskerPlot-GB.png)

**Observations:**
- We observe that 84% of the Plays campaigns have a goal of less than $10,000.
- We observe that 75.81% of the Plays campaigns with a fundraising goal of less than $1,000 are successful.
- We observe that 72.66% of the Plays campaigns with a fundraising goal between $1,000 and $4,999 are successful.
- We observe that the majority of successful campaigns for Plays (76%) have a fundraising goals of $4,999 or below.
- We observe in the dataset that you are more likely to fail (49.5%) if your fundraising goal is $5,000 and above, than if it's below (26.5%). 
- While we observe other high percentages of successful campaigns in higher goal brackets, we have established that the data is skewed and that these numbers are not significant.
- It's interesting to note that there aren't any canceled campaigns in the Plays subcategory.
- **Box Plot:** The mean and median pledged amounts are much lower than the successful pledges, which indicates that failed kickstarters are unsuccessful for reasons other than asking for too much money.

**Recommendations:**
- Louise should keep her fundraising goal below $4,999 to increase her chances of being successful.
  
### Part Three: Summary of Analysis
With these two analysis, we can make the following recommendations to Louise:
- Keep your fundraising goal below $4,999 to increase chances to be successful.
- Launch your campaign in May or June to maximize chances to be successful.

However, we're unable to provide a cohesive answer to the two questions asked in the introduction as it would require further analysis to do so, such as:
- Analysis of Outcomes Based on Length of Campaign
- Analysis of Descriptive Statistics (Mean, Median, IQR)
- Analysis of Outcomes Based on Length and Percentage Funded 
