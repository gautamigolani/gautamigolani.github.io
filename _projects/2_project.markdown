---
layout: distill
title: Framework of Repetitive Path Planning & Control for UR5 Manipulator
description: Planning & control model for manipulators
img: 
importance: 2
category: academic
date: 2021-06-09

bibliography: 2021-06-09-distill.bib

nocite: '@*'

authors:
  - name: Gautami Golani
    url: "https://gautamigolani.github.io/"
    affiliations:
      name: NUS, Singapore
 
---

> This project was done uner the supervision of <a href="https://www.eng.nus.edu.sg/ece/staff/ge-shuzhi-sam/">Prof. Sam Shuzhi Ge</a> at the Control & Simulation Lab at NUS, Singapore from March 2019 - November 2019.

## Abstract

For the past few years, manipulators have been used for a number of different applications mainly due to their cost-effectiveness and flexibility, apart from other numerous advantages they offer. With the thought of exploring manipulators in detail, I have developed a complete path planning and control framework for a manipulator in this project, giving an insight into the area of planning for the UR5 manipulator (case study). The kinematic equations are first derived, following which the computed-torque controller is designed with the help of the dynamic equations. For path planning, a repetitive motion planning (RMP) scheme is analyzed and implemented on the manipulator. The models for the same are developed in Simulink while Simscape Multibody presents a new way of visualizing the model and observing its movement. Simulations are carried out at a later stage to verify whether the results obtained have substantiated the planning model or not.

## Demo

<center>
<div id="videoal">
    <div class="video">
        <video controls>
            <source src="/assets/img/ur_bef_cont.mp4" type="video/mp4">
        </video>
    </div>
    <div class="video">
       <video controls>
           <source src="/assets/img/ur_aft_cont.mp4" type="video/mp4">
       </video>
    </div>
</div>
<div class="caption">
Visualization of the manipulator before and after implementation of the scheme and controller
</div>
</center>

## Code

The code for this project will be available on GitHub soon!






