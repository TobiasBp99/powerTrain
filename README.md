# powerTrain

## Overview 🛵

The powerTrain V1.0.0 is a prototype that can control at least one brushless motor with a power of 48V@20A. This is close to 1kW and more than 1HP. The hardware is independent of the type of control that is implemented on the motor (trapezoidal, sinusoidal, vector) and allows communication with other powerTrains for applications where it is necessary to control more than one motor simultaneously.

## Features 💡

- Wide voltage range up to 48V
- CAN BUS to communicate with other potential modules (BMS/INFOTAINMENT/POWER TRAIN)
- 3 (three) phase BLCD motor control
- Inputs for multiple sensors (TPS/PAS/BRAKE)
- Inputs/Outputs to manage a dashboard
Communication extensible to serial port
- Power stage with error detection (OVERCURRENT/OVERTEMPERATURE)

## 3D Model
![top](https://github.com/TobiasBp99/powerTrain/blob/master/images/topLayer.png)
![bottom](https://github.com/TobiasBp99/powerTrain/blob/master/images/bottomLayer.png)
![pcb](https://github.com/TobiasBp99/powerTrain/blob/master/images/pcb.png)
