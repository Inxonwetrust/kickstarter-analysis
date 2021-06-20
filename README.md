# Kickstarting with Excel

## Overview of Project

### The purpose of this project was to perform technical analysis in Excel using Pivot tables, CountIFs, and visual charts to find trends within the data.

## Analysis and Challenges

### **Analysis of Theater by month**
First I had to delimit the category and subcategory to get separate columns for more precise analyzation after this was done I had to convert the unix timestamp into normal date format. Once this was completed I could create a pivot table that filtered by year and the parent category theater. I was able to get a breakdown of outcomes by month and assess how theaters did depending on the month ![Theater_Outcomes](https://user-images.githubusercontent.com/85142929/122662750-0d484000-d15b-11eb-9a6f-44aa4363fd83.png)Based on the picture the most successful theater outcomes occur in the summer months (May-Aug) since these points hold the greatest area between the two curves.

### **Analysis of Outcomes Based on Goals**
After the Goal amounts were given I had to create a CountIF statement that included the given goal amount as well as filtering the data to "plays" only and the given outcome in the table. Once the data was gathered I used the total projects and the given outcome to create a percentage based on that outcome. 
![Outcomes_vs_Goals](https://user-images.githubusercontent.com/85142929/122662748-0cafa980-d15b-11eb-91ec-86604d92ade1.png) Based on the graph fundraising goals of success and failure are inversely related depending upon the dollar amount

### **Challenges and Difficulties Encountered**
I created the first CountIF with pledged not goals so I created the wrong technical analysis at first.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
Summer months have the greatest number of play productions. The probability of success for a play in December is roughly the same as the probability for failure. 

- What can you conclude about the Outcomes based on Goals?
The greatest percentage of play failures come from fundraising goals of 45k plus. Play fundraising goals of 10k or less are the most likely to succeed making a need for smaller goal amounts to be successful.

- What are some limitations of this dataset?
The data could be incomplete. How was the data gathered? Is it accurate? Is this data an accurate sample of the population.

- What are some other possible tables and/or graphs that we could create?
Stacked bar graph for the Theater outcomes by launch date.

