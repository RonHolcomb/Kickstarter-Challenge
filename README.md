# Kickstartin With Excel

## Overview of the Project
The purpose of this project was to find the rate of success, failure, and cancelation of Theaters and Plays. We found the Theater outcomes based on launch dates and Play outcomes based on their goals. This gave us a better understanding of how to launch a successful kickstarter.

## Analysis and Challenges
### Analysis of Outcomes Based on Launch Dates
We analyzed the success of Theater kickstarters based on their launch date. We did this by taking all of the Theater kickstarters throught the year and broke it down month by month. We created a pivot table of all 12 months and counted how many kickstarters were successful, failed, or canceled for each month, as well as how many total kickstarters there were in that given month. Afterwards we created a line chart to easily display the data of the pivot table.
![image](https://github.com/RonHolcomb/Kickstarter-Challenge/blob/main/Theater_Outcomes_vs_Launch.png)

### Analysis of Outcomes Based on Goals
Next we analyzed kickstarters for plays based on the goal amount they set. This gave us an idea of what goal will have the highest percentage of success. We did this by creating a table with all the plays grouped by a range of goals for example, all plays with a goal less than $1000, all plays with a goal between $1000 and $4999 etc. We then counted how many of these plays in each range were suucessful, failed, or canceled, and how many plays total there were. Afterwards we were able to find the percentage of how many plays succeeded vs failed vs canceled. Once we were done we created another line chart to display this information.
![image](https://github.com/RonHolcomb/Kickstarter-Challenge/blob/main/Outcomes_vs_Goals.png)

### Challenges and Difficulties
Gathering data was proven difficult specifically for the plays outcome based on goals. Using the countifs function in excel did not give the results I wanted despite following the examples provided. Although it still made for great practice and displayed yet another useful function to gather very specific data. I was still able to gather at least some data to display in the line chart, and was proud that the theater based on launch date data came out perfectly.

## Results
The following are some Results/Conclusions we can make about the data that was captured
1. We found that the best time to launch a Theater Kickstarter is from April to June as there was a huge rise and peak of success, on the other hand we can conclude that October to December was the worst time to launch as failed kickstarters peaked in October and was almost equal to successful kickstarters in December meaning there is about a 50% chance of the kickstarter failing in that month
2. Despite my graph not being correct for Plays Kickstarters based on goals I can conclude that no plays were canceled, also I can conclude that plays with a goal betwenn $1000 and $4999 have a much higher percentage of success than failure making that a very optimal kickstarter goal to set
3. Overall the data was very limited only showing specific data for specific subcatagories. We only analyzed 2 out of the 43 subcatagories and only analyzed their outcomes based on the launch date and goals. This only gives us a time frame for Theater kickstarters, and a total amount of money needed for Plays kickstarters.
4. We could create hundreds of graphs/tables with the 43 different subcatagories in this worksheet. A useful one might be which subcatagory had the most successful kickstarter and which had the most failures based on goals, pledges, and backers. This would tell us what kind of kickstarter should we do if we want to have it be successful. We could also filter said data by location to find the best country to launch in.
