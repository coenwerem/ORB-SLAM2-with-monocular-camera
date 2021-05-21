# ORB-SLAM2-with-monocular-camera
Trying out ORB-SLAM2 with a monocular camera for a differential-drive robot.

## Camera Calibration
![Camera Calibration GIF](img/calib_for_gif.gif?raw=true)

## Initial Point Cloud Tests
![Point Cloud Test GIF](img/point_cloud_test.gif?raw=true)

## Teleoperating the Robot
### Requirements
+ Ubuntu 18.04 (Bionic Beaver)
+ ROS Melodic Distro
+ Turtlebot3 Teleop Package: Run `sudo apt-get install ros-melodic-turtlebot3-teleop` to install the package.

To start the teleoperation and ORB_SLAM node, run `roslaunch orb_slam_pkg teleop_map.launch` after building the package using `catkin_make` and sourcing your workspace (using `source devel/setup.bash`) in the `catkin_ws/` directory.
