# 2D Feature Tracking

<img src="images/keypoints.png" width="820" height="248" />

This project was built as part of the **Udacity Sensor Fusion Nanodegree Program**. In this project, we use several powerful OpenCV built-in algorithms to detect keypoints(features), describe keypoints and match keypoints. Feature tracking has many applications in the field of computer vision such as motion estimation and visual odometry. Three main steps are involved in the entire tracking process. First we extract features that are trackable across a sequence of frames. Mostly we track corners and blobs as these are very distinctive in images. There are several feature detectors that have been developed, popular among them is the **Harris Corner Detector**.

## Dependencies for Running Locally
* cmake >= 2.8
  * All OSes: [click here for installation instructions](https://cmake.org/install/)
* make >= 4.1 (Linux, Mac), 3.81 (Windows)
  * Linux: make is installed by default on most Linux distros
  * Mac: [install Xcode command line tools to get make](https://developer.apple.com/xcode/features/)
  * Windows: [Click here for installation instructions](http://gnuwin32.sourceforge.net/packages/make.htm)
* OpenCV >= 4.1
  * This must be compiled from source using the `-D OPENCV_ENABLE_NONFREE=ON` cmake flag for testing the SIFT and SURF detectors.
  * The OpenCV 4.1.0 source code can be found [here](https://github.com/opencv/opencv/tree/4.1.0)
* gcc/g++ >= 5.4
  * Linux: gcc / g++ is installed by default on most Linux distros
  * Mac: same deal as make - [install Xcode command line tools](https://developer.apple.com/xcode/features/)
  * Windows: recommend using [MinGW](http://www.mingw.org/)

## Basic Build Instructions

1. Clone this repo.
2. Make a build directory in the top level directory: `mkdir build && cd build`
3. Compile: `cmake .. && make`
4. Run it: `./2D_feature_tracking`.
