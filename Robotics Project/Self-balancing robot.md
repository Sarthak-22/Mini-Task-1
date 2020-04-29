### Project3 - SELF BALANCING ROBOT

__Description__ -

As the name suggests, a self-balancing robot is a robot that knows how to balance its body to attain a stable equilibrium. The robot would use a microcontroller to acquire data from an attached [Inertial Measurement Unit (IMU)](https://en.wikipedia.org/wiki/Inertial_measurement_unit). The microcontroller fitted will communicate with various devices assembled onto the the system over I2C, the most important being obtaining data from the accelerometer and gyroscope in the IMU. 

The robot would use a PID controller to maintain balance. PID, namely the proportional-integral-derivative controller, is an extremely effective and popular control algorithm based around a feedback loop. It works by calculating an error term e(t) as the difference between some input value and a desired value (in our case, the angle of the robot is the input, and the desired value is 0°), then calculating the integral and derivative of this error term over time. To get the output of the PID controller we multiply each of these three values by the corresponding gain terms (which are set by the user) and then add all three together.

The data acquired from the IMU will be analysed by the microcontroller in such a manner that it attempts to maintain equilibrium by using a PID controller to counteract its pitch value by driving the wheels of the robot such that they move beneath the center of mass.

![robot](https://people.ece.cornell.edu/land/courses/ece4760/FinalProjects/f2018/amm452_fb262/amm452_fb262/amm452_fb262/images/balance_bot.jpg)

A detailed analysis and assembly of the robot can be found here - [self-balancing robot](https://people.ece.cornell.edu/land/courses/ece4760/FinalProjects/f2018/amm452_fb262/amm452_fb262/amm452_fb262/index.html)
