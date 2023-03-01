# Path Planning for Parking of Car-like Vehicles using Switched Heuristic Functions of Reed-Shepp Curves
> Realize non-holonomic constrained vehicle planning in narrow convex space. (The source code will cme soon)

## Installation
### Required Library
- Eigen3
- PCL 1.7
- ROS
- [jsk_recognition](https://github.com/jsk-ros-pkg)

Note: C++ 11 is recommended to run II-planner. Please install and configure C++ 11.

```sh
roslaunch cross_iter_planner ii_planner_with_chassis_polygon.launch 
```



The width and length of non-holonomic vehicle is $1.6m$ $\times$ $3.8m$ and its minimum turning radius is 5m, the  experimental environment is an 8.0m\*9.0m convex polygonal environment, the experimental results are as follows.


https://user-images.githubusercontent.com/42513042/221400117-7efa6a00-624e-4820-b820-78697eabdd43.mp4

The experimental platform utilized in this study comprises the HunterSE chassis, the experimental vehicle with chassis size of $0.64m$ $\times$ $0.82m$ and its minimum turning radius is $2.5m$, and equip with the environment sensing Hesai QT64 LiDAR and IMU. The NUC12WSHi7 serves as the computing unit, and communication is established via WIFI.



https://user-images.githubusercontent.com/42513042/221401854-9491b35c-21d1-43ee-90f5-c49ded2188bb.mp4




