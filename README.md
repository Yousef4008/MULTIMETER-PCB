# Auto-Ranging Multimeter PCB

This repository contains the design files and firmware for an auto-ranging multimeter project. The multimeter is designed to measure various electrical parameters with precision and reliability. Below are the key features and details of the project.

## Features

- **Power Supply**: 
  - Powered by a 3.7V Li-ion battery.
  - Integrated charging and protection circuit.
  - Boost converter to step up the voltage to 5V for stable microcontroller operation.
  
- **Reprogramming**:
  - Includes a USBasp port for easy firmware updates and reprogramming.

- **Measurement Capabilities**:
  - Accurately measures voltage, current, capacitance, inductance, and resistance.

- **Design Software**:
  - The PCB layout was created using Altium Designer.

## Getting Started

### Prerequisites

- **Altium Designer**: To open and modify the PCB design files.
- **AVR Programmer**: Such as USBasp for flashing the firmware onto the microcontroller.

### Usage

1. **PCB Assembly**: 
   - Assemble the PCB based on the design files provided.
   
2. **Firmware Installation**:
   - Use an AVR programmer to upload the firmware.

3. **Operation**:
   - Power the multimeter via the 3.7V Li-ion battery.
   - Use the micro USB port for charging.
   - Program the microcontroller using the USBasp port.


## Contributing

Contributions are welcome! Please fork this repository, make your changes, and submit a pull request.

## Contact

For any questions or suggestions, feel free to reach out via GitHub issues or directly on LinkedIn: https://www.linkedin.com/in/youssif-hossam-a81189240
