# PROJECT MANTIS

### Wearable-Controlled Electromagnetic Interaction System

**Project MANTIS** is an experimental engineering project focused on developing a wearable-controlled electromagnetic system. The concept consists of a bracelet-style controller and a compact disk-shaped electromagnetic device.

The goal is to explore how wireless communication, embedded programming, and electromagnet technology can work together to create a system that allows a user to control magnetic interaction through a wearable interface.

MANTIS combines concepts from electronics, programming, physics, and mechanical design.

---

## Project Vision

The long-term vision of MANTIS is to develop a compact and intuitive system that allows a user to control an electromagnetic device using simple commands from a wearable controller.

The bracelet acts as the user interface, while the disk contains the electronics and electromagnetic components responsible for producing the magnetic field.

The initial prototype will focus on demonstrating controlled electromagnetic interaction under carefully measured laboratory conditions.

## System Architecture

MANTIS is divided into two main components:

### 1. Wearable Bracelet Controller

The bracelet is designed to serve as the main control interface.

Planned components include:

- ESP32 microcontroller
- Push buttons for operating modes
- OLED display for system status
- Bluetooth Low Energy communication
- Status LEDs
- Rechargeable battery and power management
- Custom bracelet enclosure

The bracelet will send commands wirelessly to the electromagnetic disk.

### 2. Electromagnetic Disk

The disk is designed to receive commands and control an electromagnet.

Planned components include:

- ESP32 microcontroller
- Electromagnetic coil
- Magnetic core
- MOSFET or suitable motor/coil driver
- Temperature sensor
- Current-monitoring circuit
- External power connection for the first prototype
- Protective enclosure

The disk will process incoming commands and control the electromagnetic system according to its programmed operating conditions.

## Operating Modes

The initial control system is designed around three operating modes:

| Mode | Purpose |
|---|---|
| Standby | Keeps the electromagnetic system inactive |
| Attraction | Activates the selected magnetic interaction |
| Repulsion | Reverses coil polarity where the magnetic configuration supports repulsion |

The actual interaction depends on the magnetic materials, field orientation, coil design, and distance between the magnetic components.

## Technologies and Engineering Areas

The project involves:

- **Embedded systems:** ESP32 microcontroller programming
- **Programming:** C++ and Arduino framework
- **Wireless communication:** Bluetooth Low Energy
- **Electronics:** Voltage, current, resistance, and power management
- **Power electronics:** MOSFET switching, H-bridge control, and PWM
- **Electromagnetism:** Magnetic fields, coil design, and polarity control
- **Sensors:** Temperature and current monitoring
- **3D design:** Mechanical enclosures and wearable components
- **Testing:** Measuring current, temperature, magnetic field strength, and force

## Development Roadmap

The project is being developed in stages:

1. **Controller development** — Build and test the bracelet's operating logic.
2. **Electronics development** — Develop the disk's control and power circuits.
3. **Wireless communication** — Establish communication between the bracelet and disk.
4. **Electromagnet development** — Design and test the coil and magnetic core.
5. **System integration** — Connect the controller, communication system, sensors, and electromagnetic driver.
6. **Prototype testing** — Measure performance and improve the design.
7. **Mechanical development** — Refine the bracelet and disk enclosures.

## Current Prototype Approach

The first prototype will use a wired external power supply for the electromagnetic disk. This makes it possible to test the electromagnetic system without introducing the additional complexity of a battery-powered disk.

The bracelet and disk will communicate wirelessly, while the disk receives its operating power through a separate cable.

The initial development will prioritize reliable control, measurable results, and safe laboratory testing before attempting a fully wearable version.

## Project Limitations

MANTIS is an experimental project, and its capabilities are still being investigated.

Electromagnetic force depends on factors such as coil current, magnetic core, field geometry, distance, and the properties of the target material. It cannot directly move arbitrary non-magnetic objects such as ordinary wood or plastic.

The first prototype is intended to demonstrate controlled magnetic interaction with suitable magnetic targets. Long-distance operation and interaction with arbitrary objects are not established capabilities.

## Project Status

**Status:** Prototype development

The project is currently focused on learning, designing, programming, selecting components, and preparing the first hardware prototype.

## Project Goals

The main goals are to:

- Develop a functional wearable control interface.
- Establish reliable wireless communication.
- Build a controllable electromagnetic device.
- Implement temperature and current monitoring.
- Measure magnetic performance experimentally.
- Develop a compact and practical physical design.

---

**Project MANTIS**  
*Exploring the intersection of wearable technology, embedded systems, and electromagnetism.*