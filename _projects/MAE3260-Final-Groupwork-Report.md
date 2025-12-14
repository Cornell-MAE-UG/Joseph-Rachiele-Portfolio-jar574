---
layout: project
title: 3260 Final Groupwork Report
description: Drone Dissection
technologies: [MATLAB]
image: /assets/images/drone.jpg
---

For System Dynamics, my group decided to dissect a drone in order to analyze the dynamics and controls of the system.

I was inspired by this old radio when I made this rendering:

![Photo of old radio]({{ "/assets/images/old-radio.jpg" | relative_url }}){: .inline-image-l}

Our drone is battery powered with four rotating blades. The battery also powers the LED light in the center of the drone. To start the drone, press the power button which activates the LED and indicates that the drone is on. To activate the propellers and get the drone to fly, the drone must be tossed into the air. The drone’s sensor will detect its downward motion and the propellers will rapidly accelerate to propel the drone up and maintain itself in the air. 
Once in the air, the drone will then respond to motion and objects detected by its sensors. There is a sensor that will detect any objects below it and will send more power to the propellers causing them to accelerate and generate a lift force to propel the drone higher. The instructed way to fly the drone is by moving your hand towards the drone from below it, which will accelerate the propellers and cause the drone to lift.

The lateral and forward-backwaerd motion of the drone is dependent upon an uneven rotation of the blades which is dictated by a feedback system dynamic. When your hand goes under the drone and also moves forward the back propellers will accelerate more than the front propellers. This feedback will push the drone forward. The same and opposite can be done to push the drone backwards. The drone will also move laterally away from objects or your hand. The drone will also react after hitting objects, thus there is a protective plastic shell to shield the propellers from its semi-frequent crashes (shown in image 3).

See (the hopefully working) PDF for more details.