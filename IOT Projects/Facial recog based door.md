### Project 11 - FACIAL RECOGNITION BASED DOOR

__Description__-

This project comprises of three parts - i) Face detection and data gathering ii) Training recognizer iii) Facial recognition. The opening and closing of the door would be controlled by Rpi connected to a [solenoid door lock](https://www.takigen.com/products/list/14020). However, a solenoid door lock will be needed with an external power source and a relay to operate because of its relatively high operating voltage.

__Data gathering for face detection__- The first task is to gather the data for which we are going to train our classifier. We will write a python code that will take atleast 10 faces of each person using OpenCV pre-trained classifier. OpenCV already contains many pre-trained classifiers for face, eyes, smile, etc. The classifier we are going to use will detect faces.

The recognizer we set up with the help of training set can now be used to recognize the faces. It will give us the match precision and label ID. If the match precision is above a certain threshold level , the relay will turn on. If the face does not match upto the desired precision then the door will remain locked.

![image](https://maker.pro/storage/7lXpaTR/7lXpaTRkj9eDNwTUKANgJWqJVCJ8EbQt7a1NQLBR.png)

The detailed info can be found here - [Face recog door](https://maker.pro/raspberry-pi/projects/how-to-create-a-facial-recognition-door-lock-with-raspberry-pi)
