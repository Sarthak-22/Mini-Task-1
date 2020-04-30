### Project 15 - TRAFFIC LIGHT INFORMATION SYSTEM

__Description__ - 

 A Traffic Light Information System  lets the driver know at which speed he needs to drive in order to get at the junction and pass the green light without exceeding the maximum speed limit. Along with that, when the driver has to wait for the inevitable red light, it lets him know when the light is about to turn green. The smart traffic light would then send data to an online database. The GPS or any application in the phone can be used to retrieve this data which calculates the desired speed to pass the signal. It will also display the remaining waiting time until the end of the red light phase.
 
 An Arduino Yun can be used to make a traffic light consisting of 3 LED's and a real time clock. The lights will change at a given interval. The Arduino Yun saves the time that the traffic light will turn green/red. Then, it would run a PHP file that makes a connection to the online MySQL database and inserts the data received from the Arduino Yun. An Android app will retrieve the date from that database. The app calculates the desired speed and it will display a countdown timer when the car is not able to pass the green light.
 
 ![image](https://hackster.imgix.net/uploads/attachments/268772/iotopia_afb2_p5JGNwhmCj.PNG?auto=compress%2Cformat&w=1280&h=960&fit=max)

