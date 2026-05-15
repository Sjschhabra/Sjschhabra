<div align="center">
  <img src="header.svg" width="100%" alt="Sameerjeet S. Chhabra"/>
</div>

<br/>

<div align="center">

<a href="https://sjschhabra.github.io">
  <img src="https://img.shields.io/badge/🌐%20Portfolio-sjschhabra.github.io-0c1a2e?style=for-the-badge&labelColor=0c1a2e&color=38bdf8" height="32"/>
</a>
&nbsp;
<a href="https://www.linkedin.com/in/sjschhabra/">
  <img src="https://img.shields.io/badge/LinkedIn-Connect-0c1a2e?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=0c1a2e&color=0a66c2" height="32"/>
</a>
&nbsp;
<a href="mailto:sameerjeetsinghchhabra@gmail.com">
  <img src="https://img.shields.io/badge/Gmail-Email%20Me-0c1a2e?style=for-the-badge&logo=gmail&logoColor=white&labelColor=0c1a2e&color=ea4335" height="32"/>
</a>
&nbsp;
<a href="https://www.youtube.com/@elusiveastra">
  <img src="https://img.shields.io/badge/YouTube-Videos-0c1a2e?style=for-the-badge&logo=youtube&logoColor=white&labelColor=0c1a2e&color=ff0000" height="32"/>
</a>
&nbsp;
<a href="https://grabcad.com/sameerjeet.singh.chhabra-2">
  <img src="https://img.shields.io/badge/GrabCAD-3D%20Models-0c1a2e?style=for-the-badge&logo=autodesk&logoColor=white&labelColor=0c1a2e&color=0696d7" height="32"/>
</a>

<br/><br/>

![](https://komarev.com/ghpvc/?username=Sjschhabra&color=38bdf8&style=flat-square&label=profile+views)

</div>

---

## About Me

```python
class SameerjeetChhabra:
    degree    = "M.S. Robotics & Autonomous Systems — ASU  |  GPA: 3.78 / 4.0"
    location  = "Mesa, Arizona  →  Open to relocation"
    focus     = ["Legged Locomotion", "MPC", "Sim-to-Real Transfer", "Sensor Fusion"]
    stack     = ["MuJoCo", "ROS2", "MoveIt2", "PyTorch", "Open3D", "OpenCV", "MATLAB"]
    languages = ["Python", "C++"]
    hardware  = ["Jetson Nano", "Raspberry Pi", "Arduino", "LiDAR", "Stereo Cameras"]
    currently = "Building Project Eleven — 20 cm Bipedal/Quadruped with MPC"
    status    = "Graduating May 2026  ·  Seeking full-time robotics roles"
```

---

## Projects

<table>
<tr>
<td width="50%" valign="top">

**Project Eleven — Bipedal / Quadruped Robot**

`MuJoCo` `MPC` `URDF/MJCF` `SolidWorks` `C++`

Designed a 20 cm bipedal/quadruped from scratch with 3-DoF per leg (hip, knee, ankle). Exported SolidWorks CAD to URDF, compiled to MuJoCo MJCF with tuned actuators, joint limits, damping, and stiffness. Full sensor suite — IMU + contact sensors. Stable static balance achieved in sim. Currently implementing **Model Predictive Control** for dynamic locomotion with real-time joint torque optimization.

</td>
<td width="50%" valign="top">

**Grasshopper-Inspired Walking Robot — Sim-to-Real**

`MuJoCo` `System Identification` `SG90 Servos` `Cardboard`

Bio-inspired four-bar linkage walker fabricated from laminated cardboard — zero off-the-shelf structural parts. Ran system identification experiments to extract stiffness, damping, friction, and servo dynamics from hardware. Embedded all measured parameters into a MuJoCo physics model. Parameter sweeps + simulation-based gait optimization predicted real hardware performance within **5–22% sim-to-real error**.

</td>
</tr>
<tr>
<td width="50%" valign="top">

**Voice-Operated Mobile Manipulator**

`ROS2` `MoveIt2` `Nav2` `YOLOv8` `SLAM` `AMCL`

Integrated TurtleBot4 and myCobot 280 arm in a full autonomous stack. SLAM for mapping, AMCL for ±5 cm localization, Nav2 for navigation, MoveIt2 for arm motion planning, YOLOv8 for object detection at **92% accuracy**, and a speech-to-text voice command pipeline with **85% recognition accuracy** in live unscripted operation.

</td>
<td width="50%" valign="top">

**MuJoCo Robotic Arm — 3D Depth Reconstruction**

`Open3D` `Stereo Vision` `Point Clouds` `Forward Kinematics`

Built a 6-DoF arm in MuJoCo with a stereo end-effector depth camera (90° FoV) on a linear slider. Transformed depth images from **50+ camera poses** into world-frame point clouds using calibrated intrinsics, extrinsics, and forward kinematics. Fused **100k+ 3D points** and executed Poisson surface reconstruction under simulated range-dependent noise.

</td>
</tr>
<tr>
<td width="50%" valign="top">

**6-DoF Robotic Arm — Custom IK Solver & Vision**

`C++` `Newton-Raphson IK` `OpenCV` `A* Path Planning`

Derived and implemented a Newton-Raphson inverse kinematics solver from scratch achieving **±0.2 mm end-effector accuracy** across the full workspace. Integrated a real-time OpenCV vision pipeline with A* path planning. Solved a physical maze course with **95% success rate** over 20+ trials.

</td>
<td width="50%" valign="top">

**PLC-Controlled Semiconductor Automation System**

`Allen Bradley` `Ladder Logic` `HMI` `SCARA`

Automated wafer handling system using Allen Bradley PLC, SCARA robots, and laser processing with coordinated motion control. Designed full HMI interface, programmed ladder logic sequences, and validated end-to-end automation pipeline.

</td>
</tr>
<tr>
<td width="50%" valign="top">

**Smart Semiconductor Manufacturing — IIoT**

`MQTT` `Edge ML` `XGBoost` `SCADA` `AWS IoT`

Real-time wafer defect detection system using a 5-layer IIoT architecture with edge ML. Achieved **94.5% detection accuracy** and **< 50 ms latency** using XGBoost at the edge. Designed MQTT/OPC-UA data pipeline from sensor to cloud.

</td>
<td width="50%" valign="top">

**UAV Dynamic Landing — Vision Line Tracking**

`MATLAB/Simulink` `Control Systems` `Computer Vision`

Real-time vision-based line tracking controller for dynamic UAV landing designed in MATLAB Simulink. Validated stable closed-loop tracking behaviour in simulation. End-to-end controller from perception to actuation command.

</td>
</tr>
</table>

---

## Tech Stack

<div align="center">

![Python](https://img.shields.io/badge/Python-0369a1?style=flat-square&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-0284c7?style=flat-square&logo=cplusplus&logoColor=white)
![ROS2](https://img.shields.io/badge/ROS2-0ea5e9?style=flat-square&logo=ros&logoColor=white)
![MuJoCo](https://img.shields.io/badge/MuJoCo-0369a1?style=flat-square)
![PyTorch](https://img.shields.io/badge/PyTorch-0284c7?style=flat-square&logo=pytorch&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-0ea5e9?style=flat-square&logo=opencv&logoColor=white)
![MATLAB](https://img.shields.io/badge/MATLAB-0369a1?style=flat-square)
![MoveIt2](https://img.shields.io/badge/MoveIt2-0284c7?style=flat-square)
![Open3D](https://img.shields.io/badge/Open3D-0ea5e9?style=flat-square)
![Isaac Lab](https://img.shields.io/badge/Isaac_Lab-0369a1?style=flat-square&logo=nvidia&logoColor=white)
![Gazebo](https://img.shields.io/badge/Gazebo-0284c7?style=flat-square)
![TensorFlow](https://img.shields.io/badge/TensorFlow-0ea5e9?style=flat-square&logo=tensorflow&logoColor=white)
![Jetson Nano](https://img.shields.io/badge/Jetson_Nano-0369a1?style=flat-square&logo=nvidia&logoColor=white)
![Arduino](https://img.shields.io/badge/Arduino-0284c7?style=flat-square&logo=arduino&logoColor=white)
![Raspberry Pi](https://img.shields.io/badge/Raspberry_Pi-0ea5e9?style=flat-square&logo=raspberrypi&logoColor=white)
![SolidWorks](https://img.shields.io/badge/SolidWorks-0369a1?style=flat-square)
![Allen Bradley](https://img.shields.io/badge/Allen_Bradley_PLC-0284c7?style=flat-square)

</div>

---

## Achievements

<div align="center">

| | |
|:--|:--|
| 🥉 **Honeywell × ASU Hackathon 2026 — 3rd Place · $2,500** | Robotic tube insertion for heat exchangers using chamfered alignment, vibration self-alignment, and linear actuation. Validated with 3D-printed prototypes. |
| 🥈 **Los Alamos National Lab × ASU 2025 — 2nd Place · $5,000** | Designed automated mechanical unpacking and sequencing system for MinION Flow Cells under time constraints. |
| 📄 **Publication · IJRASET · February 2023** | Design and Inverse Kinematics Analysis of Cable-Suspended Parallel Robot FarmPet for Agricultural Application |
| 🔬 **GHOST Lab · Arizona State University** | Hands-on operation of Fetch, YuMi, Husky, UR5, and TurtleBot platforms for HRI research |

</div>

---

## GitHub Stats

<div align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=Sjschhabra&show_icons=true&hide_border=true&bg_color=0c1a2e&title_color=38bdf8&icon_color=7dd3fc&text_color=bae6fd&count_private=true"/>
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Sjschhabra&layout=compact&hide_border=true&bg_color=0c1a2e&title_color=38bdf8&text_color=bae6fd"/>
</div>



---

<div align="center">
<br/>

*Building intelligent systems that bridge the gap between simulation and reality.*

</div>
