---
layout: project
title: Mechatronics Robot
description: Mechatronics Robot
technologies: [MATLAB, SolidWorks, Sensors]
image: /assets/images/mech-robot.jpg
---

In the spring of 2025, I participated in a robot competition sponsored by ASML for my mechatronics class. This semester long project culminated in a fun competition where the entire class faced off in a round robin style competiton. Two of my friends and I formed a group and placed 5th overall our of 65 groups.

#### Competition Details & Constraints
The objective of the "Cube Craze" robot project is to design and build a robot that collects cubes in an arena. The goal of each match is to gather more cubes than your opponent's robot by the end of a one minute period. Whichever robot collected more cubes within is determined to be the winner.

Each team needs to build one robot from the materials provided which mainly included: a color sensor, a QTI sensor, servo motors, mirco servos, a breadboard, ultrasonic sensors (for proximity), LEDs, wheels, plastic chassis, and other less notable items. We were also given a budget of $40 for additional materials. 

Pictured below is the competition board with dimensions. Cubes would be placed in the center as labelled and there was a 3 inch black border around the perimeter of the board. Teams would be dtermined to start on the yellow or blue section at random so this was also an important details to consider when programming our color and QTI sensors.

<img src="{{ '/assets/images/Competition-Arena.jpg' | relative_url }}" alt="Arena" style="max-width: 700px; width: 100%; height: auto; display: block; margin: 2rem auto;">

At the beginning of each match the robot must fit inside an 8"x8" square with no height limit. However, after the match starts, the robot may extend beyond its starting configuration but at any time must fit inside an imaginary 12" diameter cylinder (no height limit). Items dropped (i.e. purposefully detached from the robot) do not need to fit inside the 12" diameter cylinder.


#### Team Strategy

Robot Strategy and Strategy Overview
	From a mechanical standpoint, our robot was designed to filter as many cubes as possible and store them in a flexible back bounding box. To complete this goal, we placed cardboard arms in the front to funnel the cubes into the opening on the sides of the cardboard back box. The flexible cardboard box in the back of the chassis allowed for our robot to be more maneuverable when coming into contact with opposing robots. The cardboard back bounding box was compressed with a string attached to a servo in order to fit into the 8x8” requirement. Once the robot started, the servo (as seen attached at the top of the chassis) rotated which loosened the string and allowed the back cardboard box to expand out to our 12x12” bounding box.


<img src="{{ '/assets/images/CADofBlades.jpg' | relative_url }}" alt="CAD of turbine blades" style="max-width: 700px; width: 100%; height: auto; display: block; margin: 2rem auto;">

<img src="{{ '/assets/images/CADofBlades.jpg' | relative_url }}" alt="CAD of turbine blades" style="max-width: 700px; width: 100%; height: auto; display: block; margin: 2rem auto;">



<img src="{{ '/assets/images/CADofBlades.jpg' | relative_url }}" alt="CAD of turbine blades" style="max-width: 700px; width: 100%; height: auto; display: block; margin: 2rem auto;">