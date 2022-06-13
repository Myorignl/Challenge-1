# Challenge-1
Assignment
# Kickstarting with Excel

## Overview of Project

    Louise is an artist/director who is working to produce her play *Fever*. Production of the play include cost which requires financial support. Louise used several fundraising campaigns to acquire funding for her play which had an estimated cost of $12,000. She came close to her goal, and now is researching the campaign efforts to gain insight on each campaigns effectiveness based on launched dates and funding goals. Louise is also researching what times of the year are the best to debut her play based on trends.
    
## Analysis and Challenges

    In order to assist Louise we analyzed the different campaigns styles used. Which times of the year provided a higher success rates to premier her play at theaters and which country had the greatest success. Challenges that were encountered included Excel crashing and losing the data due to failure to save progress and troubleshooting formulas used to identify error. Once challenges were address progress followed. 

### Analysis of Outcomes Based on Launch Date
To analyze the outcomes based on launch date I used the starter data sheet provided. To obtain the data I used a pivot table. The pivot table was set with outcomes in the columns, Rows with date conversion which once in the table split into years and months, the value was set as counts of the outcomes. The filters were set as Parent Category and the data was filtered for theater. Once calculated a line chart was created to provide a visual representation of the numbers. 

### Analysis of Outcomes Based on Goals

To analyze the outcomes based on goals I used the starter data sheet provided. The data was sorted by Plays and Outcome status (Successful l and Failed). Once sorted a table was created to include the Goal range with a column for the number of successful and failures per set range. The following columns included the total and the percentages. A column for cancellations was included however there were no cancellations in the data set. 

### Challenges and Difficulties Encountered

Challenges encountered included an error in the count if formula used. I included an equal to in the less than 1000 section (COUNTIF (K:K,"<=1000") this increased the numbers, the line chart did not match the example given in the excessive, It took a while to find the error. 

## Results

The analysis of the data was done to answer which fundraising efforts fared best. Conducting the analysis using the tables provided an immediate response to this.  Based on the analysis we can tell that the most successful months to debut the play and what are realistic goals using the data available. 

- What are two conclusions you can draw about the Outcomes based on Launch Date?
In the outcomes by launch date we can see that the most successful plays took place in the summer, May, June and July. A play is more likely to be cancelled in January. 

- What can you conclude about the Outcomes based on Goals?
When reviewing the data based on goals the data shows that campaigns set as less than $1,000 have a higher likelihood of success however the  $15,000 -  19,000 are a tossup with equal chance of failure or success.

- What are some limitations of this dataset?
There are some limitations encountered in the data, these include the population demographics based in the type of play that Louise is trying to produce. This would include population age, gender and income. 

- What are some other possible tables and/or graphs that we could create? 
Other graphs that could be created based on the data available include the country where the plays were most successful. The subcategories could also be used to determine which type of play was more successful and in which country. The data set includes categories like food, journalism, technology etc.  The data can be manipulated to analyze any of these categories based on interest. 

[Kickstarter_Challenge.zip](https://github.com/Myorignl/Challenge-1/files/8893100/Kickstarter_Challenge.zip)
![Outcomes_vs_Goals png](https://user-images.githubusercontent.com/104601282/173407749-a4f7dd97-0b3b-4461-9431-d97d9403df52.png)
![Theater_Outcomes_vs_ Launch png](https://user-images.githubusercontent.com/104601282/173407755-50e8ec3b-f650-4251-95c3-8c44138fd996.png)
