This is a ROS package for turtlebot3 navigation in gazebo.
To be able to use these launch files: find the 'worlds' folder in the 'assignment3_turtlebot3' package folder and copy its contents to the worlds folder in your gazebo path

Scripts:

a) circle.py: This scripts moves the turtlebot in a circular configuration.
b) square.py: Moves the turtlebot in square configuration
c) move_brake.py: Moves the turtlebot in a straight line until the laser scanner detects an obstacle (wall) and then it stops

launch files:

a) move.launch: to run this file there are two script options (if no 'code' is assigned, runs circle.py by default):
	roslaunch assignment3_turtlebot3 move.launch code:=circle.py	# if you want to run the circle.py script
	roslaunch assignment3_turtlebot3 move.launch code:=square.py	# if you want to run the square.py script

b) move_brake.launch: 
	roslaunch assignment3_turtlebot3 move_brake.launch
	
