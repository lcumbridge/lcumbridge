# Leonard Cumbridge

**Embedded systems engineer.** 20+ years building autonomous control systems for surface and airborne platforms — hard real-time firmware, sensor fusion, motor control, and the ground station software that ties it together.

Principal at [MicroRobo Systems LLC](https://microrobosys.com) · Palm Bay, Florida

---

## Featured Work — GPS Beacon Tracking Gimbal System

An 8-month part-time project: a ground-based system that automatically points a 20× zoom camera at an airborne GPS beacon. Built predominantly from COTS components. Three interconnected repos, four technical white papers.

| Repo | What it does |
|---|---|
| [**mrs-beacon-tracker**](https://github.com/lcumbridge/mrs-beacon-tracker) | System overview and component index — start here |
| [**mrs-airborne-tracker**](https://github.com/lcumbridge/mrs-airborne-tracker) | Teensy 4.0 · 9-state NED EKF · ICM-20948 DMP · NEO-M9N GPS · 34-byte binary telemetry · 3-axis gyro stabilizer |
| [**mrs-gimbal-controller**](https://github.com/lcumbridge/mrs-gimbal-controller) | Teensy 4.1 · SimpleFOC v2.4.0 · dual-axis FOC at 2 kHz · AS5048A encoders · notch filters · fault state machine |
| [**mrs-ground-station**](https://github.com/lcumbridge/mrs-ground-station) | Python 3.11 · 6-DOF EKF · critically-damped setpoint filter · VISCA RS-485 zoom · MRSLOG03 binary logging |

**Measured performance:** 0.46° RMS elevation · 0.47° RMS azimuth · steady-state, camera loaded, 12 V

**→ Technical white papers:** [microrobosys.com/papers.html](https://microrobosys.com/papers.html)

---

## Specializations

```
Hard real-time embedded firmware    C / C++ / Arduino framework / Teensyduino
Sensor fusion & state estimation    EKF · IMU · GPS · magnetometer · barometer
Brushless motor control             SimpleFOC · FOC · AS5048A · GBM-series motors
Ground station software             Python · PyQt5 · OpenGL · multi-threaded IPC
RF telemetry                        XBee 802.15.4 · UBX binary · custom framing + CRC
Autonomous flight control           PID · rate/heading-hold · S.Bus · servo output
```

---

## Background

- Defense and intelligence programs — Tomahawk Robotics Mimic Controller (9-DOF handheld drone controller, field-tested by intelligence services)
- DARPA challenge program preparation
- Formally verified RTOS implementation
- Train control system engineering (Los Angeles Metro Green Line)
- Custom PCB design — LGA and QFN packages, multi-layer mixed-signal boards

---

## Licensing

Published repos are released under [PolyForm Noncommercial 1.0.0](https://polyformproject.org/licenses/noncommercial/1.0.0) — free for noncommercial use with attribution. Commercial licensing available via [microrobosys.com](https://microrobosys.com).

---

*Available for contract, consulting, and project-based engagements.*
