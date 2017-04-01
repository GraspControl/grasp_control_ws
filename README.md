# grasp_control_ws
Top Level Repo For Project. 


Setup:
```
cd
git clone git@github.com:GraspControl/grasp_control_ws.git
cd ~/grasp_control_ws
source /opt/ros/indigo/setup.bash
wstool update
cd ~/grasp_control_ws/src
catkin_init_workspace
cd ~/grasp_control_ws
catkin_make
```

Running:
First Terminal:
```
cd ~/grasp_control_ws
source devel/setup.bash
roslaunch graspit_interface graspit_interface.launch
```

Second Terminal:
```
cd ~/grasp_control_ws
source devel/setup.bash
rosrun grasp_controller grasp_controller.py
```
