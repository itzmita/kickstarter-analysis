# An Analysis of Kickstarter Campaigns.
Performing analysis om Kickstarter data to uncover trends

We created the below Pivot Chart based on the Outcomes of the Parent Category. This analysis tells us that the Parent Category Theatre is the most successful. This also shows that Louise choice for theatrical productions is the right step forward to a successful campaign.

![image](https://user-images.githubusercontent.com/3753839/161193647-79ea4445-7157-47e9-bbd3-5882fac37c12.png)


We created the below Pivot Chart based on the Outcomes of the Subcategory. This analysis tells us that the SubCategory "Plays" is the most successful one.  

![image](https://user-images.githubusercontent.com/3753839/161193705-f3facaff-2a99-4767-bee6-93701fbc6eb6.png)


We created the below Pivot chart based on Outcomes on Launch Dates. If we see the below chart, the most successful campaign was in the month of May followed by June.  

![image](https://user-images.githubusercontent.com/3753839/161193735-b4189b08-f976-499d-a3bd-87b76e43f473.png)
---------------

**Kickstarter-Analysis**

Analyzing Kickstarter dataset to uncover trends based on certain factors.

1. Overview of project:

Background -
This assignment focuses on analyzing Kickstarter dataset which has a total number of 4114 campaign events across 9 main categories. We will be analyzing the Main category theatre and subcategory plays.  

Purpose -
This analysis is done to help Louise prepare for a successful campaign that she envisions. Her play Fever came close to its fundraising goal in a short amount of time. Now, she wants to know how she can make her campaign successful and what factors she needs to consider.

--------------
2. Analysis and Challenges:

Louise’s play Fever came close to its fundraising goal in a short amount of time. Now, she wants to know how different campaigns fared in relation to their launch dates and their funding goals


Analysis of Outcomes Based on Launch Date - Theater -

From the Kickstarter dataset we created a column named Years using the excel formula YEARS(). Once we knew the year, we created a Pivot table to have the month shown in the x-axis and outcomes shown in the y-axis. To show the months we had to group the Year rows and select the month. We are interested only in the Parent category Theatre so we had to filter that to get the final chart as below.

![image](https://user-images.githubusercontent.com/3753839/161193820-dd2d8ee4-1edd-4709-89af-529fb8744d5a.png)

-------------------
Analysis of Outcomes Based on Goals -

The below Line chart helps us to understand that Goals less than $1000 were 76% successful and most of the unsuccessful campaigns were around $45000 - $49999. Goals around $10000 - $14999 were 54% successful and 46% failed.
From the Kickstarter dataset we filtered data pertaining to plays only. There were various bands of goals we had to consider in this analysis such as Less than $1000, $1000 - $9999 etc till $50000 and more.  The focus was outcomes for these Goals which we used COUNTIFS() function to derive the counts. We could make a grid which says about the Goal bands as rows and tells how many were successful, failed, canceled campaigns . We calculated the percentage of the outcomes. Next we created a Pivot line chart as shown below.

![image](https://user-images.githubusercontent.com/3753839/161193879-0b53f348-2c47-4b51-8af6-32036d9d52bc.png)


Difficulties and Challenges Encountered -

The Outcomes Based on Goals was more challenging for me as it had lot of formulas to be typed manually. I was making errors for referencing wrong cell numbers as there were a lot of those to type. Its prone to error. 
I had a bit of challenge figuring out how to show the % after the value in the y -axis for this deliverable 2. 



-----------------

3. Result:

Conclusions from the Outcomes based on Launch Date -

	• Month of May had the highest number of successful campaigns followed by June. These 2 months had significantly higher successes than other months. 
	• Month of May also had the highest number of failed counts so Louise should look at these 2 months for launching her campaign.
	
        
Conclusions Drawn from the Outcomes based on Goals -

	• From the chart , we see that chances of having more successful campaigns are when the Goal amount is either very less like less than $1000 or significantly higher range like $35000 to $44999. 
	• The lowest change of failure is when the Goal amount is less than $1000.
	• So Louise might want to have a lesser goal than she has currently for the Fever play, in that way she will have less chances of failure. 
	

Limitations of Dataset -
	
	• The year for the data is from 2009 - 2017 (Pre-pandemic). If we can get more recent data, there might be different trends. 
	• What particular age groups participated in the pledged amount?
	
	
Other possible tables and/or graphs that we could create -

	• We can create a Pivot table to show goal amounts based on Parent Category/Subcategory and how much was pledged for each of them. This can help Louise understand how much she should set as Goal amount for her play.  









