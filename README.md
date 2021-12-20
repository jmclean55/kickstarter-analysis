# An Analysis of Kickstarter Campaigns
Kickstarter projects across the globe for different types of plays and musicals
![image](https://user-images.githubusercontent.com/95198079/145744059-b65fa074-b943-4da1-8109-f6cf983d1f1e.png)
This image shows us the outcomes based on the launch dates. 
![image](https://user-images.githubusercontent.com/95198079/145744191-58dd2105-4390-42cf-a646-2584441dc19f.png)
This image is showing the successful plays charted with the unsuccessful as a stacked column.
Based on our findings, Louise should lower her target goal and look to fund new plays and musicals that are cheaper.


# Kickstarting with Excel

## Overview of Project

### The purpose of the KickStarter Challenge analysis was to study different potential theatre projects, the funds to get them, and if the different projects achieved their funding goals.  The study was performed on different subcategories of theatre projects across the globe with data collected during every month of the year.  The purpose of the study was to find what theatre projects had success and which failed based off launch dates, funding goals, and location.  

## Analysis and Challenges
###  To collect the data for success and failure based off funding, we first determined what the goal for each individual project was.  If the funding was not met, it was deemed failed.  
#### By using pivot charts, I was able to determine the success of different types of theatre Kickstarters based off the month they were launched.  Judging by the attached graph, we can determine that theatres Kickstarters in the summer not only reach their funding to get off the ground, but also tend to have more success than those in the winter months.  I ran in to a few challenges with this pivot chart, sorting which to field to go into the specific areas gave me problems and I was unable to achieve the matching chart that was required.  My biggest situation came with bringing the months to the forefront of the row labels.  
### Analysis of Outcomes Based on Launch Date
####![Theatre Outcomes Based on Launch Date](/Users/jeffreymclean/Desktop/Jeff School 21:22 Work/Resources/Theatre_0utcomes_vs_Launch.png)
#### For plays, I separated them based off their currency goals and was able to group them by increasing amounts depending on the specific goal.  The function I used for this chart was the COUNTIFS() formula.  From this data, I was able to gather that the cheaper the play money goal was, the more projects there were.  They also were the projects that were usually more successful.  Although some of the larger funded projects were successful, the sample size is too small to determine how they would do at the numbers that cheaper plays produced at.  Based off the data of the plays, one thing was consistent; plays did not get canceled.  Once the total funding reached the $20000 mark, the plays were more inclined to fail than succeed. The main challenges that I encountered was how to properly use the COUNTIFS formula, I ran into many errors mostly because I was missing/unsure how to enter if they were successful, failed or canceled.  Thank you to the office hours for helping me learn that segment of the formula.  ### Analysis of Outcomes Based on Goals
####![Outcomes vs Goals](/Users/jeffreymclean/Desktop/Jeff School 21:22 Work/Resources/0utcomes_vs_Goals.png)

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
###Conclusions we can draw about the Theater Outcomes by Launch Date graph first and foremost is the success in funding that theatre performances had in the summer compared to the winter months. Another conclusion that is evident from this graph is the grand total amount of theatre Kickstarters attempted in the summer.  This shows that not only was there more interest from the creators of the theatre events but also increasingly more interest from those funding compared to December and January. 
- What can you conclude about the Outcomes based on Goals?
###Conclusions we can draw from the ‘Outcomes Based on Goals’ chart is that the sample size really decreases as the funding grows in costs.  There is an inverse linear relationship on the graph but once the funding reaches the $20000 mark, we are unable to make any more conclusions based on sample size alone.  One conclusion that can be made is there appears to be a hesitancy to create larger funded plays.  The data shows us that the smaller more affordable plays up to $4999 are successful nearly 75% of the time.
- What are some limitations of this dataset?
###One of the biggest limitations in the data that stood out to me was that there was not enough of a sample size to really make a strong conclusion for the larger funded projects.  Based off that, another limitation was not knowing where in these certain countries the higher funded projects were attempted to be held.  For example, a play in New York City or London would have an easier path to funding a $200,000 project compared to a similarly priced projected attempted to be held in Des Moines or Newcastle.  Accounting for the relative standard of living would help branch out the success and fail rate of the overall dataset.  Along with location, how many people worked per campaign of each project? Was it the same number per or did they vary throughout?  Projects that had 10+ people working a campaign compared to a project with only 1 person is more likely to bring in more funding and see more of a success rate.  
- What are some other possible tables and/or graphs that we could create?
###Based off the thinking in the previous paragraph, one chart I would be interesting in seeing is a specific type of parent category filtered and graphed through countries.  With this graph, I’d potentially like to see the mean of the average income per Country and what cities the projects are being funded in.  Using this data will be able to help get advanced results on where the larger funded projects are coming from which will allow more educated assumptions based on more intricate data. 
