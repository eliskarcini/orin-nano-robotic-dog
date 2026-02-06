# System Block Diagram (v0)

## High-Level Overview
- Jetson Orin Nano: autonomy, perception, behavior
- OpenCat MCU: gait control, servo timing, reflexes
- Sensors: LiDAR, camera, IMU
- Power: battery, BMS, power gating

## Data Flow
- Orin → MCU: high-level motion commands
- MCU → Orin: joint states, battery, status
- Sensors → Orin: perception inputs

> Diagram coming next.
