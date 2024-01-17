---
layout: post
title: CUAUV Projects
description: Contributions to autonomous submarine systems (kill switch and frame)
date: 2017-05-01
---

# Kill Switch

<p align="center">
  <img src="{{ 'assets/images/ksrender1_2.jpg' | relative_url }}" style="width: 75%"/> 
</p>

My first year on CUAUV (Cornell University Autonomous Underwater Vehicle), I was tasked with designing and machining a kill switch that would work on both of our submarines. The kill switch would turn on and off the major functions of the submarine to make it safe to handle, but the computer would still be online. In addition, it had a "mission start" button that would begin the autonomous mission stored in the submarine. Not only was I tasked with designing the mechanical part, I had to opportunity to design the custom board that would send the "kill" and "mission start" signals to a larger processing board inside the main hull.

<p align="center">
  <img src="{{ 'assets/images/killswitch-layout-tl_5_orig.png' | relative_url }}" style="width: 75%"/> 
</p>
  
The switch works by rotating the board encased in an acrylic tube, towards or away from a magnet that activates a hull effect sensor if the switch is in the designated position. There is a second hall effect sensor in the fore cap to send a mission start signal whenever the button is pushed. To show the current state of the submarine, there are three rows of LEDs, one for killed, unkilled, and mission start.

# Mini-submarine Frame

<p align="center">
  <img src="{{ 'assets/images/angle-front1_2_orig.png' | relative_url }}" style="width: 75%"/> 
</p>

During my tenure with CUAUV, we competed with a mini-submarine that was meant to complete tasks our main submarine may not have had time to complete. Continuing this tradition, I was tasked with creating a structurally sound, yet compact mini-submarine frame.
  
The main enclosures was required to hold are the Unified Hull Pressure Vessel (UHPV), two hot-swappable batter pods (which are interchangeable with the main submarine), six T-100 Blue Robotics thrusters, a hydrophones enclosure, and a kill switch.

<p align="center">
  <img src="{{ 'assets/images/msrender1_2.jpg' | relative_url }}" style="width: 75%"/> 
</p>
  
​The frame consists of seven large frame pieces that our team sent out to an outside manufacturer to have them water-jetted due to their complexity. Other smaller mounts were machined by members of the mechanical team, including myself
  
During the designing process, I used structural analysis software (ANSYS) to simulate the frame under different loading forces, ensuring it would stay intact under specified loading conditions.