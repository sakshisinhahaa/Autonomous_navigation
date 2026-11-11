# Autonomous Warehouse Surveillance

A ROS-based autonomous warehouse surveillance robot designed for autonomous navigation, environment mapping, obstacle avoidance, remote monitoring, and real-time data logging.

The project consists of both the complete software stack (ROS workspaces) and the hardware design files (mechanical CAD, electrical schematics, BOM, and demonstration videos).

---

# Features

- Autonomous Navigation
- SLAM Mapping
- Obstacle Avoidance & Recovery
- Remote Monitoring
- Real-Time Data Logging
- Custom Mechanical Design
- Custom Electronics Integration
- ESP32-based Motor Control
- Hardware Safety Circuit (Emergency Stop)

---

# Repository Structure

```
.
├── onboard/
│   └── ros_workspace/
│
├── offboard/
│   └── ros_workspace/
│
├── hardware/
│   ├── CAD Models
│   ├── Assemblies
│   ├── Drawings
│   ├── Lifting Mechanism
│   └── Mechanical Components
│
├── Electrical Schematics/
│
├── Demo/
│
├── Videos/
│
├── BOM_Itemized.csv
```

---

# Software

The software is divided into two ROS workspaces.

## Onboard Workspace

Location:

```
onboard/ros_workspace
```

Contains

- Robot Control
- Sensor Drivers
- Navigation
- SLAM
- Motor Interface
- Hardware Communication

---

## Offboard Workspace

Location:

```
offboard/ros_workspace
```

Contains

- Monitoring Interface
- Remote Control
- Data Logging
- Visualization
- Operator Side ROS Packages

---

# Hardware

The `hardware/` directory contains all mechanical design resources used during the project.

Contents include

- SolidWorks Parts (.SLDPRT)
- SolidWorks Assemblies (.SLDASM)
- Mechanical Drawings
- Camera Mount
- Lifting Mechanism
- Structural Components
- CAD Assemblies

Folder:

```
hardware/
```

---

# Electrical Schematics

Electrical design documents are available in

```
Electrical Schematics/
```

This includes

- High-Level Block Diagram
- ESP32 Pinout
- Motor Driver Connections
- Emergency Stop Circuit
- Motor Control Circuit
- Communication Interfaces

---

# Bill of Materials (BOM)

The complete itemized Bill of Materials is available here

```
BOM_Itemized.csv
```

The BOM includes

- Mechanical Components
- Electronics
- Fasteners
- Sensors
- Motors
- Bearings
- Structural Parts


# Demonstration

## Demo

Contains screenshots and demonstration media.

```
Demo/
```

## Videos

Contains project demonstration videos including

- SLAM Mapping
- Navigation
- Obstacle Avoidance
- Vertical Mechanism
- Scanning Mechanism
- Real-Time Data Logging

```
Videos/
```

---

