---
title: "Fearful Frankie"
excerpt: "Autonomous Robot Pet"
header:
  teaser: /assets/img/Mechatronics.JPEG

gallery:
  - url: /assets/img/Mechatronics.JPEG
    image_path: /assets/img/Mechatronics.JPEG
    alt: "Fearful Frankie Front View"
---

<img src="/assets/img/Mechatronics.JPEG" alt="Fearful Frankie" style="width:900px;"/>

## About	
Autonomous robots often struggle to mimic lifelike behaviors due to static movements and limited responsiveness. As a part of an solo class project, a small, autonomous robot dog named Fearful Frankie was developed, with the goal of creating realistic, animal-like interactions and dynamic movement patterns. Equipped with ultrasonic sensors, Frankie constantly scans its surroundings, quickly detecting and reacting to obstacles or sudden environmental changes. When the robot detects an object nearby or approaches an edge, it immediately reverses direction, simulating a cautious animal fleeing from danger. In the absence of threats, Frankie continuously exhibits playful, randomized behaviors—moving forward, turning, performing gentle curves, and executing unique “tricks” like a full 360-degree spin or a curious scanning motion—adding lifelike unpredictability and character to its interactions.
## Project Highlights
- **Responsive Obstacle Detection:** Frankie uses two ultrasonic sensors—one forward-facing for obstacle detection and one downward-facing for edge detection. These real time sensors detect any threats and send signals for the robot to act accordingly.
- **Randomized Behaviors:** Frankie exhibits lifelike randomness, alternating between forward movement, turning, gentle curves, and unique “trick” routines, such as a 360-degree spin and an idle scanning movement.
- **PWM Speed Control:** Motors are controlled via Pulse Width Modulation (PWM), enabling smooth transitions and precise speed variations, enhancing the robot's lifelike responsiveness.
- **Rapid Prototyping and Iteration:** Multiple prototypes were rapidly constructed to solve real-world engineering challenges, including torque insufficiencies and power management.
- **Integrated Mechatronic System:** Combines mechanical design (laser-cut chassis, gearbox motors), electronic components (IBT-2 drivers, Arduino, sensors), and custom software for full autonomous functionality.

## Key Technical Learnings
- Identified initial torque and RPM limitations, leading to the implementation of geared motors (1:48 gear ratio, 200 RPM).
- Upgraded from a MOSFET-based H-bridge to IBT-2 motor drivers to manage higher current loads.
- Developed filtering logic to manage sensor noise and invalid readings, improving robustness.
