# EV-Traction-Control
Model based traction control system for an electric vehicle, built in MATLAB/Simulink
# EV Traction Control System — MATLAB/Simulink

## Project Overview
A model-based traction control system for a rear-wheel drive 
electric vehicle, developed in MATLAB/Simulink. The system 
controls wheel slip ratio to maintain optimal tyre grip across 
varying road surfaces.

## Motivation
Developed as part of a personal portfolio targeting control 
systems engineering roles in motorsport. Complements an MEng 
in Electric Motorsport at Oxford Brookes University.

## System Architecture
- **Plant model:** EV drivetrain + simplified Pacejka tyre model
- **Controller:** PID slip ratio controller
- **Fault detection:** Wheel speed sensor fault injection + fallback logic
- **Surfaces modelled:** Dry (μ=0.9), Wet (μ=0.5), Ice (μ=0.2)

## Tools
- MATLAB/Simulink R2026a
- Control System Toolbox

## Project Status
🔄 In progress — Week 2 of 6

## Weekly Progress
- [x] Week 1 — Environment setup, theory foundations
- [ ] Week 2 — Plant modelling (drivetrain + tyre)
- [ ] Week 3 — PID controller design and tuning
- [ ] Week 4 — Fault injection and detection
- [ ] Week 5 — Calibration report
- [ ] Week 6 — Portfolio polish and applications
