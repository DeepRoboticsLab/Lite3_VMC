lite3_high_level

roslaunch gazebo_model_spawn gazebo_startup.launch
roslaunch gazebo_model_spawn model_spawn.launch rname:=lite3 use_xacro:=true use_camera:=false #start controller
rosrun examples example_lite3_sim
rosrun examples example_keyboard