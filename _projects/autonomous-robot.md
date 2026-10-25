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

{% include row.html l_src="robot-drivetrain.jpg" l_title="Drivetrain" l_text="A differential drive with an adjustable gearing belt drive system." r_src="robot-claw.jpg" r_title="End effectors" r_text="Two end effectors, designed and tested for picking up different objects. The front claw is shown." %}

{% include row.html l_src="robot-pcb.jpg" l_title="PCB design" l_text="Layout of the power distribution board, one of the boards in the robot's electrical system." r_src="robot-power-board.jpg" r_title="Testing" r_text="I soldered and tested a system of 8 PCBs for motor control, sensor input and microcontrollers. The assembled power distribution board is shown." %}

## Software
The robot follows its course with a PID control loop in C++ using an IR array and IMU, and an ESP CAM running colour detection to track model aliens.
