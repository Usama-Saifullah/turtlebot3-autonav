# TurtleBot3 Autonomous Navigation with ROS

![TurtleBot3](http://www.robotis.com/service/images/product/turtlebot3/turtlebot3_models.png)

A ROS-based project for autonomous navigation of the TurtleBot3 robot in Gazebo simulation. Implements path planning using A* algorithm, obstacle avoidance, and waypoint following.

## Features

- **Gazebo Simulation**: Launch TurtleBot3 in a simulated world.
- **Teleoperation**: Manual control via keyboard input.
- **Autonomous Navigation**:
  - A* path planning with dynamic obstacle avoidance.
  - Real-time LiDAR-based obstacle detection.
  - Waypoint tracking with proportional control.
- **Visualization**: RViz integration for path visualization.

---

## Prerequisites

- **ROS Noetic** (Ubuntu 20.04)
- **TurtleBot3 Packages**:
  ```bash
  sudo apt install ros-noetic-turtlebot3-*
