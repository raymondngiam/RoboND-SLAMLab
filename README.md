[![Udacity - Robotics NanoDegree Program](https://s3-us-west-1.amazonaws.com/udacity-robotics/Extra+Images/RoboND_flag.png)](https://www.udacity.com/robotics)

# RoboND-SLAMLab
In this lab, we will implement a gmapping ROS package which is based on the Grid-based FastSLAM algorithm to map an environment.

### Video demo

![alt text](images/demo.gif)

### Dependencies

- ROS Kinetic
- CMake 2.8

### Installing ROS dependencies

```bash
$ cd <repo root>/catkin_ws
$ sudo apt update
$ rosdep install --from-paths ./src --ignore-packages-from-source -y
```

### Compiling the Program

```bash
$ cd <repo root>/catkin_ws
$ catkin_make
```

### Running the Program

```bash
$ cd <repo root>/catkin_ws/src
$ sh SLAM.sh
```