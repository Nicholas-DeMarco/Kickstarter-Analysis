# An Analysis of Kickstarter Campaigns
Performing analysis on Kickstarter data to uncover trends

  The purpose of this analysis was to find out how successful or unsuccessful campaigns are based on their goal amount and the months that they are launched. There were many obstacles to overcome while trying to uncover the trend lines based on many different scenarios. But in the end I believe we found the best and worst outcomes.

Explanation of Analysis

  For the first part of this analysis we wanted to uncover how successful or unsuccessful the theater outcomes were based on the date they were launched. I created a pivot table to better display and layout our results. With that pivot table, I was able to create a pivot chart which was able to break down the numbers and make it much easier to read.
  
  Attached is a picture of the pivot chart that I was able to create by using the data from the pivot table.
![Screenshot (13)](https://user-images.githubusercontent.com/114521887/195668993-ee2cb629-3686-42c6-9dd2-eeaf497e7295.png)

  The second part of this analysis was to find out howe successful or unsuccessful plays were based on the goal that was set for them. This part of the analysis was much more difficult, as I ran into many problems trying to figure out the right code to use to make our outcomes print correctly. After trying and failing many different solutions, with a little help I was able to find my way into the right code that gave us the best possible results.
  
  =COUNTIFS(Kickstarter!$D:$D,">=1000",Kickstarter!$D:$D,"<=4999",Kickstarter!$F:$F,"successful",Kickstarter!$R:$R,"plays")
  
  By using the code included above, we were able to find out that there were 388 successful outcomes based on goal, between a goal amount of $1,000 and $4,999, which was the most out of any range of set goal amounts. This code was printed into cell B3, included is a picture to show the detail.
  
  ![Screenshot (14)](https://user-images.githubusercontent.com/114521887/195670929-fadbf976-07e8-4571-9e31-dd7935bf64d7.png)
  
  Alternatively, in the same goal range of $1,000 to $4,999, we also find the most number of failed outcomes based on goal, coming in at 146. Attached is the code and a screenshot that I used to find out answers. This formula was plugged into cell C3:
  
  =COUNTIFS(Kickstarter!$D:$D,">=1000",Kickstarter!$D:$D,"<=4999",Kickstarter!$F:$F,"failed",Kickstarter!$R:$R,"plays")
  
  Ands this is the screenshot:
  
  ![Screenshot (15)](https://user-images.githubusercontent.com/114521887/195671787-6735683c-6327-4e9f-b53c-45b10a896fd9.png)
  
  
 Final Analysis
 
  To wrap this up, let us look at some of our conclusions. One absolute conclusion that we can make is that the outcome of theatres based on their launch dates between the months of May, June, and July are the most successful. Another conclusion that I believe we can make is that failed outcomes of theatres based on the month they were launched stay pretty level across the year, while seeing a minor spike in May, June, and July as well.
  
  One final conclusion that we can make looking at our data from Outcomes Based on Goal is that our highest percentage of successful outcomes are with goals that are less than $1,000, coming in at a 75% success rate!
