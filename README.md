# EME5213 Term Project — Vehicle Suspension Modelling

**Course:** EME5213 Mechanical Vibrations (Dr. Giscard Kfoury)  
**Term:** Fall 2026

## Overview
Progressive modeling of a 2008 Honda Accord V6 3.5L EX-L suspension system through three model fidelity levels:
- **Phase 1:** 1-DOF quarter-car (sprung mass only) — free & forced vibration, transmissibility
- **Phase 2:** 2-DOF quarter-car with tire dynamics — unsprung mass, wheel-hop mode
- **Phase 3:** 4-DOF half-car with roll — bounce, roll, front/rear wheel-hop modes

Each phase is analyzed for **two tuning targets**: aggressive sports and comfort luxury configurations, using the same vehicle platform and road excitations.

## Vehicle
2008 Honda Accord V6 EX-L (8th gen, 225/50R17) with aftermarket struts of unknown specification — modeled as a measured baseline + two design alternatives.

## Repository Structure
'''├── Phase1_1DOF/ 
├── Phase2_2DOF/ 
├── Phase3_4DOF/ 
├── Parameters/ 
├── RoadProfiles/ 
├── Analysis/ 
└── Report/ 
'''
## Key Deliverables
- Parameterized Simulink models for all three phases (`.slx`)
- MATLAB scripts for computational analysis and performance charts
- Road profile generators
- Project Report with derivations, FBDs, parameter tables, and validation plots
- Measurement logs
