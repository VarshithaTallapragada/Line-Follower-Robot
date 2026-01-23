
🚗 Line Follower Robot using Arduino
📌 Project Description
This project is a Line Follower Robot built using Arduino UNO and IR sensors.
The robot is programmed to follow a black line on a white surface (or vice versa) by continuously reading sensor inputs and controlling the motors accordingly.
It demonstrates the concepts of embedded systems, robotics, and automation.

🛠️ Components Used
Arduino UNO (or compatible board)
IR Sensor Module (2 or more sensors)
Motor Driver Module
DC Motors with Wheels
Battery Pack
Jumper Wires

⚙️ Working Principle
IR sensors detect the contrast between the line (black) and the background (white).
If the left sensor detects the line → robot turns left.
If the right sensor detects the line → robot turns right.
If both sensors detect white (background) → robot moves forward.
If both sensors detect black (line) → robot stops or continues straight (depending on logic).

🔌 Circuit Connections
IR Sensor outputs → Arduino digital pins
Motor Driver inputs → Arduino digital pins
Motors → Motor Driver outputs
Battery → Motor Driver + Arduino (Vin)
