# Fall Detection System for Older Adults — STM32

Academic embedded-systems project (2024–2025) using an STM32L4 Discovery board and an MPU6500 inertial sensor, with a SIM808 GSM/GPS module and buzzer for alerting. The report describes a threshold-based detection sequence using acceleration/free-fall, impact and inactivity criteria, followed by an SMS alert with location information.

## Contents

* Project documentation and figures from the original report.
* STM32 fall detection system based on motion sensing and threshold-based detection.
* MPU6500 inertial sensor and SIM808 GSM/GPS module.
* Embedded C/C++ project with no Python package requirements.


## Build status / limitations

The report appendix is not a complete standalone source project. It references files and symbols such as `main.h`, `mpu6500.h`, STM32 HAL handles, and SIM808 libraries that are not all included in the PDF. Therefore the extracted code is **not guaranteed to compile**. Add the original STM32CubeIDE project, generated HAL files, header files and configuration before claiming a reproducible build.

The report mentions both STM32L4 Discovery and Arduino Mega 2560 in different parts. Their exact roles in the final prototype should be clarified in the README before publication.

## Suggested software environment

- STM32CubeIDE / STM32CubeMX
- STM32 HAL drivers generated for the target board
- MPU6500 driver and SIM808/GSM-GPS integration code from the original project

Do not publish SIM PINs, phone numbers, API credentials or other private configuration values.
