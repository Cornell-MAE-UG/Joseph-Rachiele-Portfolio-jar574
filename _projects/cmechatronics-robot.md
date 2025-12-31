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


#### Robot Strategy and Strategy Overview
From a mechanical standpoint, our robot was designed to filter as many cubes as possible and store them in a flexible back bounding box. To complete this goal, we placed cardboard arms in the front to funnel the cubes into the opening on the sides of the cardboard back box. The flexible cardboard box in the back of the chassis allowed for our robot to be more maneuverable when coming into contact with opposing robots. The cardboard back bounding box was compressed with a string attached to a servo in order to fit into the 8x8” requirement. Once the robot started, the servo (as seen attached at the top of the chassis) rotated which loosened the string and allowed the back cardboard box to expand out to our 12x12” bounding box.

<img src="{{ '/assets/images/mech-robot.jpg' | relative_url }}" alt="Mechatronics Robot" style="max-width: 700px; width: 100%; height: auto; display: block; margin: 2rem auto;">

#### Design Process and Reflection
Our process for designing, prototyping, and testing our robot resembled a 2 stage development plan. On one side of the team, we prioritized our focus on our weekly milestones, making sure to complete all of those in a timely manner. While on the other side of the team, when we had free time, we focused on the robot competition design and how we would implement new strategies and use our sensor to our advantage, without running out of time or pins on the board. Our process of designing was to first handle the completion of the milestones, then in our spare time work on the CAD of our robot, design of our machine, and strategy for the competition, which were constantly changing as more progress was made through each milestone. Before the competition, we settled on a cardboard based design which utilized the flexibility yet rigidity of cardboard, for the cube catch-basin, along with a 3D printed QTI sensor mount. We did not have significant roadblocks, but rather some unforeseen hiccups in some of the milestones and sensor implementation, such as having to implement a second QTI and having to recut and reshape the cardboard several times. We ultimately found that it was easiest to complete our mechanical robot and sensor design and then attach the cardboard at the very end. We also made the decision to avoid the color sensor and replace it with a second QTI sensor. This change caused a minor setback since we needed to make changes to both the code and mechanical design. Overall, there weren’t many roadblocks, just minor hiccups that we would have to work through, like figuring out the difficult code implementation of 2 QTI sensors.

<img src="{{ '/assets/images/CADofBlades.jpg' | relative_url }}" alt="CAD of turbine blades" style="max-width: 700px; width: 100%; height: auto; display: block; margin: 2rem auto;">

#### Competition Analysis
At first, we were nervous about our design because many groups opted for a stronger material for cube collection, such as sheet metal or acrylic. After a few rounds, we quickly realized that having a flexible material like cardboard worked to our advantage. When other robots crashed into ours, nothing would happen because the cardboard would shift and the main chassis would continue moving forward and collecting cubes. Unlike other robots, our robot was able to maintain the majority of the cubes that we already collected in our back collection box while also staying within the blue and yellow board by avoiding the border. In terms of functionality, our robot moved exactly how we planned. It went to the middle of the board, turned left to collect the cubes, and then turned 90 degrees every time it hit the black border for the full minute. 

**Below is a flowchart of our Arduino commands:**
<img src="{{ '/assets/images/Flowchart.jpg' | relative_url }}" alt="CAD of turbine blades" style="max-width: 700px; width: 100%; height: auto; display: block; margin: 2rem auto;">

Our group was undefeated in the round robin and we made it to the quarter finals, landing us 5th place in the competition. Our first and only loss was to the champion of the competition. If we were to complete this project again, our one change would be adding another 6V battery to make the robot move faster. The speed of our robot was its only weakness when compared to other robots. When we lost in the quarter finals, it was due to the fact that the other robot was faster and got to the cubes before our robot had a chance to collect them.

**Below are a labelled diagram and picture of our circuit:**
<img src="{{ '/assets/images/Mech-Wiring.jpg' | relative_url }}" alt="Robot Wiring" style="max-width: 700px; width: 100%; height: auto; display: block; margin: 2rem auto;">

<img src="{{ '/assets/images/Circuit-Diagram.jpg' | relative_url }}" alt="Circuit Diagram" style="max-width: 700px; width: 100%; height: auto; display: block; margin: 2rem auto;">

#### Conclusion
Looking back, there are many things that we would have done differently. A few main points that we would change would be: 1. Design a mechanism to capture and hold the block, 2. Make our robot faster, 3. Increase the range of our net region. With regards to the first point, we noticed during competition that sometimes blocks would fall out of our capture area due to our turning method or radius. In order to avoid this, we would  improve our capture method so as to restrict the blocks from leaving the collection box. For the second point, our robot overall was sluggish, taking too much time to release the cardboard net and turning its wheels and moving forward with minimal speed. Increasing the speed would only have improved our results. For the last point, we really liked our idea of releasing a larger region to capture blocks after starting the competition to maximize our bounding box, but if we were to go back we would maybe use a more elastic, bouncing-back, material to help increase the region even more. 



[📄 View MAE 3780 Complete Commented Arduino Code (PDF)]({{ "/assets/Mechatronics-Final-Report.pdf" | relative_url }})