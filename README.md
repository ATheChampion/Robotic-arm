# Lotus 5-DOF robotic arm

<img width="970" height="608" alt="image" src="https://github.com/user-attachments/assets/fa4098d0-911f-4c6f-9fd7-fc8434e9a3b7" />

A 5 degree-of-freedom (5-DOF) robotic arm engineered for high-strength 3D printing.
Smart serial servos are placed at the base of the arm to control each axis remotely using parallel linkage mechanisms and an internal timing belt system for wrist roll. The compact end effector features a Sherpa Mini extruder and Bambu P1 hotend cooled by dual 4010 blower fans, allowing multi-axis 3D printing without support structures.

## Features:

* **5-DOF Articulation:** Five independent joints allow the end effector to tilt relative to printed parts and reduce unnecessary support material.
* **Base-Mounted Actuators:** Feetech STS3215 servos are located at the base of the arm, using 4-bar linkage systems to reduce moving mass and improve the arm's accuracy.
* **Integrated Extruder and Hotend:** The head of the arm features a lightweight Sherpa Mini extruder and Bambu P1 series hotend allowing for better prints compared to the traditional Bowden setup.
* **Dual blower cooling:** The 3d prints and hotend are cooled by two 4010 blower fans which blast air through a chute during printing.
* **Planetary gearbox base:** The main rotating base / first axis features a 4:1 transmission ratio for higher torque and smoother rotation.

<img width="620" height="702" alt="image" src="https://github.com/user-attachments/assets/5d30b2db-c861-4599-8dc7-761581a5e5df" />

## CAD and Mechanical overview:

The arm is built out of 3d printed parts along with screws, gears, ball bearings and pulleys.

* **Base structure:** Servo mounts are connected directly to the rotating base.
* **Remote rotation** The arm uses 2GT timing belts, pulleys, and linkages to route motion through the arm structure.
* **Custom toolhead** The head of the arm holds the hotend, cooling, bed sensor, and extrusion mechanics together using a mount for the specific part combination.
