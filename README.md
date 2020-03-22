# Sensor Fusion Self-Driving Car Course - Camera Examples

Basic Examples for OpenCV && Keypoint Detectors/Descriptors

### Project Status:

![issue_badge](https://img.shields.io/badge/build-Passing-green) ![issue_badge](https://img.shields.io/badge/UdacityRubric-Passing-green)

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

## Project Overview

All those projects were mini code-assignments from [Udacity Sensor Fusion Nanodegree - ND313](https://www.udacity.com/course/sensor-fusion-engineer-nanodegree--nd313)

And Here's project lists

* Opencv Example : Practice Basic OpenCV functions, Load images, Handle pixel values using `cv::Mat` datastructure

* TTC_Lidar && TTC_Camera : Calculate [TTC(Time To Collision)](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.511.3548&rep=rep1&type=pdf) by using Lidar / Camera datasets

* Gradient Filtering : Practice Gaussian smoothing, Calculate gradient intensity by using Sobel kernel / get magnitude, gradient from image. 

* Cornerness Harris : Practice Harris Corner detection with some parameters. And Also, Implement `Non-Maximum-Suppression` to those keypoints

* Detect Keypoints : Learn about many kinds of detectors, And Compare those methods with regard to precision, speed, keypoint destributions.

* Describe Keypoints : Learn how to describe keypoints, which is reffered to descriptor. Compare two mostly used descriptor methods (HOG & Binary).

* Descriptor Matching : Match keypoints between consecutive two images by implementing specific `matcherType`/`descriptorType`/`selectorType` combination

## Basic Build Instructions

1. Clone this repo.
2. Enter to project : `cd ./<your-prefer-project>`.
3. Make a build directory in the top level directory: `mkdir build && cd build`
4. Compile: `cmake .. && make`
5. Run executable files
