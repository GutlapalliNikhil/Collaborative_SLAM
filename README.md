##
mkdir catkin_make
cd catkin_make
mkdir src
cd src
git clone https://github.com/GutlapalliNikhil/Collaborative_SLAM.git
cd ..
catkin_make
source devel/setup.bash

1) Launching 2 turtlebots in gazebo env

roslaunch ros_multi_tb3 2_tb3_house.launch

2) Running the exploration on those 2 robots

roslaunch explore_lite explore_1.launch

roslaunch explore_lite explore_2.launch
