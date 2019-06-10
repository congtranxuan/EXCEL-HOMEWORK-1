# Excel Homework 1

The work is done based on the Kickstarter dataset representing the projects created on Kickstarter platform in some years.

1. Used conditional formatting to highlight the column of state with different colors according to its states.

![boy-512](https://user-images.githubusercontent.com/50689116/59233135-d4a91f80-8bac-11e9-92ee-1dc53566c17b.png)

2. Created a column named Percent Funded use formula E2/D2*100 to represent the percentage of fund that was gained.
![test img](2016-11-08 (1).png)
 

3. Used conditional formatting with 3 color-shading red, green, blue to highlight the interval of Percent Funded within 0-100-200.
 

4. Created column P called Average Donation using formula If(L2<>0,E2/L2,0)

5. Split column Category & Sub-category into two columns Category in column Q and Sub-Category in column R using Data/Data Tools/Text to Columns.

6. Analyze the dataset using Pivot table and Pivot chart sorted with Category.
 

7. Analyze the dataset using Pivot table and Pivot chart with Sub-Category
 

8. Because the deadline and launched at columns store date at Unix Timestamp, use formulas (J2/86400)+DATE(1970,1,1) and (I2/86400)+DATE(1970,1,1) to change date to Excel style and store at Date Created Conversion and Date Ended Conversion columns.

9. Used Pivot table and Pivot chart to analyze the data to count the number of successful, failed and canceled based on Date Created Conversion.
 

10. Some comments about this dataset:
a)		Given the provided data, what are three conclusions we can draw about Kickstarter campaigns?
•	Three categories which had the most successful projects are theater, music and film & video.
•	Most projects in journalism were canceled at final.
•	In category of theater, there are most projects in plays sub-category and the number of successful projects is almost double the number of failed ones.
•	There are most of projects based on goal of more than 1000 and less than 4999 backers. However, with the projects had the goal less than 1000, it had more chance of success.
b)	What are some limitations of this dataset?
•	This dataset is limited by the scenarios of Kickstarter platform, it would not represent for all the projects belonging to the categories or sub-categories and started on that time that created on other platforms.
•	The projects in same categories created in the same month but different years would be different because the differences in scenarios and trends.
•	Within the same category or sub-category, every project depends on different elements to succeed but the same goal or same date in a year.
c)	What are some other possible tables and/or graphs that we could create?
•	We can analyze the chance of success for projects by the percent fund, what is the minimum to be successful.
•	We could create more tables to analyze the projects in categories with goals, which goals are suitable for projects to get the success.
11. Created a sheet of Outcome based on Goal to analyze the projects with goal using COUNTIFS('Kickstater Data'!$F$2:$F$4115,B$17,'Kickstater Data'!$D$2:$D$4115,"<1000") according to its ranges and states.
 

12. Analyzed the statistical aspect of the dataset by created sheets called Backers for Outcomes, Successful data to test Median and Unsuccessful data to test Median. I copied figures from Kickstarter Data and used Data Analysis Tool/Historam, created the according Bin containing MAX value to sketch the histogram data. Based on these distribution chart, we can draw the conclusion that the data is right-skewed and Median is the value to better representing the data generally.
 
 


 
