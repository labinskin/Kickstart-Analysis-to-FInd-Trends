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

Data Limitations**

There are a few limitations to the data that must be noted before moving onto the results and analysis. First, the dataset only includes data up to 2017. We are almost four full years past the last piece of data collected. In this time, the world has undergone and is in the midst of a global pandemic that has shifted our ability to engage in theater, especially plays. While some countries, including the United States, has begun a return to normalcy, the global pandemic could have changed the success/failure rate of Kickstarter campaigns, especially theater and plays. Additionally, economic hardship of many citizens around the globe might have effected the number of campaigns that get fully funded.

Second, there is little information about supporters outside of the average donation. More demographic information about supporters would be critical. What demographics typically support theater and play Kickstarter campaigns? Collecting and analyzing any demographic information about supporters might be critical in crafting and launching a successful campaign. There could be a specific demographic of donors that fund a majority of campaigns. Targeting this demographic could be critical in funding a campaign.

Third, does the genre of the play matter or influence its success or failure? Each play as a blurb, describing what takes place. But, there is no genre category. Could the content of the play influence the amount donated, effecting which plays succeed and fail?

Fourth, there is no information about advertising and social media campaigns to publicize the campaigns. Understanding how the organizers publicized the event and the reach these efforts have could be a factor in determining the success or failure of a campaign. If an organizer was able to publicize their campaign to a wide audience, they could garner many supporters and meet their goal. However, if a campaign was poorly publicized or relied on people searching and looking through the vast amount of Kickstarter campaigns to stumble upon theirs, with few people knowing it existed, could be another factor in its success or failure.

## Results
