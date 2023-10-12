# ros2-humble-auv-eca-a9
- 此程序可应用于Ubuntu 22.04 ros2 humble中，其完整仿真工具包如下https://github.com/Liquid-ai/Plankton
- 将其工具包下载完成后，将上述文件夹进行替换，即可实现运行，运行顺序：
- source /opt/ros/humble/setup.bash
- ros2 launch uuv_gazebo_worlds ocean_waves.launch
- ros2 launch eca_a9_gazebo start_demo_teleop.launch joy_id:=0
