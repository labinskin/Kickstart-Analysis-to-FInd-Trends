# An Analysis of Kickstarter Campaigns
## Kickstarter Analysis

## Overview

**Purpose of the Project**

My friend Louise wants to launch a Kickstarter campaign for a play she wants to put on, *Fever*. *Fever* came close to reaching its fundraising goal in a short amount of time. Now, Louise has contacted me to analyze Kickstarter data that was collected from 2009 to 2017 to determine how different campaigns fared in relation to their launch dates and their fundraising goals. The data set is large, including data on the goal, amount pledged, country, date launched/completed, and number of backers, being among the data most pertinent to this analysis. This data includes information on plays and other theatrical campaigns, as well as campaigns for books, television, and music. Louise would like me to analyze the data so she has a better understanding of the fundamentals that might shape a successful, or unsuccessful, Kickstarter campaign. She believes it is critical to understand when campaigns are launched, the type of campaign, including unique campaigns, and how campaigns for plays, her interest, faired. This analysis is intended to help Louise understand the fundamentals of Kickstarter campaigns, provide insight about launch dates, the campaign goal, and their influence in the success or failure of play campaigns.



## Analysis and Challenges

**Analysis**

This section will overview some of the basics in preparing the data for analysis. 

With a large dataset, one of the keys to a successful analysis was filtering the data to better match Louise's goal. This filtering included creating Parent Category and Subcategory sorting tools that allowed me to focus my analysis on theater campaigns, and to dive even deeper with a sharper focus on only plays. Additionally, extra columns were added to convert the unix timestamps to regular dates, for a clear understanding of when campaigns launched and concluded, and a year column was included for quicker reference and ease of sorting in pivot tables.

From there, my first major analysis was to filter the data, examining all theater related campaigns over the eight year period. Next, a pivot table was created, showing the successful, failed, and canceled campaign totals for each month. <img src="https://github.com/labinskin/Kickstart-Analysis-to-Find-Trends/blob/main/Pivot%20Table.png" />The data would allow Louise to see which months, if any, launched the most campaigns, which months were more successful, and which ones were not. Drawing on the data in this pivot chart, a clear visualization of the data was created in a line graph (see below in the results section for the chart and discussion).

The second major analysis presented in this report was the collection and analysis of data pertaining to the funding goal amount of plays. Using the `=CountIfs`function in Excel, data was transferred from the main spreadsheet to a new one. The data was arranged in rows and categories. The rows consisted of possible goal amounts starting with less than $1,000, then $1,000 to $4,999, and increasing in increments of $4,999 until the last category of $50,000 and above. The columns consisted of `=CountIfs`that totaled the number of successful, failed, and canceled campaigns. Another column totaled the projects with the `=Sum`function. And the last three columns calculated the percentage of successful, failed, and canceled campaigns. ![Outcomes Chart](https://github.com/labinskin/Kickstart-Analysis-to-Find-Trends/blob/main/Outcomes%20Chart.png)This allows Louise and us to examine if there are goals amounts that are more or less successful. A full visualization of the data is presented below in the results.

## Results
