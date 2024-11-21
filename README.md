# BLDC_Motor
Simulink Project for Controlling a BLDC Motor with a PMSM and PID Controller

# BLDC Motor Control 

## Project Description
This Simulink project models the control of a BLDC motor using a Permanent Magnet Synchronous Machine (PMSM) with a PID controller. The model includes:
- A PID controller to maintain a constant speed in RPM.
- A controlled voltage source providing the necessary voltage to a Universal Bridge, which acts as a three-phase inverter.
- A PMSM that receives the three-phase AC voltage from the Universal Bridge.
- Real-time feedback of rotor speed, which is fed back to the PID controller for adjustment.
- Processing of rotor position using Hall effect sensors. The signals are multiplexed, coded, and decoded to generate gating signals for the Universal Bridge.

The project displays the following on scopes:
- Final rotor speed in RPM.
- Rotor speed in radians per second.
- Three Hall effect signals.

## Features
- Maintains a constant motor speed using PID control.
- Provides real-time feedback and adjustment of rotor speed.
- Processes Hall effect signals to generate gating signals for the Universal Bridge.
- Monitors and displays rotor speed and Hall effect signals in real-time.

## Files Included
- `BLDC_Motor.slx`: The Simulink model file.
- `README.md`: Project description and details.
- Optional: Additional documentation in the `docs` folder.

## How to Use
1. Clone this repository to your local machine.
2. Open `BLDC_Motor.slx` in MATLAB Simulink.
3. Run the simulation and observe the output on the scopes.

## Author
- Jayesh Verma
- [LinkedIn](https://www.linkedin.com/in/jayeshv45/)
