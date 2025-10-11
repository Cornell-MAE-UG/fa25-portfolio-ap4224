---
layout: project
title: Test
description: Rigid Bar Max Possible Weight
technologies: [MATLAB, python]
image: /assets/images/function-graph.png
---


As part of a Statics class assignment, we were asked to design a rigid bar of fixed length with 3 pin supports that could lift the maximum possible weight to the highest possible height.

This is a diagram:

![Image 10-10-25 at 4 58 PM](https://github.com/user-attachments/assets/3788ef87-fca1-4d51-abec-60dc8e50bdeb)


This is how I solved the problem:

```python
    #A is the pin on the floor and holding the end of the bar
    #B is the pin connected to the wall and the other end of the bar
    #C is the pin on the floor holding the actuator

    L=1.3 #length of the bar (in m);
    d=0.4 #length from point A to actuator (in m)
    x=1.2 #length from A to C (in m)
    h=0.5 #length from C to B (in m), also the max height
    
    F_max=58000 #RSA Actuator max force (in N)
    pheta=22.62 #angle from A to the ground

    W_max=(F_max*d*cos(pheta))/(L*cos(pheta)) #max weight that can be lifted from the height h=0.5m
    plot();
```
git add .
git commit -m "<Commit Edit>"
git push origin main
