# STM32L053C8 CMSIS Template

This repository contains a minimalistic template project for working with the STM32L053C8 microcontroller using only CMSIS(Cortex Microcontroller Software Interface Standard).

## Features

- Basic project structure
- CMSIS core and device-specific header files
- Minimalistic `main.c` file to get started quickly
- Linker script and startup code

## Getting Started

1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/STM32L053C8-CMSIS-Template.git

2. Open the project in STM32CubeIDE:
  - Launch STM32CubeIDE;
  - Go to File -> Open Projects from File System;
  - Click Directory... and select the cloned repository folder;

3. Set up dependencies in project settings for GNU compiler:
  - Right-click on the project in the Project Explorer and select Properties;
  - Go to C/C++ Build -> Settings;
  - Under Tool Settings, configure the MCU GCC Compiler and MCU GCC Linker if necessary;

4. Rebuild the project with the new settings:
  - Right-click on the project and select Build Project;

5. Enjoy!
