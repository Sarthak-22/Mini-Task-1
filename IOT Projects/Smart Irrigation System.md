### Project 13 - SMART IRRIGATION SYSTEM

__Description__-

The Smart Irrigation System is an IoT based device which is capable of automating the irrigation process by analyzing the moisture of soil and the climate condition (like raining). The device would use [BOLT IOT](https://www.quora.com/What-is-BOLT-IoT) so that data gathered from the sensors can be easily accesible in the internet through BOLT cloud page.

In this project, we will command the arduino/328p microcontroller through a webpage to control the motor (i.e., to start and stop the motor) and the rest of whole irrigation process will be automatically controlled by arduino itself. The user can manually switch off or switch on the motor through the website. The Arduino can be coded in such a way that as soon as the user prompts the motor to switch on, the device sprinkles water until the soil moisture sensor has reached the required threshold value. 

If weather condition is such that it started raining, then the micro-controller will shut down the motor pump till raining. And after that it checks whether the soil moisture sensor has reached the threshold value or not. If it crosses the threshold value then motor pump will remain shut down otherwise it will start again automatically.

Detailed info can be foun here - [Smart Irrigation System](https://www.instructables.com/id/SMART-IRRIGATION-SYSTEM-Using-IoT/)
