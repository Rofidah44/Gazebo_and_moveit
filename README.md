# Gazebo_and_moveit
## Install ROS melodic and run the robot arm in gazebo and moveit
I dowenloaded vmware to use ubunto and install ROS melodic on ubunto
i started to install ROS in the temrminal with some commands lines
"roslaunch robot_arm_pkg check_motors.launch" with this command the robot arm will show in Rviz and in a new window will appear the joint_state_publisher
Now we want to connect the robot arm in the gazebo simulator by using this command "roslaunch robot_arm_pkg check_motors_gazebo.launch" 
Then we will run the robot arm in gazebo using this command "rosrun robot_arm_pkg joint_states_to_gazebo.py"
open the moveit in Rvis with this command "roslaunch moveit_pkg demo.launch"
Then we will run the robot arm with Rviz and gazebo using this command "roslaunch moveit_pkg demo_gazebo.launch"
