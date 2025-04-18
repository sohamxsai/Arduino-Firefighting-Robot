# Arduino-Firefighting-Robot
The importance of this project lies in its potential for real-world application in industries, homes, and warehouses to mitigate fire hazards and save lives. It also serves as a great entry point into embedded systems, robotics, and automation.
This Arduino program controls a fire-fighting robot using three flame sensors, a servo motor, a relay-controlled water pump, and two DC motors. The robot constantly monitors for fire using analog sensors placed on the left, center, and right. If a flame is detected (i.e., the sensor value drops below a defined threshold), the robot responds accordingly based on the flame’s location. If the fire is in the center, it moves forward; if to the left or right, it turns in that direction. Upon detecting fire, it also activates a water pump via a relay and sweeps a servo-mounted sprayer from left to right to extinguish the flame. After a fixed duration, the pump is turned off automatically. The robot stops and resets the pump and servo when no fire is detected. The code includes clear functions to handle robot movement (forward, left, right, stop), pump control, and servo operations. Sensor values and status messages are printed to the Serial Monitor for debugging and observation. This setup provides an automated way to detect and respond to small fires, making it ideal for safety or rescue robots in experimental or controlled environments.
Tools/Software/Materials Used:
• Arduino Uno
• Relay Module
• L298N Motor Driver
• Flame Sensor
• DC Motors
• Wheels & Chassis
• Water Pump/Fan
• Battery & Wires
• Arduino IDE (Software)
 
Methodology:
1. Connect flame sensor to Arduino to detect fire.
2. Use L298N motor driver to control robot motion.
3. Use relay module to control water pump/fan.
4. Program logic to move the robot towards fire source and activate extinguishing mechanism.
