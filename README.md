
# Toilet usage monitoring 

PROBLEM SATEMENT
India has the largest number of people open defecation nearly 490 million or one third of its population. This is more prevalent in rural house hold where statistically 55.4% of the population contributes to open defecation. Although the government has built in a lot of community as well as group toilets in accordance to the ‘Swachh Bharat’ initiative, the situation has scarcely improved.
The reasons attributed to this is lack of motivation amongst people, a monitoring agency to make sure the community and group toilets are used, lack of immediate repair of toilets in case of breakdown and lack of sanitation. Although manual surveys are done to look into the usage and conditions of the toilets, the surveys take a year to complete and repairs also take a long time to be corrected.Hence an efficient toilet monitoring strategy has been proposed to reduce open defecation in India.

IR SENSOR PROGRAM
Read the IR proximity sensor data and upon triggering, note the current time using millis() function. We find the difference in time in the detection of left and right sensors to get the direction of motion at the entrance of toilets.

REGRESSION PROGRAM
The data obtained from the sensors are stored in Thingspeak cloud.This data is usually has a lot of irregularities.Hence a best fit curve is obtained.The the local maximas and minimas are found out.The last maxima or minima is considered as after that the data is usually considered.The data after the last maxima or minima is fitted into a straight line and the gradient is found.If gradient is positive then there is no problem else there is a failure.
