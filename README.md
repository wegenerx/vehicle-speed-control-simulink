# Vehicle Speed Control (Simulink)

This repository contains Simulink models for a vehicle longitudinal speed
control system developed as a course project for *Automatic Control Theory*.

## Model Overview
- Plant: first-order mass–damping model  
  G(s) = 1 / (500s + 50)
- Control strategy: PI controller with unit negative feedback
- Control objective: vehicle speed tracking under step reference

## Files
- `vehicle_openloop.slx` — open-loop vehicle model (force input)
- `vehicle_closedloop.slx` — closed-loop speed control with PI controller

## Simulation Environment
- MATLAB / Simulink (tested on R2022b)

## Notes
- Models focus on control structure and dynamic behavior
- Nonlinear effects (actuator saturation, road slope, noise) are not considered
