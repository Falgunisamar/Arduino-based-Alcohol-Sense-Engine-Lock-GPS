# Arduino-based-Alcohol-Sense-Engine-Lock-GPS
Creating an alcohol sensing engine lock system with GPS using Arduino involves integrating an alcohol sensor, GPS module, and a relay to control the engine. 
Hardware Components:

Arduino Board (e.g., Arduino Uno)
Alcohol Sensor (e.g., MQ-3)
GPS Module (e.g., NEO-6M)
Relay Module
LCD Display (optional)
Buzzer (optional)
Push Button (optional)
Power Supply
Drunk driving is one of the major reasons behind road accidents worldwide. In all of the road accident cases worldwide drivers have been observed to have excess alcohol content in their blood. So we here design a smart alcohol detector system using arduino coupled with gsm and gps for location transmission.

The system allows for automatic sensing of alcohol in breath, we also use a motor to demonstrate as a vehicle. We further use a GPS module with GSM to send an SMS message to the concerned person in case alcohol is detected and stop the vehicle motor.

The system consists of an Arduino Uno board along with an Mq-3 alcohol sensor for detection and a GSM/GPS Module for notification. In the case of a sober driver i.e. the alcohol is under the permissible limits the car will normally which is indicated by the motor rotating, but in the case of a drunk driver, the alcohol content would be higher than the permissible limit which is detected by the alcohol sensor and the Arduino controller which stops the motor so that drunk driving can be avoided and also sends an SMS notification to the authorities or family members along with the location of the car so that assistance can be provided. The project also has an LCD for parameter display.
