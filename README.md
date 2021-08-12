# J124 Final Project: Data Analysis & Visualization of Where it Pays to Attend College
## By Layal Younan
### Data Analysis Process
* Download the “Where it Pays to Attend College” [data sheets](https://www.kaggle.com/wsj/college-salaries) as .csv files, upload it to Google Drive, and open it with Google Sheets. <br>

*The following are five questions and step-by-step answers based on the data sets:* <br>
<br>

**Question 1: _Which undergraduate majors has the highest percent change from starting to mid-career (median) salary, and which has the lowest? Include the percent change amount._** <br>

**Step-by-step answer:**
1. Sort the column "Percent change from Starting to Mid-Career Salary" in the "degrees-that-pay-back" data sheet from Z->A (or greatest to smallest) to find the highest percent change from starting to mid-career (median) salary, like so: <br>
!['Highest Percent Change from Starting to Mid-Career Salary','A Google Sheet representing the undergraduate majors in the first column and the percent change of their starting to mid-career (median) salary in the fourth column. The column "Percent change from mid-career 10th to 90th percentile" has been filtered and sorted from highest to lowest in order to illustrate the highest percent change.'](/Screenshot-Highest-Percent-Change.jpg)
* **As shown, math and philosophy have the highest percent change from starting to mid-career (median) salary with a 103.5% change.**
2. Unsort the column now.
3. Sort the column "Percent change from Starting to Mid-Career Salary" in the "degrees-that-pay-back" data sheet from A->Z (or smallest to greatest) to find the lowest percent change of starting to mid-career (median) salary, like so: <br>
!['Lowest Percent Change from Starting to Mid-Career Salary','A Google Sheet representing the undergraduate majors in the first column and the percent change from their starting to mid-career (median) salary in the fourth column. The column "Percent change from mid-career 10th to 90th percentile" has been filtered and sorted from lowest to highest in order to illustrate the lowest percent change.'](/Screenshot-lowest-percent-change.jpg)
* **As shown, physician assistant has the lowest percent change from starting to mid-career (median) salary with a 23.4% change.** <br>
<br>

**Question 2: _Of the schools that had data, which three schools have the highest percent change from mid-career 10th percentile to mid-career 90th percentile? Include the percent change amount._** <br>

**Step-by-step answer:**
1. Create a filter on the "salaries-by-region" data set. On the column "Mid-Career 10th Percentile Salary" filter out "N/A" in order to only see the schools that have data.
2. Title the first empty column, which is the ninth column, "Percent change from mid-career 10th to 90th percentile" and bold it.
3. In the new column, "Percent change from mid-career 10th to 90th percentile," subtract the "Mid-Career 10th Percentile Salary" column from the "Mid-Careeer 90th Percentile Salary" column, then divide that by the "Mid-Career 10th Percentile Salary" column and multiply it by 100, or hit the percent symbol to automatically do so. This will give you the percent change.
4. The data set should appear as so:
!['Percent Change from Mid-Career 10th to 90th Percentile in "Salaries-by-Region" Data Set','A Google Sheet representing the mid-career 10th percentile in the "Mid-Career 10th Percentile Salary" column and the mid-career 90th percentile in the "Mid-Career 90th Percentile Salary" column. A filter has been applied to remove all of the "N/A"s in the "Mid-Career 10th Percentile Salary" column. The "Percent change from mid-career 10th to 90th percentile" column is presented to illustrate that change in salary from 10th to 90th percentile. The values as percentages and formula are shown in the picture.'](Screenshot-percentchange-10-90.jpg)
5. Sort the "Percent change from mid-career 10th to 90th percentile" column from Z->A (or greatest to smallest) to find the highest percent change from mid-career 10th to 90th percentile, like so: <br>
!['Highest Percent Change from Mid-Career 10th to 90th Percentile in "Salaries-by-Region" Data Set','A Google Sheet representing the mid-career 10th percentile in the "Mid-Career 10th Percentile Salary" column, the mid-career 90th percentile in the "Mid-Career 90th Percentile Salary" column, and the percent change from mid-career 10th to 90th percentile in the "Percent change from mid-career 10th to 90th percentile" column. The "Percent change from mid-career 10th to 90th percentile" column was sorted from highest to lowest to find the top three schools with the highest percent change from mid-career 10th to 90th percentile. Yale University, State University of New York (SUNY) at Fredonia, and Harvard University were the top three, with 462.07%, 451.83%, and 425.55% change, respectively.'](Screenshot-highest-10-90.jpg)
* **As shown, Yale University, State University of New York (SUNY) at Fredonia, and Harvard University have the highest percent change from mid-career 10th to 90th percentile, with 462.07%, 451.83%, and 425.55%, respectively.** <br>
<br>

**Question 3: _Which five undergraduate majors have the highest percent change from mid-career 10th percentile to mid-career 90th percentile? Include the percent change amount._** <br>

**Step-by-step answer:**
1. On the "degrees-that-pay-back" data set, title the first empty column "Percent change from mid-career 10th to 90th percentile" and bold it.
2. In the new column, "Percent change from mid-career 10th to 90th percentile," subtract the "Mid-Career 10th Percentile Salary" column from the "Mid-Careeer 90th Percentile Salary" column, then divide that by the "Mid-Career 10th Percentile Salary" column and multiply it by 100, or hit the percent symbol to automatically do so to find the percent change. 
3. The data set should appear as so:
!['Percent Change from Mid-Career 10th to 90th Percentile in the "Degrees-that-Pay-Back" Data Set','A Google Sheet representing the mid-career 10th percentile in the "Mid-Career 10th Percentile Salary" column, the mid-career 90th percentile in the "Mid-Career 90th Percentile Salary" column, and the percent change from mid-career 10th to 90th percentile in the "Percent change from mid-career 10th to 90th percentile" column. The values as percentages and formula are shown in the picture.'](Screenshot-percentchange-major-10-90.jpg)
4. Sort the "Percent change from mid-career 10th to 90th percentile" column from Z->A (or greatest to smallest) to find the highest percent change from mid-career 10th to 90th percentile, like so: <br>
!['Highest Percent Change from Mid-Career 10th to 90th Percentile in "Degrees-that-Pay-Back" Data Set','A Google Sheet representing the mid-career 10th percentile in the "Mid-Career 10th Percentile Salary" column, the mid-career 90th percentile in the "Mid-Career 90th Percentile Salary" column, and the percent change from mid-career 10th to 90th percentile in the "Percent change from mid-career 10th to 90th percentile" column. The "Percent change from mid-career 10th to 90th percentile" column was sorted from highest to lowest to find the top five undergraduate majors with the highest percent change from mid-career 10th to 90th percentile. Music, philosophy, art history, drama, and marketing were the top five, with 401.87%, 373.24%, 334.03%, 316.89%, and 315.68% change, respectively.'](Screenshot-highest-major-10-90.jpg)
* **As shown, music, philosophy, art history, drama, and marketing have the highest percent change from mid-career 10th to 90th percentile, with 401.87%, 373.24%, 334.03%, 316.89%, and 315.68%, respectively.** <br>
<br>

**Question 4: _What are the average starting median salaries for each region?_** <br>

**Step-by-step answer:**
1. On the "salaries-by-region" data set, create a pivot table.
2. On the pivot table, set the row to "Region" and add the average of "Starting Median Salary" as the value in order to observe the average starting median salaries for each region. It should appear as so:
!['Pivot Table of Average Starting Median Salaries Based on Region','A pivot table on Google Sheets with the rows being names of five different regions and the column being the average starting median salary for that region. The values are shown as amounts in dollars.'](Screenshot-pivot-table-region-avg-starting.jpg)
* **As shown, the average starting median salary is $51,032.14 for California, $44,225.35 for Midwestern, $48,496.00 for Northeastern, $44,521.52 for Southern, and $44,414.29 for Western.** <br>
<br>

**Question 5: _How many schools in each region have a mid-career median salary greater than or equal to $100,000?_** <br>

**Step-by-step answer:**
1. On the "salaries-by-region" data set, create a pivot table.
2. On the pivot table, set the row to "Region" and add the count of "School Name" as the value. Set a filter for "Mid-Career Median Salary" to be values greater than or equal to $100,000. This is so we find how many schools in each region have a mid-career median salary greater than or equal to $100,000.
!['Pivot Table of Number of Schools with Mid-Career Median Salaries Greater Than or Equal to $100,000 Based on Region','A pivot table on Google Sheets with the rows being names of five different regions and the column being the number of schools with mid-career median salaries greater than or equal to $100,000. The values are depicted as amount in dollars.'](Screenshot-pivot-table-region.jpg)
* **As shown, California has 9 schools, Midwestern has 3 schools, Northeastern has 26 schools, Southern has 8 schools, and Western has 1 school with a mid-career median salary greater than or equal to $100,000.** <br>
<br>

**Question 6: _Which undergraduate major has the highest starting median salary? Which has the highest mid-career median salary? Include the amount._** <br>

**Step-by-step answer:**
1. On the "degrees-that-pay-back" data set, sort the "Starting Median Salary" column from Z->A (or greatest to smallest) to find the highest starting median salary, like so:
!['Highest Starting Median Salary','A Google Sheet representing the starting median salaries in the "Starting Median Salary" column and the undergraduate majors associated with them in the "Undergraduate Major" column. The "Starting Median Salary" column was sorted from greatest to lowest to find the highest starting median salary. The first amount, or the greatest, that popped up is $74,000 tied to physician assistant. The rest of the majors and amounts are listed as well in descending order.'](Screenshot-starting-salary.jpg)
* **As shown, physician assistant has the highest starting median salary, with $74,300.**
2. Unsort the column now.
3. Sort the "Mid-Career Median Salary" column from Z->A (or greatest to smallest) to find the highest mid-career median salary, like so:
!['Highest Mid-Career Median Salary','A Google Sheet representing the mid-career median salaries in the "Mid-Career Median Salary" column and the undergraduate majors associated with them in the "Undergraduate Major" column. The "Mid-Career Median Salary" column was sorted from greatest to lowest to find the highest starting median salary. The first amount, or the greatest, that popped up is $107,000 tied to chemical engineering. The rest of the majors and amounts are listed as well in descending order.'](Screenshot-midcareer-salary.jpg)
* **As shown, chemical engineering has the highest mid-career median salary, with $107,000.**
<br>

### Story Summary and Sourcing

Based on the findings from the data provided by The Wall Street Journal, it is noteworthy how the starting median salaries and mid-career median salaries differ between majors but also within majors. For instance, physician assistants have the highest starting median salary, with $74,300, but this major experiences the lowest percent change from starting to mid-career salary, with only 23.4%. As such, starting median salaries can be misleading to students looking to solidify their major and career who want a high-paying job. Physician assistants start out the strongest, but chemical engineers have a much higher mid-career median salary, with $107,000. As chemical engineering has a starting median salary of $63,200, it experiences a 69.3% increase in the mid-career median salary. If we look further and observe the rest of the information provided for these majors, we see the mid-career 90th percentile for physician assistants is $124,000 while it is $194,000 for chemical engineers. This means that the starting median salary is not indicative of one’s ability to advance their salary. When someone is deciding on what major or career-path they want to choose, it is important to observe both the starting median salary and the mid-career median salary. Ultimately, if one’s priority is money in the long-run, one should solely focus on the undergraduate major with the highest mid-career median salary. However, the data set provided does not reveal the whole story. Different costs and benefits are provided for each undergraduate major that are not always tangible, and if they are they are sometimes excluded from the data, such as healthcare benefits or the cost of school. Not to mention, the data only provides salaries based on undergraduate majors; however, there are plenty of jobs with employees who did not attend college. <br>

As such, two additional sources to help guide students to make the best undergraduate decision for them would be ["The Value of a Bachelor's Degree" inforgraphic](https://pages.northeastern.edu/rs/558-EBH-425/images/BachelorComp_Infographic.pdf) created by Northeastern University and ["The ‘Indirect’ Costs at College Can Involve Nasty Surprises" report](https://www.nytimes.com/2020/08/07/your-money/college-costs-tuition.html) by The New York Times. "The Value of a Bachelor's Degree" infographic would be useful in writing this story because it would shine light on the the differences between having a job with a bachelor's degree and a job without one. It provides data in the form of statistics on various matters related to a career, such as data on unemployment, the impact of networking, and a sense of identity. This would help readers decide whether or not they want to earn a bachelor's degree before they jump ahead to deciding what major is right for them. Next, "The "Indirect' Costs at College Can Involve Nasty Surprises" report would complete the story because it informs readers of the costs of college that are not included in the tuition. This would help in calculating whether the cost of college will be worth the benefits that a certain undergraduate major will provide. Beyond those sources, I would also interview my friend Aida Mahfood (whose cell phone number is 818-303-4898) as she has been a physician assistant for a year, but started her college career with a different major. After taking time to decide what will benefit her, she chose to be a physician assistant, so I think hearing why she made that decision would be beneficial for others weighing the costs and benefits of the major with the lowest percent change from starting to mid-career median salary. Finally, I would also interview my friend Shivin Devgon (whose cell phone number is 714-875-2587) since he recently graduated from the University of California, Berkeley with an Electrical Engineering and Computer Science degree, which is one of the majors with the highest mid-career median salary. He could explain why he chose that major and the payoff it has given so far, as well as the cost put in to get there. <br>
<br>

## Data Visualizations

