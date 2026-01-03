---
layout: project
title: Rover Wheel CAD
description: Advanced CAD Project
technologies: [Autodesk Fusion]
image: /assets/images/nasarover.jpg
---
 
I designed a wheel for the Mars Rover Project Team using Autodesk Fusion 360. Some things that I focused on were tread design, dimensions, lightening hole shapes, etc.

![Photo of wheel]({{ "/assets/images/rover_wheel.jpg" | relative_url }}){: .inline-image-l}

![Photo of wheel]({{ "/assets/images/red_rover_wheel.jpg" | relative_url }}){: .inline-image-l}

The main focus was on treads. The treads had to be designed so that the sand could exit easily when the rover traversed across the Mars-simulated terrain. I added a straight edge to the ends of the tread to maintain a constant tread width and create consistent contact with the ground. In the middle, I added a curve to allow the sand to collect and flow outwards with the help of gravity. In order to avoid stress concentrations, I added fillets to all sharp edges.


As for the dimensions, I increased the diameter to 10.5 in and the width to 4 in so that the rover doesn't get stuck in holes. Increased diameter makes it easier to climb out of holes. A wheel escapes a hole by rotating up the exit slope, and with a larger radius, there is lesser curvature at the contact point of the hole. Larger radius also reduces how deep the wheel can fall inside a hole with the same width. As for increasing the width to 4 in, a wheel cannot fall into a hole that has a smaller width than the wheel. With a 4 in width, the hole must be wider than 4 in and deeper than 0.396 in (some calculations shown below) before the wheel sinks in and tries to escape.

![Photo of calculations]({{ "/assets/images/wheel_calculations.jpg" | relative_url }}){: .inline-image-l}

For the lightening holes, I added 20 curved lightening holes to reduce mass and preserve structural integrity. Lower mass leads to lower required motor torque and lower rotational inertia, which means easier acceleration and quicker turns. It's also easier to manufacture since it takes lesser time to print out and reduces the thermal gradients. I also ensured that there was enough space between the lightening holes so that the bars don't become too thin and buckle easily due to the heavy weight being carried by the wheel. The lightening holes were intentionally curved rather than left straight. This arched geometry allows controlled deformation under loading by allowing the holes to fall into themselves rather than being squished towards the center of the wheel.

Here are the front and side views of a previous wheel design that I printed out. 
![Photo of front view]({{ "/assets/images/prototype_full.jpg" | relative_url }}){: .inline-image-l}
![Photo of side view]({{ "/assets/images/prototype_side.jpg" | relative_url }}){: .inline-image-l}
This wheel was printed out using TPU from a Bambu Lab P2S printer. This design was 10.5 in tall and 9 in wide. It only printed out halfway because it was too wide and would have been used too much TPU if we continued to let it print. This is why I reduced the diameter to 4 in but still let it be wider than last year's design. Its treads were modeled after the Perseverance Rover but was changed because I received feedback that the soil that the rover would be traveling on would be different from the actual Martian soil. This wheel also lacked curvature, but I added a slight curve to the new design so that the rover could turn around quickly and easily without causing breakages at the edges of the wheel. I also changed the shape of the lightening holes by increasing the curvature at the edges. The curvature of the lightening holes allows the wheel to deform elastically under the carried weight in a controlled manner. Instead of deforming towards the center of the wheel, the lightening holes would collapse on themselves. By guiding this deformation, we are reducing the likelihood of unpredictable material behavior and improving durability when the wheel is carrying weight.
