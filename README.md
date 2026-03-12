# 3-DOF SCARA Manipulator — Design & Kinematic Simulation

> Developed during the **Def-Space Tech Internship and Technical Training Program**

---

## Overview

This project presents the **design, visualization, and kinematic simulation** of a 3-Degree-of-Freedom (3-DOF) SCARA robotic manipulator.

The objective was to understand and demonstrate the principles of:
- Robot manipulator design and coordinate alignment
- Forward and inverse kinematics
- Trajectory simulation and motion visualization

---

## Robot Configuration

The manipulator follows the **SCARA (Selective Compliance Assembly Robot Arm)** architecture with the following joints:

| Joint | Type | Description |
|-------|------|-------------|
| Joint 1 | Revolute | Base Rotation (θ₁) |
| Joint 2 | Revolute | Elbow Rotation (θ₂) |
| Joint 3 | Prismatic | Vertical Extension (d₃) |

**Common Applications:** Pick & Place Systems · Assembly Lines · Precision Manufacturing · Automated Production

---

## Project Workflow

### 1. Concept Modeling — TinkerCAD
Initial robotic arm structure was built to establish link geometry and joint configuration:
- Defined manipulator structure and base/link geometry
- Positioned joints and created a rough conceptual model

### 2. Mechanical Design & Animation — Blender
Model components were refined and animated:
- Assembled robotic arm components and aligned links/joints
- Defined joint rotations and created motion animations
- Verified correct joint behaviour visually

### 3. Kinematic Simulation — MATLAB
A full mathematical model was implemented covering:
- **Forward Kinematics** — Calculate end-effector position `(X, Y, Z)` from given joint angles
- **Inverse Kinematics** — Determine joint angles required to reach a target position
- **Trajectory Motion** — Simulate smooth motion between waypoints

---

## Robot Parameters

```
Link 1 Length    :  120 mm
Link 2 Length    :  100 mm
Platform Height  :  140 mm
Maximum Reach    :  220 mm
Vertical Range   :  0 – 100 mm
```

---

## MATLAB Interactive Simulation

The MATLAB interface provides real-time control and visualization:
- Joint angle sliders for manual control
- Real-time end-effector position readout
- Robot specification display panel
- Automatic pick-and-place demo mode

---

## Project Structure

```
3dof-scara-manipulator/
│
├── Report.pdf
├── scaramodel-animation.mp4       # Blender animation
├── Matlab simulation.mp4          # MATLAB simulation recording
└── scara_robot_interactive.mat    # MATLAB interactive model-code
```

---

## Demonstrations

| Demo | File | Description |
|------|------|-------------|
| Blender Animation | `scaramodel-animation.mp4` | Robotic arm motion in Blender |
| MATLAB Simulation | `Matlab simulation.mp4` | Joint motion & end-effector positioning |
| Interactive Model | `scara_robot_interactive.mat` | Manually adjustable/Automatic MATLAB model |

---

## Key Concepts Demonstrated

- [x] SCARA Robot Architecture
- [x] Robotic Manipulator Design
- [x] Forward Kinematics
- [x] Inverse Kinematics
- [x] Robot Motion Visualization
- [x] Trajectory Simulation

---

## Future Improvements

-  Build a physical hardware prototype
-  Integrate servo / stepper motors
-  Implement microcontroller control (Arduino / Raspberry Pi)
-  Add computer vision for object detection
-  Integrate ROS (Robot Operating System) for full control pipeline

---

## Project Files

The full simulation files and animations are available here:

Google Drive:
https://drive.google.com/drive/folders/1h2PrLcrqwxpdoaEGGJ73osZo6VT-y6d4?usp=sharing

## Author

Developed as part of the **Def-Space Tech Internship and Technical Training Program**.
