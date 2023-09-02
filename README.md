# ROS
### mkdir catkin_ws
### cd catkin_ws
#### mkdir src
### catkin_create_pkg ros_tutorials_topic message_generation std_msgs roscpp
### source devel/setup.bash
### git clone https://github.com/ROBOTIS-GIT/ros_tutorials.git

### rosrun ros_tutorials_topic topic_publisher

### rosrun ros_tutorials_service service_server
### rosrun ros_tutorials_service service_client 2 3
### roslaunch ros_tutorials_topic union.launch
### rqt_graph
### export TURTLEBOT3_MODEL=burger
### source devel/setup.bash
### roslaunch turtlebot3_gazebo turtlebot3_world.launch
### source devel/setup.bash
### roslaunch turtlebot3_teleop turtlebot3_teleop_key.launch

### roslaunch turtlebot3_slam turtlebot3_slam.launch slam_methods:=gmapping
### rosrun map_server map_saver -f ~/map
### roslaunch turtlebot3_navigation turtlebot3_navigation.launch map_file:=/home/user/map.yaml

### https://github.com/Octanas/Reactive-Wall-Following-Robot
https://github.com/Octanas/Reactive-Wall-Following-Robot.git
