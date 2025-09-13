---
layout: post
title: Robotics & Computer Vision for Automated SLA 3D Printing Post-Processing
description:  Developed a ROS2-based system integrating robotic arms, custom grippers, and computer vision to automate support removal in Stereolithography (SLA) 3D printing. Designed and tested control workflows using ROS2, Rviz, and MoveIt, and created optimized gripper prototypes to handle dental parts printed on RapidShape systems.
skills: 
  - Robotics (UR5e arm, ROS2, MoveIt, Rviz)
  - Computer Vision
  - Python & ROS2 packages
  - Automation & Control Systems
  - Additive Manufacturing (SLA/DLP)
main-image: /back.jpg 
---

---
## Background
Post-processing in Stereolithography (SLA) 3D printing is still heavily manual, particularly for removing support structures. This project targeted automation of that workflow by leveraging robotic arms, ROS2 communication, and custom grippers.
<br>

## Methods
- Implemented ROS2 (Humble) on Ubuntu, connecting the UR5e robotic arm through Ethernet.
- Developed publisher-subscriber nodes for robotic arm communication and visualization.
- Utilized Rviz for real-time simulation and motion monitoring; MoveIt for kinematics and motion planning.
- Designed and 3D-printed optimized gripper attachments for secure handling of dental parts.
<br>

# Proposed Architecture
{% include image-gallery.html images="archi.jpg" height="600" %}<br>

## Key Results
- Demonstrated ROS2-based control and real-time visualization of UR5e robotic arms.
- Successfully prototyped and tested custom grippers capable of handling SLA-printed dental parts.
- Established groundwork for integrating dual-robot systems and vision-based gripping.

{% include image-gallery.html images="main.jpg" height="800" %} <br>
