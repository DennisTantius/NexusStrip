# NexusStrip

<p align="center">
  <img src="images/NexusStripLogo.png" alt="image" width="80%" />
  <br />
  <img src="https://img.shields.io/static/v1?label=MCU&amp;message=ESP32-S3&amp;color=222222&amp;style=flat-square" alt="MCU: ESP32-S3" />
  <img src="https://img.shields.io/static/v1?label=OS&amp;message=ESP-IDF%20%2F%20FreeRTOS&amp;color=CC2927&amp;style=flat-square" alt="OS: ESP-IDF / FreeRTOS" />
  <img src="https://img.shields.io/static/v1?label=Language&amp;message=C%20%2F%20C%2B%2B&amp;color=00599C&amp;style=flat-square" alt="Language: C/C++" />
  <img src="https://img.shields.io/static/v1?label=CAD&amp;message=KiCad&amp;color=314CB6&amp;style=flat-square" alt="CAD: KiCad" />
  <br />
  <img src="https://img.shields.io/static/v1?label=Hardware&amp;message=PCB%20Design&amp;color=2E8B57&amp;style=flat-square" alt="Hardware: PCB Design" />
  <img src="https://img.shields.io/static/v1?label=Control&amp;message=GPIO%20%2F%20Relay&amp;color=8A2BE2&amp;style=flat-square" alt="Control: GPIO / Relay" />
  <img src="https://img.shields.io/static/v1?label=Domain&amp;message=Power%20Management&amp;color=C1292E&amp;style=flat-square" alt="Domain: Power Management" />
  <img src="https://img.shields.io/static/v1?label=Version&amp;message=v0.0.9&amp;color=E9DF00&amp;style=flat-square" alt="Version: v0.0.9" />
  <img src="https://img.shields.io/static/v1?label=Status&amp;message=Prototype&amp;color=orange&amp;style=flat-square" alt="Status: Prototype" />
</p>

<h3 align="center">
  A modular desktop power management unit with manual switching and optional ESP32-S3 based MCU control.
</h3>

## Overview

Nexus Strip is a modular desktop power management unit designed to operate either as a conventional power strip or as an MCU-controlled switching system.

The project combines embedded firmware, relay control, PCB design and a modular control concept. The long-term goal is to support socket-level switching, power measurement, local display output, wireless communication and a local web or terminal-based user interface.

<p align="center">
    <img src="images/NexusStripOverview.png" alt="image" width="80%" />
</p>

## Roadmap

<p align="center">
    <img src="images/NexusStripRoadmap.png" alt="image" width="80%" />
</p>

## Project Status

Current version: **v0.0.9**

| Area | Status |
|---|---|
| Concept | In progress |
| Logo / visual identity | :white_check_mark: Done |
| Hardware architecture | In progress |
| Firmware architecture | Planned |
| KiCad PCB design | Planned / in progress |
| Relay control prototype | Planned |
| Display integration | Planned |
| Wireless communication | Planned |
| Power measurement | Planned |
| Webserver / TUI | Planned |

This repository documents the development process from concept to prototype. The current focus is system architecture, hardware partitioning and documentation.

## System Architecture

<p align="center">
    <img src="images/NexusStripSystemArchitecture.png" alt="image" width="80%" />
</p>
