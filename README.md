# Programming Robots with ROS workspace
------
This is my local workspace of the "Programming Robots with ROS" book's code.
To have this properly running on your machine (ROS Indigo tested) you should create a workspace:

```bash
$ mkdir -p ~/rosbook_ws/src && cd ~/rosbook_ws/src
$ git clone https://github.com/bpinaya/rosboot_ws.git
$ cd ~/rosbook_ws && catkin_make
```

Besides having installed ROS Indigo full (check [instructrions here](http://wiki.ros.org/indigo/Installation/Ubuntu)) you should install the following packages:
- `sudo apt-get install ros-indigo-turtlebot-gazebo`
