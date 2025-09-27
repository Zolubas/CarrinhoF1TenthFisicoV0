How to run?
1) Unzip the files and save them in the F1Tenth car workspace (it must be mounted with Hokuyo LiDAR 10 UST-LX and VESC 6MK VI)
2) Run the follow commands from your home:

First terminal

```
cd f1tenth_ws/
source install/setup.bash 
ros2 launch f1tenth_stack bringup_launch.py 
```

Second terminal

```
cd ftgBasic_ws/
source install/setup.bash 
ros2 run autodirve2vheicle_pkg autodirve2vheicle_node 
```

Third terminal

```
cd ftgBasic_ws/
source install/setup.bash 
ros2 run ebva_mapless_control EBVAUSPQualifier 
```
