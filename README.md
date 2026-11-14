# STM32 Temperature Fan Control

This project implements a fan-based temperature control system for the STM32F411E-DISCO board. It uses C++ together with the STM32 HAL.

The system uses an LM35 temperature sensor and a potentiometer to set the desired temperature. It controls the fan using PWM and measures fan speed using the tachometer (Tach) signal.

## Project structure

- `firmware/Core/` contains the application, peripheral interfaces, and startup code.
- `firmware/Drivers/` contains the STM32 HAL and CMSIS files.
- `firmware/Mini_Projet_CPP_STM32411.ioc` contains the STM32CubeMX configuration.
- The `.project`, `.cproject`, `.mxproject`, and `.settings/` files in `firmware/` contain the STM32CubeIDE project configuration.
- The `.ld` files in `firmware/` are linker scripts for Flash and RAM configurations.
- `stm32-temperature-fan-control.pdf` is the project document.

## Opening the project

In STM32CubeIDE, import the `firmware/` folder as an existing project. The project retains its original STM32CubeIDE name, `Mini_Projet_CPP_STM32411`.
