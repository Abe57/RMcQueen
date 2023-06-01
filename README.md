Engineering materials
====

This repository contains engineering materials of a self-driven vehicle's model participating in the WRO Future Engineers competition in the season 2022.

## Content

* `t-photos` contains 2 photos of the team (an official one and one funny photo with all team members)
* `v-photos` contains 6 photos of the vehicle (from every side, from top and bottom)
* `video` contains the video.md file with the link to a video where driving demonstration exists
* `schemes` contains one or several schematic diagrams in form of JPEG, PNG or PDF of the electromechanical components illustrating all the elements (electronic components and motors) used in the vehicle and how they connect to each other.
* `src` contains code of control software for all components which were programmed to participate in the competition

## Introduction

This project uses parts from the 31313 EV3 set made by Lego. The robot was programmed using the EV3 Classroom App.
This car-shaped robot uses 3 motors (2 large, 1 medium) and 3 sensors (proximity, color, touch).

### Movement

The robot uses it's large motors to go forwards or backwards, which move the wheels in that direction..
To turn it uses the medium motor, that rotates the front wheels and the vehicle left and right.

### Sensors

It detects when an object is near and slows down, then it reverses to half of it's total current path.
If it detects green using the color sensor, it will turn left.
If it detects red, it turns right.

If the touch sensor in the back detects a press, it will go forward to halfway of it's current path, then turn to the opposite of the last direction.
