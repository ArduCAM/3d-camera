OpenCV and Depth Map on Arducam Stereo Camera HAT
===========
(base on [stereopi-tutorial](https://github.com/realizator/stereopi-tutorial))


## Was tested in the following environment:
* Raspbian Buster, latest version recommended
* Python 3.7.3 (built-in)
* OpenCV 3.4.4 (pre-compiled, ‘pip’ from Python Wheels)
* StereoVision lib 1.0.3 (https://github.com/erget/StereoVision)

## Installing Python3.x Dependencies
* Installing the latest Raspbian
* sudo apt-get update && sudo apt-get install -y libhdf5-dev libhdf5-serial-dev libatlas-base-dev libjasper-dev libqtgui4 libqt4-test && sudo pip3 install opencv-python==3.4.6.27
* sudo pip3 install stereovision
* sudo pip3 install matplotlib
* Install [kernel driver](https://www.arducam.com/docs/arducam-obisp-mipi-camera-module/3-use-on-raspberry-pi/3-2-driver-installation/)
* git clone https://github.com/ArduCAM/3d-camera.git


**See [Depth Mapping on Arducam Stereo Camera HAT with OpenCV](https://www.arducam.com/docs/cameras-for-raspberry-pi/synchronized-stereo-camera-hat/opencv-and-depth-map-on-arducam-stereo-camera-hat-tutorial/) for details.**