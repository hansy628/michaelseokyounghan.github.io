---
layout: archive
title: 
permalink: /projects/
author_profile: true
analytics: true
---

{% include base_path %}

The primary focus of my research revolves around the transformation of novel designs or concepts into practical robotic systems, aiming to create a tangible impact in our daily lives. These systems encompass crucial components such as actuators, sensors, and controllers. By harnessing creative designs or models, I strive to advance the performance, manipulability, and human-robot interaction of robots.



# Anthropomorphic Robotic Finger Design with Optical Fiber Tendon (2023-)
<img align="left" src="https://hansy628.github.io/mshan_project/files/prototype.jpg" alt="Photo" style="width: 300px; height: 320px; border-radius: 1px"/>
<img align="left" src="https://hansy628.github.io/mshan_project/files/finger_design1.jpg" alt="Photo" style="width: 360px; height: 320px; border-radius: 1px"/>
Currently working on developing a robotic finger inspired by human finger design. Likewise the human finger, this robotic finger has rigid bone for supporting the structure, flexible tendons for making motion, and sheaths for guiding and protecting.
This system consists of all-polymer materials for main structure and optical fiber tendons for not only transmitting the force but also sensing information of finger motion change. Since optical fiber tendons are able to reflect its deformation according to the tendon force, this finger can detect finger joint angle variation. Based on the neural network technique, how much joint angle changes corresponds to total light intensity of the fiber sensor.  


# Biomimetic Soft Actuator (2022-)
<img align="left" src="https://hansy628.github.io/mshan_project/files/lce_concept.jpg" alt="Photo" style="width: 180px; height: 200px; border-radius: 1px"/>
<img align="left" src="https://hansy628.github.io/mshan_project/files/Sequence 01.gif" alt="Photo" style="width: 180px; height: 200px; border-radius: 1px"/>
Since the nature organism muscle is actuated by repeating contraction and relaxation, it can make a motion more efficiently than other artificial actuators. 
The idea of this project comes from this question "Is it possible to make an unit muscle able to generate contraction and relaxation by any type of stimuli?". 
Liquid Crystal Elastomer(LCE) is one of the probable solutions. While through optical excitation this polymer can be deformed permanently, it can be restored by a certain range of heat source. 
Working on a new design, which is able to convey the heat source uniformly and be interfaced with other robot components.


# Grasping Control with a Novel Design of Soft Tactile Sensor (2021)
<img align="left" src="https://hansy628.github.io/mshan_project/files/softsensor.png" alt="Photo" style="width: 220px; height: 220px; border-radius: 1px"/>
<img align="left" src="https://hansy628.github.io/mshan_project/files/mrac_vid_1030_1.gif" alt="Photo" style="width: 400px; height: 300px; border-radius: 1px"/>
In this project, skin-inspired soft tactile sensor is developed to measure normal forces and assess the stick-slip behavior of objects contacting the silicone surface. 
This sensor is not only easy to fabricate but also straightforward to interpret the sensor signals according to the force.[here](https://onlinelibrary.wiley.com/doi/abs/10.1002/admt.202200406) 
On top of that, through the adaptive control technique, the sensor application is presented using the off-the-shelf gripper product. 
While object slipping occurs, the sensor provides lateral force information so that it is able to control how much should be gripped by the robotic grasper.[here](https://ieeexplore.ieee.org/abstract/document/10122010) 


# Motion Control of Minimally Invasive Surgical Robot (2019)
<img align="left" src="https://hansy628.github.io/mshan_project/files/misrobot.jpg" alt="Photo" style="width: 350px; border-radius: 1px"/>
<img align="left" src="https://hansy628.github.io/mshan_project/files/instrument_test.jpg" alt="Photo" style="width: 250px; height: 250px; border-radius: 1px"/>
Minimally invasive surgical(MIS) robot is known for the less of post-surgery effect since it can approach only small part of the body to incise or just use the natural orifice as well. 
In this project, my team and I worked on making precise motion of the surgical robot so that it can elevate the surgery performance. 
Theoretically, through kinematic and dynamic analysis of the tendon-driven robot, plausibility is presented [here](https://www.mdpi.com/2076-3417/9/19/4114). 
Technically, reliability of the system is also shown by comparing calculation results and actual using the position and orentation sensors in the real 3D space. 


# Locomotion Generation of Tensegrity Robot based on Iterative Learning Control (2014)
<img align="left" src="https://hansy628.github.io/mshan_project/files/tensegrity.jpg" alt="Photo" style="width: 220px; border-radius: 1px"/>
A tensegrity system is a highly flexible and balancing structure, which is made up of a rigid body and a tensile material. 
In this research, it is developed to explore an uncertain, rugged area by making its locomotion. Each actuator is connected to each side of tensegrity, which is the elastic spring component in this robot so that leads to deformation of the whole structure. 
However, in order to sustain its stability, it is necessary to keep a certain tendon force between on each vertext. 
Therefore, in this project, the dynamic analysis and system stability are presented to implement the robotic system. 
On top of that, the iterative learning control algorithm is applied for creating an improved performance of the robot. 
You can check "Locomotion of Three-Bar Tensegrity" video [here](https://www.youtube.com/watch?v=3nluj3a4f2s) and publication [here](https://ieeexplore.ieee.org/abstract/document/7064594). 


# Previous Projects (~2013)

Below projects were presented from the local competition or contest exhibition.
<img align="left" src="https://hansy628.github.io/mshan_project/files/prev_threetoone.jpg" alt="Photo" style="width: 980px; height: 220px; border-radius: 1px; padding: 1px 1px 10px 1px"/>

## A Balancing Bicycle(right)
Based on the inverted-pendulum control, this bicycle can maintain its balance. 
On the back of the bicycle, there is a flywheel that makes inertia momentum. 
Using this flywheel data and the gyro data of the bicycle body, we can control the attitude of the bicycle theoretically through the simulation.
## An Autonomous Vehicle(middle)
Using LIDAR sensor, this robot is able to detect obstacles so that avoid to head toward a fixed waypoint with a minimum distance while generating a local map.
## An Anti-Collision Device for Automobile Doors(left)
This work presents the electromagnetic locking system in an automobile door to prevent unexpected collision while opening.

