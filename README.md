# Kickstarting with Excel
---
## Overview of Project
---
### Purpose
After coming close to her fundraising goal in a very short amount of time, Louise wants to better understand how to maximize her fundraising efforts for future projects by looking at other campaigns. My analysis focused on how different campaigns performed based on two factors: launch date and funding goals.

---
## Analysis and Challenges
---
### Analysis of Outcomes Based on Launch Date
The first step was to filter the Kickstarter data to only select campaign outcomes that were successful, failed and canceled. Then we summarized the data on a monthly basis regardless of which years the campaigns were launched. With these metrics we can display a Line Graph of outcomes on a monthly basis based on the 3 separate outcome classifications; successful, failed, canceled. Finally, we filtered this information through the Parent Category of theater.

---
![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/99817571/155741310-e89521f7-d7c3-4052-94e0-52f6d6824522.png)
---
### Analysis of Outcomes Based on Goals 
The subsequent analysis focused on breaking down the previously selected campaign outcomes category based on different funding goal ranges. We narrowed the scope of outcomes based on goal amounts to only display the subcategory of plays. Once we produced this matrix we calculated the percentage of each outcome classification over that goal range.

---
![Outcomes_vs_Goals](https://user-images.githubusercontent.com/99817571/155741446-f60e2292-cb3f-48e6-b788-fe8175d1ead2.png)
---
### Challenges and Difficulties Encountered
The overall process of selecting and filtering the relevant rows and columns of data in order to produce informative charts was not cumbersome. However, one of the possible challenges that could hamper the process of creating these tables and charts would be in the use of functions such as COUNTIFS() or SUM(). If the proper syntax isn’t used we could be inserting into columns irrelevant or even an excess of data points that could produce inaccurate charts and effect our recommendations for Louise.

---
## Results
### Conclusions
Based on the Launch Date line chart, we can observe that the peak month to launch a successful theater funding campaign would be in the month of May. Similarly, a secondary conclusion we can make is that as the season transitions from winter to spring we see substantial growth in successful campaigns that then begins to drop significantly as the season transitions to summer. Accordingly, the best season for theater fundraising campaigns is in the spring.
Based on The Outcomes Based on Goal data set we can observe that fundraising play campaigns will have a higher likelihood of success if the goal amount is less than 5,000. The ranges of less than 1,000 and 1,000 to 4,999 fundraising goal had a higher than 72 percent chance of success. After 4,999 we can see that the likelihood of success fluctuates as the goal amount increases.

---
### Limitations and Recomendations
One of the limitations of the data set is that we are filtering the Outcomes based on Launch Date and Goals using two different levels of categories; theaters (Parent Category) and plays (Subcategory). Included in the Parent Category of Theater is musicals which is not applicable to Louise whose interest is in campaign outcomes related to plays. This could potentially skew the data for Outcomes based on Launch Date if musicals did not have generally successful outcomes.
A new analysis that we can produce is to display how long it takes to fulfill a plays funding goal. We know that the best month to begin a funding campaign is in the month of May but we don’t know how long it takes to meet the goal amount.
Based on The Outcomes Based on Goal data set we can observe that fundraising play campaigns will have a higher likelihood of success if the goal amount is less than 5,000. The ranges of less than 1,000 and 1,000 to 4,999 fundraising goal had a higher than 72 percent chance of success. After 4,999 we can see that the likelihood of success fluctuates as the goal amount increases.
