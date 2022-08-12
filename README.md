# base64_subscriber
A ROS subscriber for subscribing a base64 image string and converting it to an OpenCV image.

## Installation

Go to your src folder of your catkin_ws and clone the repository:

```
cd ~/catkin_ws/src
git clone https://github.com/Michdo93/base64_subscriber.git
cd ~/catkin_ws
catkin_make
```

## Usage

You can run it like following:

```
rosrun base64_subscriber ImageSubscriber.py
```
