# PID Self-Leveling Platform

A single-axis platform designed to stay horizontal at a 0° setpoint
when its base tilts. Developed as a group project for IE3034 Control
Systems Engineering at the Sri Lanka Institute of Information Technology.

## How it works

1. An MPU6050 measures acceleration and angular velocity.
2. A complementary filter combines the sensor readings to estimate tilt.
3. A PID controller compares the estimated tilt with the 0° setpoint.
4. An SG90 servo moves the platform to reduce the error.

## Modeling and testing

The project covers transfer-function and state-space modeling, MATLAB
simulation comparing P, PI, and PID control, and hardware tests for
reference tracking and disturbance rejection. The report discusses how
servo limits, friction, backlash, and sensor noise affect the prototype.

## Project files

Add the original firmware, MATLAB simulation files, and wiring schematic
when available.
