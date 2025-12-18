---
layout: project
title: Blade Design (new)
description: Blade Design Project for Fluids Lab
technologies: [MATLAB, CAD, LabView, Excel]
image: /assets/images/Blades.jpg
---


This project focused on the design, fabrication, and experimental evaluation of small wind-turbine blades optimized for safe operation and maximum power extraction under constrained operating conditions. The blades were designed to operate at a fixed rotational speed of 1500 RPM under a mean free-stream velocity of 4.59 m/s, while satisfying geometric constraints. 

![Photo of CAD]({{ "/assets/images/CADofBlades.jpg" | relative_url }})


Safety considerations guided all design choices. From Lab 5 and in class analysis, the dominant failure modes were identified to be flapwise bending fracture and uncontrolled overspeeding due to torque brake failure. A blade length of 4 inches was selected to maintain acceptable factors of safety for both failure modes. At the target rate of 1500RPM and upper-bound free-stream velocity of 7.74 m/s, our length selection maintained a factor of safety of 1.24 with respect to the torque brake limit and 10 with respect to flap wise bending. While our conservative design ensured structural integrity, it severely diminished power outputs.    

We performed aerodynamic optimization calculations on the NACA 4412 airfoil at a Reynold’s number of approximately 50,000. The blade twist distribution was optimized to maintain an angle of attack of 8.5 degrees, which corresponds to the maximum lift-to-drag ratio for this airfoil. 

![Photo of Blades] ({{ "/assets/images/old-radio.jpg" | relative_url }})

Our target experimental wind tunnel speeds were 4.3 m/s, 5.5 m/s, and 6.1 m/s. For each wind speed, we first set the torque brake applied voltage to 0, then carefully ramped the wind tunnel fan frequency up to reach the target speed. We allowed approximately 30 seconds to allow flow to reach a steady state before taking an initial data point. We then applied the torque brake in small increments of 0.2 V, 0.3 V, or 0.5 V for each wind speed, respectively, which allowed us to gather approximately the same number of data points for each wind speed. After each adjustment to the torque brake, we again allowed approximately 30 seconds before taking data to allow the flow to steady.

Results form torque and power graphs at freestream of 5.5 m/s included below:


![Photo of old radio] ({{ "/assets/images/Results5.5.jpg" | relative_url }})

Through this project, we were able to get an idea of the real-life obstacles of wind turbine design that are not necessarily quantifiable by a well-known mathematical model or law presented in class. We successfully designed a safely-operating blade, gathered meaningful data, and reflected on our results while identifying shortcomings of our design and experimental process.



