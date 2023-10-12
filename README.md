# ros2-humble-auv-eca-a9
此程序可应用于Ubuntu 22.04 ros2 humble中，其完整仿真工具包如下https://github.com/Liquid-ai/Plankton
source /opt/ros/humble/setup.bash
ros2 launch uuv_gazebo_worlds ocean_waves.launch
ros2 launch eca_a9_gazebo start_demo_teleop.launch joy_id:=0
