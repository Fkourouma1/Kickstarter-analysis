![Chart Image 1](https://user-images.githubusercontent.com/103543959/172937272-ac295000-465a-49b8-8484-643fb207045b.png)
![Chart image 2](https://user-images.githubusercontent.com/103543959/172937301-a8f479ca-ead0-4729-8b89-d5dc3b95c13b.png)
# Kickstarting with Excel
Kickstarter Challenge 1
## Overview Of Project 
The main purpose of this project is to help Louise who is looking to start a crown funding campaign to fund her play. We need to help her analyze, visualize and organize her data.
### Purpose
The purpose of this project is to help Louise visualize her campaign according to their Launch date and funding goals. 
## Analysis and Challenges
In this project, we first named our file as Kickstart_Challenge.xlsx, then we created a YEAR column based on Launch date by using the YEAR()formula. Next, we created a pivot table and chart filtered by Theater and years; we filtered the column for “successful”, failed” and “canceled”.
We next created a new sheet named “Outcomes Based on Goals”. This included Goal, number Successful, Number Failed, Number Canceled, Total projects, percentage Successful, Percentage Failed and Percentage Canceled. Our Goal columns were grouped based on their goal amount. Then we used the COUNTIFS() function to calculate the number of Successful, Failed and Canceled by using “plays” criteria. After that we calculated the total project Sum as well as the percentage for each Category. We end this part by creating a chart. 
My challenge with this project was calculating the percentage and using the COUNTIFS() formula. And analyzing the chart. 
### Analysis of Outcomes Based on Launch Date 
Based on Launch date, we created a new sheet in our Kickstarter file which we filtered by years and parent category “Theater” and finish it by creating a chart.We also added the outcomes count for successful, failed and canceled Theater as well as the months. 
After setting up our pivot table, we came across that the month of May had a higher count of “Successful” as 111. It is also noticeable that “Theater” Parent category have a few numbers of “Canceled” which total only 37. While the Grand total is 1369 with 839 Successful”.
At last, we created a pivot chart titled Theater Outcomes Based on Launch Date. This chart visualizes our pivot table.  
### Analysis of Outcomes Based on Goals
In this section, we created a new sheet that we renamed “Outcomes Based on Goals”. This included Goal, number Successful, Number Failed, Number Canceled, Total projects, percentage Successful, Percentage Failed and Percentage Canceled. The "Goal" columns were grouped based on their goal amount. Then we used the COUNTIFS() function to calculate the number of Successful, Failed and Canceled by using “plays” criteria. After that we calculated the total project Sum as well as the percentage for each Category. We finalyse it with a line Chart.  
### Challenges and Difficulties Encountered
The first challenge in this project was to make sure we are filtering the parent category as “Theater” so our numbers can reflect accurate information. Then making sure that our data in descending order as required. 

## Results
- What are two conclusions you can draw about the Outcomes based on Launch Date?
The first conclusion is that the category “Theater” has a considerable number of “Successful”.
Secondly, the count of cancelled is not noticeable. It is very low. 
- What can you conclude about the Outcomes based on Goals?
Based on the Goal, it was remarkable that we had no Play marked as “Canceled”.
The highest number of “Successful was in the goal range of 1000 to 4999.
- What are some limitations of this dataset?
In my view, one of the limitations of this dataset could be to visualize the dollars amount lost or gain based one categories or subcategories. Another limitation could be to create a table based on the count of donator. By country. 
- What are some other possible tables and/or graphs that we could create?
We could create a table with the Outcome, Country and the Average donation. That can help her analyzed which country has donating more and how will that reflect with the outcomes. 
