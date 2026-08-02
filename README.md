# STM32 FreeRTOS Binary Semaphore LED Control

## Overview

This project demonstrates **Binary Semaphore** implementation using **FreeRTOS** on the **STM32F407 Discovery Board**. Two FreeRTOS tasks are synchronized using a **Binary Semaphore** to control an onboard LED. The semaphore ensures that only one task accesses the shared resource (LED) at a time, preventing resource conflicts and illustrating task synchronization in a Real-Time Operating System (RTOS).

## Hardware Required

- STM32F407 Discovery Board
- USB Cable

## Software Used

- STM32CubeIDE
- Embedded C
- STM32 HAL Library
- FreeRTOS

## Features

- FreeRTOS task creation
- Binary Semaphore synchronization
- LED control using GPIO
- Task synchronization without resource conflicts
- RTOS-based embedded application
- Beginner-friendly FreeRTOS example

## Project Structure

```text
Core/
├── Inc/
│   └── main.h
├── Src/
│   └── main.c
├── FREERTOS/
│   ├── App/
│   ├── Source/
│   └── CMSIS_RTOS/
```

## How to Run

1. Open the project in **STM32CubeIDE**.
2. Build the project.
3. Connect the **STM32F407 Discovery Board** via USB.
4. Flash the firmware to the board.
5. Run the application and observe the LED being controlled through synchronized FreeRTOS tasks using a Binary Semaphore.

## Technologies Used

- Embedded C
- STM32 HAL Library
- FreeRTOS
- STM32F407 Discovery Board
- GPIO Programming
- Binary Semaphore
- RTOS Task Synchronization

## Key Concepts

- FreeRTOS Scheduler
- Task Creation
- Binary Semaphore
- Resource Synchronization
- Mutual Exclusion
- Inter-Task Communication

## Applications

- Embedded Real-Time Systems
- Task Synchronization
- Shared Resource Management
- Industrial Automation
- IoT Devices
- Embedded Firmware Development
