# Light_detection_with_ML

The project is about monitoring a sudden change in lighting of the room. 

The light_sensoring devices use a Light Dependent Resistor(LDR) which is a resistor whose resistance changes inversely with the intensity of light falling on it. As the intensity increases the resistance decreases.
If the sensor_value crosses a certain threshold it will send SMS to the user to about the change and will alert him.
In a room, the light intensity may vary every minute due to the sunlight so it's not possible to give a certain threshold. That's where Machine Learning model is used. 

In this project Anomaly detection using Z-score is used to alert for a sudden change in the intensity of light.
If there is sudden change in intensity of light the device will send a SMS to the user. 
It can be build to send an email or a tweet on twitter.

Devices used :

Bolt IoT module.
LDR.

Software: 

Python3,
Twilio(for SMS sending)

File Description:

"conf.py" has the configuration details for the device and twilio api.

"anomaly_detection.py" has the code to do the task.
