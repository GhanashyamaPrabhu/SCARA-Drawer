# SCARA Drawing Robot

This project implements a SCARA (Selective Compliance Assembly Robot Arm) robotic system capable of reproducing drawings by converting images into robot motion trajectories.

The system converts image paths into Cartesian coordinates and uses inverse kinematics to control a SCARA robot arm that draws the image on paper.

---

## Project Overview

The goal of this project is to explore robotic manipulation, kinematics, and motion planning by building a robotic drawing system.

The pipeline converts input images into trajectories that can be executed by a 2-DOF SCARA robot.

---

## System Pipeline

Image Input  
→ Path Extraction  
→ Coordinate Scaling  
→ Inverse Kinematics  
→ Motor Command Generation  
→ Robotic Arm Drawing

---

## Key Concepts Implemented

• SCARA robot kinematics modeling  
• Forward and inverse kinematics computation  
• Image-to-path conversion for robotic drawing  
• Trajectory generation for smooth pen motion  
• Stepper motor control via Arduino  
• Coordinate transformation between image and robot frame  
• Calibration of link lengths and workspace limits

---

## Technologies Used

Python  
Arduino  
Robotics Kinematics  
Motion Planning  
Computer Vision

---

## Applications

Robotic drawing systems  
Industrial SCARA robot study  
Robotics education  
Automation and motion planning research

---

## Inspiration

This project builds upon open-source SCARA drawing robot implementations and explores robotic kinematics and trajectory control for automated drawing.
