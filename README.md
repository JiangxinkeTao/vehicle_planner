# II-Planner
> Realize non-holonomic constrained vehicle planning in narrow convex space. 

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



The width and length of non-holonomic vehicle is 1.6m\*3.8m and its minimum turning radius is 5m, the  experimental environment is an 8.0m\*9.0m convex polygonal environment, the experimental results are as follows.









https://user-images.githubusercontent.com/42513042/221400117-7efa6a00-624e-4820-b820-78697eabdd43.mp4






