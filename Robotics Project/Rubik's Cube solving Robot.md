### Project 2 - RUBIKS CUBE SOLVING ROBOT
#### (Difficulty - High)

__Description__ - 

This project aims to build a rubiks cube solving robot that utilized image processing, Kociemba's algorithm, and servos acting as claws/arms to turn the cube. The analysis of different faces of the cube can be done using an image processing package in python, OpenCV. After processing the 6 images of 6 faces, the code can then pass the input to an algorithm named Kociemba's Algorithm.

The algorithm can be implemented using python. This package is published on PyPI and can be installed with: $ pip install kociemba. The information about Kociemba's algorithm can be found on Herbert Kociemba's [website](http://kociemba.org/cube.htm).

A webcam can be fitted at all the six sides of the robot to capture the image of each side. The image can then fed to a python script which interprets the input data. The input data can be passed to Kociemba algorithm which then returns a string of moves to the control system to solve the cube.

The video demonstration for a Rubiks Cube Solving Robot - ![video](https://www.youtube.com/watch?v=P_QeuBTk3vQ&feature=youtu.be)
             
