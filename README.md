## Robot Package

#source a ros2
$ source /opt/ros/humble/setup.bash

#source al paquete dentro de src
$ source install/local_setup.bash

#levantar el robot
$ ros2 launch my_bot launch_sim.launch.py world:=./src/my_bot/worlds/obstaculos.world