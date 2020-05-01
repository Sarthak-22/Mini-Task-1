### Project 16 - BIDIRECTIONAL VISITOR COUNTER

__Description__ -

The main intention of this project is to create a circuit within a device which keeps the track of the number of persons entering or leaving a room and display it on an LED screen.When a person enters the room, count would be increased, whereas on leaving, the count would decrease. IR sensing mechanism is used to sense the presence of visitors and the whole counting operation is done by a microcontroller.

Two pair of IR sensors would be used placed at two ends of the entrance of the room. Each pair consists of an IR Transmitter (IR LED) and an IR receiver(PhotoDiode). Output from each sensor is fed to the microcontroller. In normal operation, IR light from the LED would not fall on the Photo Diode as it is a Reflective type IR Sensor which is possible only when the the light gets reflected from an object to the photodiode (in this case the person entering or leaving). The output from the sensor would be a logic LOW signal in this case.

In case of any interruption (due to any person crossing the path), the Photo Diode would start receiving the IR Light due to reflection and start conducting. As a result, the output from the sensor would be a logic HIGH signal. The transition from low to high, for each sensor pair is detected by the microcontroller and accordingly the count would be increased or decreased.

The microcontroller would work in such a way that if it senses logic HIGH, first on the Sensor 1 and then on Sensor 2, it assumes that the person is leaving the room and decreases the count displaying the same on the LCD. Same would be the mode of operation of the microcontroller when the person enters the room.

The circuit Diagram can be seen here - 

![image](https://www.electronicshub.org/wp-content/uploads/2015/09/Bidirectional-Visitor-Counter-using-8051-Microcontroller-Circuit-Diagram.jpg)

For detailed info on circuit connection, visit - [Bidirectional Vision Counter](https://www.electronicshub.org/bidirectional-visitor-counter-using-8051-microcontroller/)
