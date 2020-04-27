# moving_cube_rl
 this is a tutorial on building a cube with  a single wheel that learn to move using gym environment.
 this tutorial from https://www.theconstructsim.com and can be view the youtube explination: https://www.youtube.com/watch?v=3_afZzjAQbc
 
 to run the training
 1. roscore
 
 open gazebo 
 2. roslaunch gazebo_ros empty_world.launch
 
 then spwn the cube 
 3. roslaunch my_moving_cube_description spawn_moving_cube.launch
 
 and now we can run the controller
4. roslaunch my_moving_cube_description moving_cube_control.launch

finally we run the training launch file

5. roslaunch my_moving_cube_training_pkg start_training.launch
