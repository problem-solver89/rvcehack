# Toilet usage monitoring 

AIM: to find the trend of the public toilet usage and help the government in efficient maintenance of the same. 

Read the IR proximity sensor data and upon triggering, note the current time using millis() function. We find the difference in time in the detection of left and right sensors to get the direction of motion at the entrance of toilets.
Use regression analysis and curve fitting to determine the trend of the usage to enable taking necessary measures if the usage is declining. 
The data is uploaded to the cloud at regular intervals for monitoring. 
