# RestaurantSimulation
The restaurant will cater to three different kinds of customers, drive-through, eat-in and carryout.  I want the restaurant to have enough staff to handle peak load times during the day.  

I have uploaded an Excel file with 30 interarrival times (in minutes) that were observed from another restaurant.  You need to determine what distribution this data follows (create a frequency chart) and estimate the parameters (mean, standard deviation, and/or boundaries) of the distribution.  You will use these estimates for the drive-through customers and the walk-in customers for the model.  Sixty percent of the walk-in customers stay in the restaurant to eat.

The drive-through has two windows.  Cars arrive to the first window and place their order and pay for the food.  They pick up their order at the second window.  There is room for three cars two wait between the two windows.  There is room for seven cars to wait at the first window.  The time to place an order is 1 ± 0.5 minutes and the time spent getting food is 2 ± 0.5 minutes.  After the cars receive their food, they leave the restaurant.

The walk-in customers proceed to the cashier who takes their orders. The same cashier who takes the walk-in orders also takes the drive-through orders.  The service time at the cashier station is exponentially distributed with a mean of 2 minutes.  The wait time for getting their food is exponentially distributed with a mean of 2 minutes.  The restaurant has enough space for 7 people to wait at the cashier stand and 5 people can wait for their order.

The people who stay in the restaurant to eat proceed to the tables and the rest leave the system.  The eating time is normally distributed with a mean of 15 minutes and a standard deviation of two minutes.  The restaurant has 8 tables for people who decide to stay.

Prepare a simulation model that will help us decide how many people to staff in the drive-through area, the number of cashiers for the walk-in customers and the number of tables to have in the eating area.  

We have a service goal for both the drive-through and walk-in stations of the restaurant.  We want to keep the total time in system less than 15 minutes for the drive-through station, less than 20 minutes for the carryout people and less than 35 minutes for the eat-in people.   Find the staffing policy (and number of tables) that will meet our customer satisfaction levels.

You will write up your recommendations in the form of a report to me as the customer of this simulation project.  The report will include the following sections; objectives of the study, decisions to be made, description of the model, assumptions made in the model, experiments that were tested, and final recommendations.  Summarize the output from your model runs as an attachment.  Place a copy of your model and report in the drop box of Georgia View. 

This project is due on December 10th at midnight. You may work in teams on this assignment.  You will hand in one report per team and each member of a team will receive the same grade.
