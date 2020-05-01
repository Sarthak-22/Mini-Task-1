### Project 20 - SMART STREET LIGHTS

__Description__ - 

This system controls street lights using Light Dependent Resistors and PIR sensors. The proposed system would essentially consist of a microcontroller, LDR, PIR and RTC.

Street lights are switched on depending on the intensity of the Sun light on LDR. If the intensity of Sunlight on light dependent resistor is low, its resistance value is high. This value increases and becomes high when it is completely in dark. This resistance value decides when the street lights are required to switch ON.

As the resistance value is maximum in the midnights, real time clock comes into the play. The controller checks peak time during which there is no traffic and switch OFF the lights.When there is any vehicle on the road, it is detected by the PIR sensor.

PIR sensor senses the motion of the objects.

The PIR sensor internally will have an IR detector. Every object in the world radiates some IR rays. These are invisible to the human eye but electronic components can detect them. Different objects will emit IR rays of different wavelength. These rays were detected by the PIR sensor. PIR is initially high and is set to low automatically after sometime. Whenever it detects the motion of any object, it becomes low.

Whenever PIR sensor is detected it just indicates the microcontroller to switch on the street lights. Then lights are switched on for 2 to 3 minutes and switched off automatically.

![image](https://www.electronicshub.org/wp-content/uploads/2014/06/Street-Lights-That-Glow-on-Vehicle-Movement-Circuit-Diagram-1024x536.jpg)
