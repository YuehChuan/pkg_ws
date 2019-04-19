pkg_ws
===
ros2 workspace python packages for demos

ubuntu18.04 ROS2 Crystal Clemmys 

Demo videos 1
===



Installation
===

PreInstall

**for ubuntu18.04**

Build from source https://hackmd.io/s/r1XrUugc4
Binary install https://hackmd.io/s/r1zBPCgqE


**pkg_ws** 
Building
========

git clone https://github.com/YuehChuan/pkg_ws


To compile the code, 
```
    cd ~/pkg_ws
    
    clocon build --symlink-install
```
How to Fly
========

**2. talk and listener demos**


Open 2 terminals shows like this, you can utilize byobu tool.
Remember "Tab" key is always your GOOD friend for autocomplete!

**Terminal1: talker**
```
cd ~/pkg_ws

source install/setup.bash

ros2 run demo_nodes_py talker
```
**Terminal2: listener**

```
cd ~/pkg_ws

source install/setup.bash

ros2 run demo_nodes_py listener
```
