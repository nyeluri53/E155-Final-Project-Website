---
layout: page
title: Project Overview
permalink: /
exclude: true
---

# Project Abstract

Welcome to our MicroPs final project.
We are building a split flap clock.



<div style="text-align: left">
  <img src="./assets/img/Logo.png" alt="logo" width="100" />
</div>


# Project Motivation

# New Hardware
* Stepper Motor: One piece of new hardware we hadn’t used before were stepper motors. Unlike traditional motors, a stepper motor allows for precise control over angular displacement, making it an ideal choice for the movements needed in rotating the flaps of the clock. The stepper motor divides a full rotation into a series of steps, and each step corresponds to a specific angular displacement. This level of control ensures accurate positioning of the flaps, contributing to the overall precision and reliability of the clock's rotation amounts.
* Hall Effect Sensors: In order to synchronize the stepper motor with the physical position of the flaps, we introduced a Hall effect sensor. When the flap spool containing the magnet reaches the designated home position, the Hall effect sensor registers the magnetic field, signaling that the flaps are in their home state. This serves as a pivotal reference point for the system, allowing it to recalibrate and ensure accurate timekeeping. Essentially, the Hall effect sensor acts as a positional marker, providing feedback to the control system about the current state of the flaps. This information is instrumental in maintaining synchronization and preventing drift in the display over time.

# System Block Diagram

