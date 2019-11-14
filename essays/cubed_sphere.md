---
layout: essay
type: essay
title: Cubed Sphere Simulator
# All dates must be YYYY-MM-DD format!
date: 2012-08-07
labels:
  - Simulator
  - Differential equations
  - Numerical analysis
  - C++
  - OpenGL
---

<img class="ui image" src="/images/CubedSphere_pic.png">

Cubed Sphere Simulator is an environment for solving differential equations on the sphere. 

The method uses a grid created on a cube and projected on a sphere. Several smoothing techniques are applied for smoothing the points for having as equal distribution of points in the space as possible. The simulator implements various ways of accessing the neighbors and traversing the grid. Also several most used schemes are implemented. It is possible to split the regions based on the area of the interest.

Implementation of the cubed sphere simulator using Euler’s explicit and implicit schemes, locally one-directional decomposition, classical Runge-Kutta method and fourth-order strong stability preserving schemes.


<div style="margin-top: 10px; " class="ui center aligned grid">
    <div class="middle aligned column">
        <embed src="https://Li-JJ.github.io/images/cubed_sphere.pdf" width="800px" height="2100px" />
    </div>
</div>
