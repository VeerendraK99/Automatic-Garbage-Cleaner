# Automatic-Garbage-Cleaner
The main purpose of the entire system is to provide a more radical solution to the manual cleaning of drains. So this system is a vehicle which operates with help of raspberry pi
as the brain and it controls the motion motors using the motor driver IC L293D. The raspberry is pre-programmed with a python code about the controls of motors. While the motor
for the control of wheels is running another motor which controls the motion of conveyor system also rotates. This conveyor is the heart of the system it alone controls the
lifting up of the floating waste from the water and storing them in a bin. An ultra sonic sensor is placed on top of the bin for its monitoring. When the bin gets filled upto a 
predetermined threshold level the ultra sonic sensor senses it and with the python code in raspberry pi if the level is reached the motors will be stopped and a mail will be 
delivered to the selected recipient indicating the status of the bin in form of a text message using SMTP protocol. The central idea of vehicle was taken from the Mr. Trash Wheel 
concept.

Also the motors will be started only when an object is detected by the camera powered by the raspberry pi using an R-CNN image processing algorithm to reduce power consumption and 
also for system to work efficiently.
