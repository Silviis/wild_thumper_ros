# wild_thumper_ros
ROS package for Wild Thumper robot base. Contains URDF and launch files for simulation.

## Usage:

Clone this repository into catkin workspaces src/ folder. Build the package, source devel/setup.bash and launch e.g.


`catkin_make` or `catkin build`

`source devel/setup.bash`

`roslaunch wild_thumper_ros wild_thumper_gazebo.launch`

Now you should have a Gazebo window with Wild Thumper spawned inside a world. The world launched is defined in the launch file. Remember to `export GAZEBO_RESOURCE_PATH=/your/path/to/wild_thumper_ros/` so Gazebo finds the world file(s).
