![The Ottawa Skybound Logo](https://hc-cdn.hel1.your-objectstorage.com/s/v3/1629d2e3f622f46302eb5b086aa902cd3c22def1_image.png)

# Apex Hardware

## Overview

This repository contains the hardware design files for Ottawa Skybound's weather ballon for [Apex](https://apex.hackclub.com). The repository contains of multiple PCB modules designed in KiCad. The system includes a motherboard, wireless communication module, and various sensor interfaces.

## Boards

LoRa Module: Wireless communication module using LoRa technology. Designed by Adam Turaj

Motherboard: Main control board for the Apex system. Designed by Adam Turaj

Sensor Board: A board containing an IMU and temperature reader. Designed by Joshua Gallinger

Strain ADC: Analog-to-digital converter board for strain measurements. Designed by Adam Turaj

Archive/RF Module: Previous design iteration of the LoRa board. Designed by Adam Turaj

Gas Sensor: Collects data on TVOC concentrations in the air. Designed by Aryan Zafer

Ground RF: Board used to communicate and receive data from the weather balloon. Designed by Aryan Zafer

## Development Requirements

KiCad 9.0 or newer

## License

This project is licensed under the GNU GENERAL PUBLIC LICENSE. The license can be found [here](https://github.com/Apex-Ottawa-Team/hardware/blob/main/LICENSE).
