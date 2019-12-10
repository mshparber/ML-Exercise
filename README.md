# ML Exercise
Dear Candidate!

In this exercise you will be helping the "Keshev&Rikuz Inc." company to better understand their customers' behavior.  

The company has developed an App that improves customers' concentration skills. The App is a timed challenge game.  
Customers need to improve the completion time without being distracted: the faster - the better.  

The Data:  
https://1drv.ms/u/s!AoP_9ampPIT7yC0iQayj6wyyhxYh?e=GyCtxw  
For this exercise you have 2 files:  
1. PlayData - this file includes the results of every game played by each customer. Maximum - one game a day allowed.
Only the data of the customers that were active on 2019-08-01 is shown, including their history.  
The columns:  
 - CustomerID  
 - DayNumber - sequence of the days played. Starts with 1 for every customer  
 - Seconds - how many seconds it took to complete the game on that day  
2. CustomerData - this file contains information about the customers that were active on '2019-08-01'  
The columns:  
 - CustomerID  
 - Gender  
 - Platform: the App can be used on PC or on Mobile devices  
 - ActivePeriodNumber: if a customer doesn't play a game for one day - he/she is considered a churned customer for that Period.  
   If he/she resumes playing after a churn period, than ActivePeriodNumber is increased by 1.  
   So the Customer with ActivePeriodNumber = 3 means that this is his/hers third Period using the app.  
   In the PlayData file there is an information for the last ActivePeriod only.  
 - First_Try_Ever_Seconds: the result in seconds for the first completion of the game ever (in the first Active Period)  
 - Will_Churn: 1 - if a customer will churn (stop using the app) in the next week (till '2019-08-08'). 0 - if no churn.  

You have two missions:
1. Create customers' profiles based on their behavior: game statistics and attributes
2. Predict which customers are likely to churn

The company is particularly interested in their Mobile devices customers' behavior, and not so much for PC users.

You are free to use any algorithms / libraries you find useful and make any reasonable assumptions.  
You are requested to show and explain your results in a "management friendly" way.

For your exercise, please use Google Colab notebook if possible.  

If you have any questions, please feel free to contact me @:  
0528388384  
michael@wis2biz.com  
  
Best of luck and enjoy!  
Michael Shparber
