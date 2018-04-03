## Sophus

C++ implementation of Lie Groups using Eigen. 

### Packaging

This is a development fork of the upstream repository maintained for the ROS community in order to maintain stability across ROS distros. Please send any non-release related issues or pull requests upstream. 

Note that this is ahead of the release branch on kinetic.

### Installation - CMake

```
$ cd Sophus
$ mkdir build
$ cd build
$ cmake ..
$ make
```

### Installation - Catkin

```
$ mkdir -p ~/sophus_ws/src
$ cd ~/sophus_ws/src
$ vcs import < https://github.com/stonier/sophus.git
$ cd ~/sophus_ws
$ catkin_tools build
```

