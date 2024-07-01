# ROSMASTERX3-AMR
This repository presents a Autonomous Mobile Robot (ROSMASTERX3) that can be used to carry payloads in warehouse. The goal was to develop an autonomous navigation system capable of navigating through uncharted indoor environments using LIDAR and RGB-depth cameras.

# Problem Statement
In today's technological era, there is a growing demand for autonomous navigation systems that can navigate from one point to another within uncharted territories. Traditional navigation methods, which often rely on GPS, may not be reliable in indoor and GPS-denied environments. Hence, this project aims to develop a robust and adaptive solution that involves building a map of an unexplored terrain with high accuracy and precision while simultaneously localizing the robot on the map.

# Project Objectives
1. 2D Point Cloud Map Generation: Generate a 2D point cloud of a closed environment using the ROSMASTER X3 Robot equipped with a 2D LIDAR, by implementing the GMapping SLAM Algorithm.
2. Autonomous Navigation: Demonstrate functionalities like point-to-point autonomous navigation, multi-point autonomous navigation, and obstacle avoidance.
3. 3D Map Generation: Generate a 3D map of the same closed environment using an RGB-depth camera and the RTAB 3D Visual SLAM Algorithm.
4. 3D Navigation: Attempt to perform the above functionalities using the 3D Visual Map (Note: This objective faced technical challenges and was not fully accomplished).

# Scope
1. Implement open-source 2D SLAM and 3D Visual SLAM algorithms for generating point cloud maps.
2. Use an open-source navigation algorithm for autonomous navigation.
3. Focus on building an autonomous navigation system for indoor environments only.
4. Excludes development of new SLAM algorithms or motion planning algorithms and 3D point cloud maps using LIDAR.
