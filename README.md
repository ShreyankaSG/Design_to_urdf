# Design_to_urdf
 In your ROS environment

Place the generated _description package directory in your own ROS workspace. "catkin_ws" is used in this example. 
Then, run catkin_make in catkin_ws.

cd ~/catkin_ws/

catkin_make

source devel/setup.bash

Now you can see your robot in rviz. 
You can see it by the following command.

roslaunch (whatever your robot_name is)_description display.launch

If you want to simulate your robot on gazebo, just run
roslaunch (whatever your robot_name is)_description gazebo.launch
