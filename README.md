# An analysis of kickstarter Project
## Overview of Project
Louise, an upcoming playwright,who wants to start a crowdfunding campaign to help fund her play 'fever'. The basic idea of this project is to help Louise by organising, sorting and analysing the crwodfunding data of kickstarters campaings to determine whether there are specific factors that make the campaign successful.

### Purpose 
The purpose of this project is to help Louise with the insights from the Kickstarter data analysis which could help her to set up her campaign from start to finish.

## Analysis and Challenges
To start the analysis, the data has been sorted,and organised. There are different set of analysis done in this dataset to help Louise plan her campaign.
1. Outcomes based on Parent category
2. Outcomes based on Sub category
3. Outcomes based on Launch date
4. Outcomes based on Goals
5. The measure of central tendency and spread
6. Outliers

For these analysis, the raw kickstarter data was sorted, filtered and formatted accordingly. New columns such as, Percentage funding, Average donation, Category and subcategories were created from raw data. 

### Analysis of Outcomes Based on Launch Date
The analysis of outcomes based on Launch date will be helpful in finding which month of the year has most successful campaign in 'theatre' category. For this analysis, Pivot table and pivot chart with the Launch date in the legend and outcomes in the series, with the parent category in filter. 

<img width="420" alt="Theatre_outcomes_vs_Launch" src="https://user-images.githubusercontent.com/108298416/176965628-82c7538d-8e59-4778-948c-008125c090aa.png">

### Analysis of Outcomes Based on Goals
This Analysis helps to visualize the percentage of successful,failed and canceled plays based on funding goals.For this analysis, the percentage of outcomes were calculated for Goal fund ranges. The analysis was performed by creating pivot table and pivot chart, with the goal in rows and the sum of percentage of outcomes in the columns. 

<img width="585" alt="Outcomes_vs_Goals" src="https://user-images.githubusercontent.com/108298416/176965720-e9e38e7c-2844-43ea-a225-4aaf8f899b2c.png">

### Challenges and Difficulties Encountered
For performing the analysis of outcomes based on Launch date and outcomes based on goals, launch dates and years were required. In kickstarter data,Launch and end dates were not in a readable format. The data were in unixtimestamps format and we can confirm this by using https://www.epochconverter.com/ to find the data type. The unixtimestamps in kickstarter data had to be converted to actual dates by using the formula  =(((Unixtimestamp/60)/60)/24)+DATE(1970,1,1)

## Results
### Conclsions about the Outcomes based on Launch Date
* The pivot chart shows that the theatre category campains which were launched on the months of May and June were successful
* Overall, the campaigns which were launched on the month of May were more successful and the campaigns launched in the month of december were less successful based on the outcomes. 

### Conclusion about the Outcomes based on Goals
The results shows that, less than $1000 funding goal have better success percentage rate

## Other possible tables and/or graphs that we could create
* We could create outliers chart using box and whisker chart to find descriptive statistics for all the categories and countries separately
* We could use Vlookup and Hlookup to lookup any value for a specific campaign
* We could create a pivot table and pivot chart for outcomes based on subcategories
![image](https://user-images.githubusercontent.com/108298416/176961724-22248148-fffc-4eba-bb9a-ab2d9def4d3f.png)




