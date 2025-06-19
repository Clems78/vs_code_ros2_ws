# vs_code_ros2_ws
A base template for using vs code remote dev extension with ros2 Jazzy


- Create a "ros2_ws" folder
- git clone the repository
- Add the dev container extension to vs code
- ctrl + shift + p : choose "reopen in container"

You now have a working ROS2 Jazzy install 

- Create a src folder in the ros2_ws
- Run colcon build
- Run source install/build.bash

To test the install:
- ros2 topic list

To test that GUI app work:
- ros2 run rviz2 rviz2
- gz sim

Add packages to the "packages.repo" file

