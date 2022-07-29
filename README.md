# Kickstarting with Excel

## Overview of Project

### Purpose
Louise's own play called "Fever" has came close to the goal established in quick time. The purpose of this project is to help give Louise insight on how similar theater and play campaigns succeded, failed, or even canceled based on their launch date and funding goals.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
#### Pivot Table
The first step to find out the outcomes based on launch date is to create a pivot table. A pivot table is useful in this instance because it can provide a summary of our data and give us insight based on the data we use.

![Outcome Based on Launch Date Pivot Table](https://github.com/40super/kickstarter-analysis/blob/main/resource/Pivot_Table_Outcome.png?raw=true)

Looking at the Pivot table, the information on how many campaign were successful, failed, and canceled on a monthly basis is showned. Additionally, this pivot table is filtered to only show the campaigns that are only of the theater category. To get a better understanding of the table, creating a visual graph can help see trends and any other findings.

![Outcome Based on Launch Date](https://github.com/40super/kickstarter-analysis/blob/main/resource/Theater_Outcomes_vs_Launch.png?raw=true)

The graph shown above provide information on trends of campaigns results on a monthly basis.

### Analysis of Outcomes Based on Goals

The next analysis that was performed was on the outcomes based on goals. The objective of this analysis was to count the number of successful, failed, and canceled campaigns based on the goal amount of the campaign. By using the excel function `COUNTIF()`, it performs conditional checks to count only the campaigns that fits the parameter given. In this case, the goal range and the sub-category "plays".

![Outcome Based on Goals](https://github.com/40super/kickstarter-analysis/blob/main/resource/Outcomes_vs_Goals.png?raw=true)

As a result, this graph shows the percentage of campaigns outcome based on the goal amount.

### Challenges and Difficulties Encountered
During the challenge I did not have many difficulties due to having some knowledge of excel. The only difficulties I had, was troubleshooting any mistakes I made such as forgetting to apply filters to get the appropiate data table. Furthermore, I think a challenge that can be encountered is if the data was of larger scale, applying certain functions and adding custom parameters to each column can be tedious.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
* Based on the Outcomes based on Launch Date graph, the best time to launch a campaign is in May. 
* Another conclusion is that October would be the worst time to launch a campaign due to the higher failure rate compare to the successful rate within the same time.

- What can you conclude about the Outcomes based on Goals?
* Based on the graph, goals between 20000 to 30000 had a higher percentage of failing than succeeding.
* 
- What are some limitations of this dataset?

Some limitation that I noticed while using this dataset is the data distribution for certain categories. For example, looking at the outcome based on goals graph, goals with a monetary value greater than 20000 had less than 10 entries in majority of the goal range while goals under 20000 had greater amount of entries. This can cause entries that have higher goals to have higher weightage which can skew the data.

- What are some other possible tables and/or graphs that we could create?

I think a good graph that can be useful to get a better understanding of the data is the box and whisker plot. Using this graph can give an understanding of the amount of outlier and also see if the data is distributed normally.
