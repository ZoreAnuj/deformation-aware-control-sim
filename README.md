# Deformation-aware Control Simulation for Robotic Subretinal Injection

This project simulates a real-time, deformation-aware control system for autonomous robotic subretinal injection, guided by intraoperative OCT. It explores the integration of vision-based feedback and motion compensation to enhance precision in delicate surgical procedures.

## Key Features
*   Simulates a control loop that accounts for tissue deformation in real time.
*   Integrates simulated intraoperative OCT (iOCT) guidance for visual feedback.
*   Implements motion compensation strategies for enhanced instrument stability.
*   Provides a modular framework for testing control algorithms in a virtual surgical environment.

## Tech Stack
*   Python
*   ROS (Robot Operating System)
*   Gazebo / PyBullet (for simulation)
*   OpenCV

## Getting Started
1.  Clone the repository: `git clone https://github.com/zoreanuj/deformation-aware-control-sim.git`
2.  Install dependencies: `pip install -r requirements.txt`
3.  Launch the simulation: `roslaunch launch/simulator.launch`