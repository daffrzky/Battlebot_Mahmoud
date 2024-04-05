# Overview:

This project involves building a simple robot with an Arduino board that can follow black lines using infrared sensors to stay on track. We've also added a feature: an ultrasonic sensor and gripper mechanism, so the robot can pick up objects as it moves along.

# Components:
 - Bullet list
              - Nested bullet
                  - Sub-nested bullet etc
          - Bullet list item 2
Arduino board (Arduino Nano
Clipper
LED Lights
Motor driver module
Infrared sensors (8x)
DC motors (2x)
Wheels (2x)
Chassis
Battery pack
Gripper mechanism
Ultrasonic sensor

# Setup and Installation:

1) Establish the connection between the motor driver module and the Arduino board.
2) Link the motors to the designated outputs of the motor driver.
3) Attach the infrared sensors to the analog pins of the Arduino board.
4) Interface the ultrasonic sensor with the specified pins on the Arduino board.
5) Wire the LED lights to the analog pins for control.
6) Connect the gripper mechanism to the allocated pin on the Arduino board.

# Running the code:

1. Install Arduino IDE
2. Upload the code
3. Select proper COM port

# Assembly:

1) Put the motors and wheels on the chassis.
2) Fix the infrared sensors to the front of the robot, pointing down to see lines on the ground.
3) Install the ultrasonic sensor and gripper mechanism following their instructions.

# How to use:

1) Turn on the robot.
2) Put it on a surface with a black line.
3) The robot will use its sensors to follow the line and move forwards, as well as changing its directon to avoid objects that ostruct its path.
4) It can now grab things with its special sensor and gripper.
5) Check the code comments to understand how it works.
6) The robot will keep following the line until you turn it off or something special happens, for example if it can no longer see the line.
7) Ensure the power bank has enough battery.


