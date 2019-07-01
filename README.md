# Data Exploration of PISA report: Relationships Between Student Performance, Socioeconomic Status and Internet Access
## by Alfredo Yigal Núñez Varillas


## Dataset

In this project, we will explore the data obtained in the PISA report of 2012. The database, which can be obtained [here](https://www.oecd.org/pisa/pisaproducts/pisa2012database-downloadabledata.htm), has information on 485490 students of 15 years from 65 countries worldwide. One of the most outstanding points of the PISA report is the amount of information that was collected. Not only basic data such as country, age and score was obtained; but rich and varied data, from quantity of books in the student's house, educational level of their parents, access to Internet, etc.


## PISA_Data_Wrangling.ipynb

This dataset is huge, so I did the Wrangling phase in an individual notebook called PISA_Data_Wrangling.ipynb. It is necessary to run that notebook in order to obtain a csv file with clean data that will be used in the data exploration phase.

Important information: There's 3 code cells commented in this notebook. This was done because we need to run those cells the first time we run the notebook, in order to get a pkl file specifying the column types of the csv. In the subsequent times that this notebook runs, it will no longer be necessary to run those cells, since we will have already had the pkl file.

The wrangling efforts were:
* Removing columns that weren't important for our analysis.
* Changing column names.
* Changing column types.
* Renaming columns' variables accordingly. For example 1 to 'Never' in column ST115Q01 (skip classes within school)
* Adding new columns: global_region, comb_core, ECS_level.

## Summary of Findings

Basically, my findings were:

1. Girls have on average higher scores in Reading than boys in every country that participated in the PISA Report.
2. Immigration Status doesn't seem to have a strong relationship with the students' performance.
3. Use of the Internet is related to higher scores, regardless of the ECS level.
4. Students who arrive late to school, skip classes within school or skip whole school days tend to have lower scores.
5. The lower the ECS level, the more students tend to skip whole school days.

## Key Insights for Presentation

My presentation will focus on all previous findings except the second point, as it didn't provide more interesting insights to discuss.

For this presentation, basically I added titles and labels and set a unique color (if the color wasn't an indicator) for all charts. Likewise, I verified that the graphics were visually ordered, with no text on top of the plots, titles no too big nor too small, etc.

This polishing were made in the Data Exploration notebook. Originally, I didn't make any changes to the plots I obtained while working on this project, as I understood what was going on.
