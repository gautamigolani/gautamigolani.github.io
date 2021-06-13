---
layout: distill
title: Framework of Repetitive Path Planning & Control for UR5 Manipulator
description: Planning & control model for manipulators
img: 
importance: 2
category: academic
date: 2021-06-09

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

<h2 id="References">References</h2>
<details>
<summary>List of references for this project</summary>
<br>
<ol align="justify"> 
    <li>https://www.universal-robots.com/</li>
    <li>W. Khalil and E. Dombre, Modeling, Identification and Control of Robots, Elsevier, 2004.</li>
    <li>J. J. Craig, Introduction to Robotics: Mechanics and Control, Pearson/Prentice Hall Upper Saddle River, NJ, 2005.</li>
    <li>M. W. Spong, S. Hutchinson, and M. Vidyasagar, Robotics, Dynamics and Control, John Wiley & Sons, NY, 2005.</li>
    <li>B. Siciliano, L. Sciavicco, L. Villani, and G. Oriolo, Robotics: Modeling, Planning and Control, Springer-Verlag, London, 2009.</li>
    <li>F. L. Lewis, D. M. Dawson, C. T. Abdallah, Robot Manipulator Control: Theory & Practice, Marcel Dekker, Inc., NY, 2003.</li>
    <li>P. M. Kebria, S. Al-wais, H. Abdi, and S. Nahavandi, "Kinematic and dynamic modelling of UR5 manipulator," in Proc. IEEE Int. Conf. Syst., Man, Cybern., 2016, pp. 4229-4234.</li>
    <li>K. Kufieta, Force Estimation in Robotic Manipulators: Modeling, Simulation and Experiments, UR5 as a case study, Thesis, Norwegian University of Science and Technology, 2014.</li>
    <li>M. R. P. Ragazzon, Robot Manipulator Collision Handling in Unknown Environment without using External Sensors, Specialization Project, Norwegian University of Science and Technology, 2012.</li>
    <li>K. P. Hawkins, Analytic inverse kinematics for the universal robots, Technical report, Georgia Institute of Technology Publications, 2013.</li>
    <li>R. S. Andersen, Kinematics of a UR5, Technical report, Aalborg University, 2018.</li>
    <li>D. Guo, F. Xu, and L. Yan, "New pseudoinverse-based path-planning scheme with PID characteristic for redundant robot manipulators in the presence of noise," IEEE Trans. Control Syst. Technol., vol. 26, no. 6, pp. 2008-2019, 2018.</li>
    <li>A. S. Deo and I. D. Walker, "Minimum effort inverse kinematics for redundant manipulators," IEEE Trans. Robot. Autom., vol. 13, no. 5, pp. 767-775, 1997.</li>
    <li>A. De Luca, L. Lanari, and G. Oriolo, "Control of redundant robots on cyclic trajectories," in Proc. IEEE Int. Conf. Robot. Autom., 1992, pp. 500-506.</li>
    <li>T. Shamir and Y. Yomdin, "Repeatability of redundant manipulators: Mathematical solution of the problem," IEEE Trans. Autom. Control, vol. 33, no. 11, pp. 1004-1009, 1988.</li>
    <li>S. Seereeram and J. T. Wen, "A Global Approach to Path Planning for Redundant Manipulators," in IEEE Trans. Robot. & Autom., vol. 11, no. 1, pp. 152-159, 1995.</li>
    <li>C. A. Klein and C.-H. Huang, "Review of pseudoinverse control for use with kinematically redundant manipulators," IEEE Trans. Syst., Man, Cybern., vol. SMC-13, no. 2, pp. 245-250, 1983.</li>
    <li>Y. Zhang and Z. Zhang, Repetitive Motion Planning and Control of Redundant Robot Manipulators, Springer-Verlag, New York, 2013.</li>
    <li>T. Shamir, "The singularities of redundant robot arms," Int. J. Robot. Res., vol. 9, no. 1, pp. 113-121, 1990.</li>
    <li>L. T. Dung, H-J. Kang, Y-S. Ro, "Robot manipulator modeling in MatlabSimmechanics with PD control and online Gravity compensation," IEEE Int. Forum on Strategic Tech., pp. 446-449, 2010.</li>
    <li>F. Piltan, M. H. Yarmahmoudi, M. Shamsodini, E. Mazlomian, A. Hosainpour, "PUMA-560 Robot Manipulator Position Computed Torque Control Methods Using MATLAB/SIMULINK and their Integration into Graduate Nonlinear Control and MATLAB Courses," Int. Journal of Robot. & Autom. (IJRA), vol. 3, issue 3, pp. 167-191, 2012.</li>
</ol>
</details>





