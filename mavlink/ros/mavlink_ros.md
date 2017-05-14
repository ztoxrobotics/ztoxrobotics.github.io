#`mavlink_ros` ROS package

The `mavlink_ros` package is a *serial MAVLink to ROS bridge*. This ROS package created a  node that allows to send and receive MAVLink packets through a serial interface.

The [mavlink_ros](https://github.com/mavlink/mavlink_ros) ROS package was initially coded by Lorenz Meier for rosmake (old ROS versions). An updated (**catkinized**) package is available [here](https://github.com/y22ma/mavlink_ros).

#### Compiling `mavlink_ros`

To use `mavlink_ros` you just need to clone the repository at `~/catkin_ws/src` directory:

```bash
cd ~/catkin_ws/src
git clone https://github.com/y22ma/mavlink_ros
```

Then we need to compile the package with `catkin_make`:
```bash
cd  ~/catkin_ws/
root:~/catkin_ws# catkin_make
Base path: /root/catkin_ws
Source space: /root/catkin_ws/src
Build space: /root/catkin_ws/build
Devel space: /root/catkin_ws/devel
Install space: /root/catkin_ws/install

