# ROS2 ROS Robot With Camera Sensor

This repository contains a simulation of a three-wheeled robot equipped with a camera sensor, implemented using the Robot Operating System (ROS2). The simulation provides a platform for experimenting with robot control, perception, and navigation algorithms.

## Features

- Three-wheeled robot model: Simulated robot with three wheels for locomotion.
- Camera sensor: A simulated camera sensor for capturing the robot's surroundings.
- ROS 2 integration: The simulation is built on ROS 2, providing a modular and scalable framework for robotics development.
- Customizable: The simulation environment can be easily customized and extended to incorporate additional sensors, actuators, or functionalities.

## Prerequisites

- ROS 2: Make sure you have ROS 2 installed on your system. You can follow the installation instructions provided on the [ROS 2 website](https://index.ros.org/doc/ros2/Installation/).

## Installation

1. Clone this repository to your local machine: git clone https://github.com/ankitaryan404/ros_robot_with_camera_sensor.git
2. Build the ROS 2 workspace:
3. cd ros_robot_with_camera_sensor <br>
  colcon build


## Usage

1. Source the ROS 2 installation:

```source /install/setup.bash```

2. Launch the simulation:
 
```ros2 launch my_robot_bringup my_robot_gazebo.launch.xml```

