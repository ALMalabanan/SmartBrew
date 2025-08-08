# SmartBrew ☕
> Your Personal Barista in a Machine

![SmartBrew Logo](https://via.placeholder.com/400x150/2E8B57/FFFFFF?text=SmartBrew+Coffee+Automation)

## 📖 Description

SmartBrew is an innovative coffee shop automation system that transforms the traditional coffee-making process through intelligent PLC-controlled machinery. This project demonstrates a fully automated coffee brewing station that can prepare customized beverages with precise ingredient ratios, making it perfect for educational institutions, research facilities, and anyone interested in industrial automation and robotics.

**Who is it for?**
- Engineering students learning PLC programming
- Automation enthusiasts and makers
- Coffee shop owners looking for automation solutions
- Researchers in industrial robotics and control systems

**Why is it useful?**
- Demonstrates real-world application of PLC programming
- Showcases integration of pneumatic systems with automated control
- Provides consistent, precise beverage preparation
- Serves as an excellent educational tool for automation concepts

## 📋 Table of Contents

- [Features](#-features)
- [Tech Stack](#-tech-stack--built-with)
- [Installation](#-installation)
- [Usage](#-usage)
- [Project Structure](#-project-structure)
- [Known Issues](#-known-issues--limitations)
- [Future Improvements](#-future-improvements)
- [Credits](#-credits--acknowledgements)
- [License](#-license)
- [Contact](#-contact-info)

## ✨ Features

- **Automated Coffee Brewing**: Complete automation from ingredient selection to final beverage preparation
- **Precise Ingredient Ratios**: Custom-formulated ingredients ensure perfect 1:1 ratios for consistent taste
- **Cartesian Manipulator Integration**: Advanced robotic arm movement for precise ingredient handling
- **Dual Station Operation**: Two brewing stations (P1-P4 and P6-P8) for increased efficiency
- **Intelligent End Effector**: Tomato harvesting-inspired gripper ensures consistent ingredient quantities
- **Ultrasonic Sensor Array**: Cost-effective object detection system for cup positioning
- **Automatic Refilling System**: Chicken feeder-inspired mechanism maintains ingredient levels
- **Conveyor Belt Integration**: Expands operational positions beyond hardware limitations
- **Spherical Ingredient Design**: Prevents clogging and ensures smooth ingredient transfer
- **Hot Water Dispensing**: Integrated heating system (simulated via buzzer in demo)

## 🛠 Tech Stack / Built With

### Hardware
- **PLC Controller**: CL-150 PLC
- **Manipulation System**: Electro-Pneumatic Training Equipment / Cartesian Manipulator
- **Sensors**: Ultrasonic Sensor Array
- **Actuators**: Pneumatic cylinders and solenoids
- **End Effector**: Custom gripper mechanism
- **Conveyor System**: Belt-driven ingredient transport

### Software & Tools
- **Programming Environment**: WinSPS
- **PLC Programming**: Instruction List (IL) programming
- **Design Software**: 
  - Pics Art (system illustrations)
  - Canva (documentation and diagrams)
  - Microsoft Word (documentation)
- **Development**: PC-based programming environment
- **Initial Development**: MacroPLC (preliminary development)

## 🚀 Installation

### Prerequisites
```bash
# Required Hardware
- CL-150 PLC
- Electro-Pneumatic Training Equipment
- PC with serial/USB connectivity
- Ultrasonic sensors
- Pneumatic components
```

### Software Setup
```bash
# 1. Install WinSPS software
# Download WinSPS from manufacturer's website
# Follow installation wizard

# 2. Connect PLC to PC
# Use appropriate communication cable (Serial/USB)
# Verify connection in WinSPS software

# 3. Load SmartBrew program
# Open SmartBrew project file in WinSPS
# Compile and verify program using WinSPS debugging tools
# Transfer to CL-150 PLC
```

### Hardware Configuration
```bash
# 1. Set up Cartesian Manipulator
# Mount manipulator in designated workspace
# Connect pneumatic lines according to documentation
# Calibrate movement limits

# 2. Install Sensor Array
# Position ultrasonic sensors for cup detection
# Connect sensor outputs to PLC inputs
# Test sensor response

# 3. Configure Ingredient Stations
# Set up ingredient containers at positions P1-P8
# Install refilling mechanisms
# Test conveyor belt operation
```

## 💡 Usage

### Starting the System
```bash
# 1. Power on all pneumatic equipment
# 2. Initialize PLC program
# 3. Verify all sensors are responding
# 4. Check ingredient levels in all stations
```

