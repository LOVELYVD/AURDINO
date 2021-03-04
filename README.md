# AURDINO


LINE FOLLOWER ROBOT : Sense and follows a black line.

:I have used a microcontroller to control whole the process of system . Arduino is an open-source hardware and very useful for project developments.


When light falls on a white surface it is almost fully reflected . When light falls on a  black surface light is completely absorbed. This behavior of light is used in building a line follower robot.

IR Transmitters and IR receivers [photodiodes] are used for sending and receiving light. IR transmits infrared lights.When infrared rays falls on the white surface, it’s reflected back and caught by photodiodes which generate some voltage changes. When IR light falls on a black surface, light is absorbed by the black surface and no rays are reflected back, thus photo diode does not receive any light or rays. Here in this Arduino line follower robot when the sensor senses white surface then Arduino gets 1 as input and when senses black line Arduino gets 0 as input.

3 sections are sensor section, a control section, and driver section.

IR Module is sensor circuit that consists IR LED/photodiode pair, potentiometer, LM358, resistors and LED. IR sensor transmits Infrared light and photodiode receives the infrared light.


I have added a voltage regulator to get 5 volts for Arduino, comparator and motor driver. And a 9-volt battery is used to power the circuit.

L293D is a motor driver IC which has two channels for driving two motors. L293D has two inbuilt Transistor Darlington pair for current amplification and a separate power supply pin for giving external supply to motors.



         
