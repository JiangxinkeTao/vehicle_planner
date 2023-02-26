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

<video id="video" controls="" preload="none" poster="封面">
      <source id="mp4" src="./video/single_cvx.mp4" type="video/mp4">
</videos>










