# J124 Final Project: Data Analysis & Visualization of Where it Pays to Attend College
## By Layal Younan
* Download the “Where it Pays to Attend College” [data sheets](https://www.kaggle.com/wsj/college-salaries) as .csv files, upload it to Google Drive, and open it with Google Sheets. <br>

*The following are five questions and step-by-step answers based on the data sets:* <br>
<br>

**Question 1: _Which undergraduate majors has the highest percent change from starting to mid-career (median) salary, and which has the lowest? Include the percent change amount._** <br>

**Step-by-step answer:**
1. Sort column D in the "degrees-that-pay-back" data sheet from Z->A to find the highest percent change from starting to mid-career (median) salary, like so: <br>
!['Highest Percent Change from Starting to Mid-Career Salary','A Google Sheet representing the undergraduate majors in column A and the percent change of their starting to mid-career (median) salary in column D. Column D has been filtered and sorted from highest to lowest in order to illustrate the highest percent change.'](/Screenshot-Highest-Percent-Change.jpg)
* **As shown, math and philosophy have the highest percent change from starting to mid-career (median) salary with a 103.5% change.**
2. Sort column D in the "degrees-that-pay-back" data sheet from A->Z to find the lowest percent change of starting to mid-career (median) salary, like so: <br>
!['Lowest Percent Change from Starting to Mid-Career Salary','A Google Sheet representing the undergraduate majors in column A and the percent change from their starting to mid-career (median) salary in column D. Column D has been filtered and sorted from lowest to highest in order to illustrate the lowest percent change.'](/Screenshot-lowest-percent-change.jpg)
* **As shown, physician assistant has the lowest percent change from starting to mid-career (median) salary with a 23.4% change.** <br>
<br>

**Question 2: _Of the schools that had data, which three schools have the highest percent change from mid-career 10th percentile to mid-career 90th percentile? Include the percent change amount._** <br>

**Step-by-step answer:**
1. Create a filter on the salaries-by-region data set. On column E filter out "N/A."
2. On box I2, type in "=((H2-E2)/E2)x100"
3. Double click the bottom right corner of box I2 so the rest of the boxes in column I get a value too.
4. Title I1 "Percent change from mid-career 10th to 90th percentile" and bold it. The data set should appear as so:
!['Percent change from mid-career 10th to 90th percentile','
