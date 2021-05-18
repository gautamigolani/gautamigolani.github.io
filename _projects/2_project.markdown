---
layout: page
title: Framework of Repetitive Path Planning and Control for UR5 Manipulator
description: Planning and control model for robot manipulators
img: /assets/img/fig1.jpg
importance: 2
category: academic
---

<div id="toc_container">
<p class="toc_title">Contents</p>
<ul class="toc_list">
    <li><a href="#Model">1 Complete Model</a>
    <ul>
        <li><a href="#Part1">1.1 Inverse Kinematics and Path Planning</a></li>
        <li><a href="#Part2">1.2 Dynamics and Control</a></li>
        <li><a href="#Part3">1.3 Model of the Robot</a></li>
    </ul>
</li>
<li><a href="#Simulations">2 Simulations</a></li>
<li><a href="#Conclusion">3 Conclusion</a></li>
<li><a href="#References">4 References</a></li>
</ul>
</div>  

<br>

For the past few years, manipulators have been used for a number of different applications mainly due to their cost-effectiveness and flexibility, apart from other numerous advantages they offer. With the thought of exploring manipulators in detail, I have developed a complete path planning and control framework for a manipulator in this project, giving an insight into the area of planning for the UR5 manipulator (case study). The kinematic equations are first derived, following which the computed-torque controller is designed with the help of the dynamic equations. For path planning, a repetitive motion planning (RMP) scheme is analyzed and implemented on the manipulator. The models for the same are developed in Simulink while Simscape Multibody presents a new way of visualizing the model and observing its movement. Simulations are carried out at a later stage to verify whether the results obtained have substantiated the planning model or not.

<br>

<h2 id="Model">Complete Model</h2>
<h3 id="Part1">Inverse Kinematics and Path Planning</h3>

In general, there are a number of path planning schemes available for manipulators, but here the focus will be on the RMP scheme.
By using the differential kinematic equation stated below, the path planning model for the robotic manipulator can be modeled.
<center>
    <img src="https://latex.codecogs.com/svg.latex?r_{d}&space;=&space;f(\theta)" title="r_{d} = f(\theta)" />
</center>
<br>
where <img src="https://latex.codecogs.com/svg.latex?\small&space;r_{d}\in&space;R^m" title="\small r_{d}\in R^m" /> is the task coordinate and <img src="https://latex.codecogs.com/svg.latex?\small&space;f(\theta)\in&space;R^n" title="\small f(\theta)\in R^n" /> is the joint coordinate, respectively.
Differentiating the above equation w.r.t time,
<br> 
<center>
<img src="https://latex.codecogs.com/svg.latex?\dot{r_{d}}&space;=&space;J(\theta)\dot{\theta}" title="\dot{r_{d}} = J(\theta)\dot{\theta}" />
</center>
<br>
where <img src="https://latex.codecogs.com/svg.latex?\small&space;J(\theta):R^n-R^m" title="\small J(\theta):R^n-R^m" /> is the Jacobian matrix.




