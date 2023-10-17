# Release Notes

## Nvblox with Isaac ROS 2.0.0 October 18, 2023:
### What's New
Isaac ROS-synchronized release including:
- General dynamics detection and reconstruction.
- Added free-space layer and integrator to track regions high-confidence free-space.
- Depth and Mask image pre-processing options.
- Performance improvements stemming from making all CUDA calls asynchronous, and moving work off the default CUDA stream.
- Improved stability. More warnings turned on, tests run (optionally) under asan.

## Nvblox with Isaac ROS DP3 April 5, 2023
### What's New
- `nvblox` v0.0.4 with Ada GPU support, updated doxygen docs, new tutorials, and improvements for DNN-based person detection and separation during 3D scene reconstruction

## Mission Dispatch with Isaac ROS DP2 Oct 19, 2022
### What's New
- `mission-dispatch` introduced as a VDA5050-compatible cloud service 

## Nvblox with Isaac ROS DP1.1 September 1, 2022
### What's New
Isaac ROS-synchronized release including:
- `nvblox` add support for dropping blocks outside of a specified radius

## Nvblox with Isaac ROS DP1 June 30, 2022
### What's New
Isaac ROS-synchronized release including:
- `nvblox` minor updates to CMake targets and with additional README details

## Nvblox EA3 with Isaac ROS March 23, 2022
### What's New
Isaac ROS-synchronized release including:
- `nvblox` introduced as a GPU-accelerated TSDF and ESDF library for robots equipped with RGB-D cameras 

## Isaac 2021.1 Jun 25, 2021
### What's New
Initial public release including:
- Isaac-compatible drivers for specific cameras, lidars, and other sensors 
- Jetpack 4.5.1

### Limitations
This release has the following known limitations:
- The Isaac 2021.1 release only supports the Isaac Sim 2021.1 release. More recent versions of Isaac Sim will be incompatible.
