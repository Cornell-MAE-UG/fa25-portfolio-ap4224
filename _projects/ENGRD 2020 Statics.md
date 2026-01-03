---
layout: project
title: Statics Class Project I
description: Rigid Bar Max Possible Weight
technologies: [MATLAB, python]
image: /assets/images/ritz.jpeg
---


As part of a Statics class assignment, we were asked to design a rigid bar of fixed length with 3 pin supports that could lift the maximum possible weight to the highest possible height.


This image shows what the problem was and how I solved it:

![Photo of wheel]({{ "/assets/images/mech.jpg" | relative_url }}){: .inline-image-l}
A is the pin on the floor and holding the end of the bar
B is the pin connected to the wall and the other end of the bar
C is the pin on the floor holding the actuator

L=1.3 #length of the bar (in m);

d=0.4 #length from point A to actuator (in m)

x=1.2 #length from A to C (in m)

h=0.5 #length from C to B (in m), also the max height
    
F_max=9000 #RSA Actuator max force (in N)

pheta=24.62 #angle from A to the ground
