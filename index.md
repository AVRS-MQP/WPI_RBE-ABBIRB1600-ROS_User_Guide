# WPI_RBE-ABBIRB1600-ROS_User_Guide

### Description

This Site is a hub for examples of past ROS-I projects and help getting setup up with ROS-I on WPI's ABB-IRB-1600 Robotic arm. 

# Examples

As other MQPs and Industrial projects create more examples feel free to make a pull request on this repo to add your repo as an example.

- [Template](https://github.com/AVRS-MQP/template_ws)

A minimal template based on the code of AVRS and Seurobot project. Includes corrected URDF and launch files over ROS-I Experimental branch. Has packages and template code for using Python to C++ ROS action server/client pair to enable motion planning in Python. 

- [AVRS (Automatic Vehicle Recharging Station) - MQP](https://github.com/AVRS-MQP/AVRS 
)

The goal of this project is to automatically plug in autonomous electric vehicles, thus automating one of the last steps a level 5 autonomous vehicle would need for complete independence from human assistance. For the project we are using an ABB-IRB 1600 industrial robotic arm, a custom end effector capable of opening and closing the charging port as well as tool changing between 2 charging port standards, custom computer vision / point cloud processing software, as well as robotic arm kinematic software. This is accomplished using ROS-I.


- [Seurobot](https://github.com/RBE4815-Team6/Seurobot)

This project was an exercise for RBE/ME 4815 in using an industrial robotic arm to perform the complex task of drawing an image in the style of pointillism. Custom tooling was made to hold three dry erase markers to draw pre-processed images. Accomplishing this task required numerous frame transformations between the markers and precise motion to avoid damaging the tooling. The real-time logic needed to perform this task required the use of ROS to control the arm. Using ROS allowed us to write our control software in Python and easily process images. 

- [Catching Balls with a Robotic Arm](www.google.com)

This project was also an exercise for RBE/ME 4815 using an industrial robotic arm to catch balls thrown towards the arm in a hoop held b an end effector. Two Pixy cameras were used to locate a ball and predict its trajectory. The arm was then moved to a point along the trajectory in order to catch the ball. This project was done in ROS which had too much overhead to move the arm quickly enough. Howevever, the arm was moved to the correct location by messages sent but not received in real time. Unlike both of the previous projects, this was all done on a laptop rather than the machine in Washburn Shops and includes a guide for setting up a ROS system.



# Setup Guide
A detailed guide to setting up ROS-I as done by all projects listed above can be found [here]. A number of links to ROS Wiki tutorials and downloads are provided and are all necessary. 

# Usage 
All three of these projects were done on the ABB-IRB 1600 6/1.45 arm at WPI in Washburn Shops Room 108. In their current state, they will only function correctly on that model of arm. However, it is possible to modify them or take components for other applications. 

