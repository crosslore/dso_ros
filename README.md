# ROS Wrapper around DSO: Direct Sparse Odometry

## Changes in this repository

* Install with ROS catkin now
* Clone the repository into your ros workspace
* Ensure you are on the catkin branch `git checkout catkin`
* Clone [rpng/dso](https://github.com/rpng/dso) into your ros worspace
* `sudo apt-get install libsuitesparse-dev libeigen3-dev libboost-all-dev`
* Ensure [Pangolin](https://github.com/stevenlovegrove/Pangolin) is globally installed
* Grab a dataset from the TUM website [link](https://vision.in.tum.de/data/datasets/mono-dataset)
* Run the program using: `rosrun dso_ros dso_live image:=image_raw calib=XXXX/camera.txt gamma=XXXX/pcalib.txt vignette=XXXX/vignette.png`
* Note: This is used for live images from a sensor driver or a rosbag.
* Note: To run on the tum_mono dataset see the instructions in the main repository


### License
This ROS wrapper around DSO is licensed under the GNU General Public License
Version 3 (GPLv3).
For commercial purposes, we also offer a professional version, see
[http://vision.in.tum.de/dso](http://vision.in.tum.de/dso) for details.

*All additional code added is released under the GNU General Public License Version 3 (GPLv3).*
