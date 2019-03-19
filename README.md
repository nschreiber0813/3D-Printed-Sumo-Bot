# 3D-Printed-Sumo-Bot
This is a repository for my 3D Printed arduino sumo robot.

# Code and Electronics

The robot is programmed in Arduino. I used an Arduino uno with a GPIO extension board but that is not required unless you are hoping to use my code. The wiring schematic is simple. Pins 7 and 8 are for the standerd sized metal gear servo motors that drive the robot and pins 6 and 7 are used for the IR sensors that are used for detecting the edge of the sumo arena.

# About the code

The code uses an int called Mode. This mode is used for testing the robot in 4 different stages of developement. The first stage is mode 0 and the final mode is 3. When making this robot I had problems with the servos. The servos couldn't move straight when the servos changed directions. When the motors changed directions they didn't start changing directions at the same time. To work with that I didn't program the robot to change to turn. It was doing that on it's own sporatically.

# The different modes

Mode 0 is for making the robot and testing the motors. Mode 1 is for testing the robots sensors. Mode 2 is for getting the robot to avoid the edge. Mode 3 is the code used for battling other sumos.
