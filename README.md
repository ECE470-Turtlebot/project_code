# project_code
Code to control the turtlebot3 simulator in gazebo for object detection and robotic arm manipulation


# How to Start Simulation
To use, clone the turtlebot branches into a workspace, build it, and source it.
Make sure you have gazebo9 installed. If not check the gazebo installation header.
Export the turtlebot environment variable using "export TURTLEBOT3_MODEL=burger" in your preferred shell
Upon doing this you can launch the turtlebot3 in gazebo in its various worlds using roslaunch

One example that launches turtlebot in a house environment is as follows:-
roslaunch turtlebot3_gazebo turtlebot3_house.launch

turtlebot3_gazebo package lies in the turtlebot3_simulations repo.

# Installing Gazebo
On ubuntu, gazebo 9 can be installed with apt using the following command:-
"sudo apt install gazebo9"
