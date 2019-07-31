# Ball_fallowing_robot

To run, setup two terminals

cd catkin_ws
catkin_make
source devel/setup.bash
Run in separate terminals:

roslaunch my_robot world.launch
roslaunch ball_chaser ball_chaser.launch
The bot will follow the white ball around. You have to manually move the white ball to places that the bot can see it.
