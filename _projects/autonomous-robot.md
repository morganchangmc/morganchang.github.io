---
title: Autonomous Robot
meta: ENPH 253 | Jul – Aug 2025
tags: [Robotics, PCB Design, Mechanical Design]
cover: robot-hero.jpg
order: 1
summary: A fully autonomous robot built for a simulated Mars mission competition.
---
A fully autonomous robot built for a simulated Mars mission competition. I designed the chassis, drivetrain and end effectors, and designed, soldered and tested the power electronics.

## Detailed CAD
{% include img.html src="robot-cad.jpg" caption="Full model in Onshape, showing the front claw, rear claw, ESP CAM and user input module." %}

## Drivetrain
{% include img.html src="robot-drivetrain.jpg" caption="A differential drive with an adjustable gearing belt drive system." %}

## End effectors
{% include img.html src="robot-claw.jpg" caption="Two end effectors, designed and tested for picking up different objects. The front claw is shown." %}

## PCB design and testing
{% include img.html src="robot-pcb.jpg" caption="Power distribution board layout." %}
{% include img.html src="robot-power-board.jpg" caption="The assembled power distribution board. In total I soldered and tested a system of 8 PCBs for motor control, sensor input and microcontrollers." %}

## Software
The robot follows its course with a PID control loop in C++ using an IR array and IMU, and an ESP CAM running colour detection to track model aliens.
