# Crowdfunding Data Analysis

Crowdfunding platforms like Kickstarter and Indiegogo have been growing in success and popularity since the late 2000s. From independent content creators to famous celebrities, more and more people are using crowdfunding to launch new products and generate buzz, but not every project has found success.

This repository contains Excel files and analysis scripts for conducting a comprehensive analysis of crowdfunding data. The dataset consists of 1,000 sample projects from crowdfunding platforms like Kickstarter and Indiegogo. The analysis aims to uncover trends and insights that can help understand the factors contributing to the success or failure of crowdfunding campaigns.

### Folder Structure
- data: Contains the Excel file with the sample crowdfunding project data.
- analysis: Contains scripts and Excel files for conducting various analyses.


## Analysis Tasks
Crowdfunding Goal Analysis
### Description:
This analysis focuses on understanding the relationship between the crowdfunding goal amount and the success, failure, or cancellation of projects.

![image](https://github.com/ZinDaria/Excel-challenge-/assets/141193973/8cbc7627-255a-497c-bd74-b326d41d869b)


![image](https://github.com/ZinDaria/Excel-challenge-/assets/141193973/ccb8467d-63ed-4b5e-8234-557f5fcb0efe)

### Steps:

1. Create a new sheet with columns for goal range, number successful, number failed, number canceled, total projects, percentage successful, percentage failed, and percentage canceled.
2. Populate the goal column with specified ranges.
3. Use COUNTIFS() formula to count successful, failed, and canceled projects within each goal range.
4. Populate number successful, number failed, and number canceled columns.
5. Calculate total projects column.
6. Calculate percentage successful, percentage failed, and percentage canceled.
7. Create a line chart to visualize the relationship between goal amount and success/failure/cancellation rates.

![image](https://github.com/ZinDaria/Excel-challenge-/assets/141193973/d49801fe-068f-4343-880e-5d5852e55308)


![image](https://github.com/ZinDaria/Excel-challenge-/assets/141193973/22fbfdac-fb2a-44bb-bc0d-7565a507c55e)


## Statistical Analysis
### Description:
This analysis aims to characterize the number of backers for successful and unsuccessful crowdfunding campaigns.

### Steps:

1. Create a new worksheet with columns for the number of backers of successful and unsuccessful campaigns.

![image](https://github.com/ZinDaria/Excel-challenge-/assets/141193973/0a82328c-8ee4-43b2-a50d-fd75160e3919)


2. Evaluate summary statistics for successful campaigns: mean, median, minimum, maximum, variance, and standard deviation.
3. Repeat step 2 for unsuccessful campaigns.
4. Determine whether mean or median better summarizes the data.
5. Determine if there's more variability with successful or unsuccessful campaigns and explain the reasoning.
