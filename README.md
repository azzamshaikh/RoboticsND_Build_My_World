# RoboticsND_Build_My_World
Create a Gazebo World enviroment which includes a building and robot models. This is the foundation for the rest of the RoboticsND projects

## Instructions

1. Clone this repo.
2. Make a build directory in the top level directory: `mkdir build && cd build`
3. Compile: `cmake ../ && make`
4. Add plugin path: `export GAZEBO_PLUGIN_PATH=${GAZEBO_PLUGIN_PATH}:***add your directory***/myrobot/build`
5. Change to world directory: `cd .. && cd world` 
6. Launch the world file in Gazebo to load both the world and plugin: `gazebo Azzam\'s_World`
