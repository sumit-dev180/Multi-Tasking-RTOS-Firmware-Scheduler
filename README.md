# Multi-Tasking RTOS Firmware Scheduler

A FreeRTOS-based multitasking firmware architecture that manages sensor acquisition, local display updates, and emergency alarm handling through independent tasks.

## Project Overview

The Multi-Tasking RTOS Firmware Scheduler is an embedded systems project focused on implementing a multitasking firmware architecture using FreeRTOS.

The system separates sensor acquisition, display updates, and emergency alarm handling into independent tasks. These tasks execute concurrently and coordinate their operation using RTOS synchronization mechanisms.

## Objectives

- Develop firmware using a microcontroller platform that supports FreeRTOS.
- Configure and initialize the FreeRTOS environment.
- Create independent tasks for sensor acquisition, display updates, and emergency alarm handling.
- Assign suitable task priorities.
- Implement inter-task communication using RTOS mechanisms.
- Ensure prompt emergency alarm response.
- Prevent race conditions when accessing shared resources.

## Key Features

- FreeRTOS-based multitasking architecture.
- Independent task execution.
- Periodic sensor acquisition.
- Real-time display updates.
- Emergency alarm handling.
- Task priority management.
- Inter-task communication and synchronization.
- Shared resource protection.

## Independent Tasks

### 1. Sensor Acquisition Task
Reads sensor measurements at defined intervals.

### 2. Display Update Task
Displays real-time sensor readings on a local display.

### 3. Emergency Alarm Task
Monitors critical conditions and activates an alarm when predefined thresholds are exceeded.

## RTOS Concepts Used

- FreeRTOS
- Task Creation
- Task Scheduling
- Task Priorities
- Queues
- Semaphores
- Task Notifications
- Periodic Task Execution
- Race Condition Prevention

## Working Principle

1. Initialize the microcontroller hardware and FreeRTOS environment.
2. Create independent tasks for sensor acquisition, display updates, and emergency alarm handling.
3. Configure suitable priorities for each task.
4. Use RTOS synchronization mechanisms for communication between tasks.
5. Start the FreeRTOS scheduler.
6. Execute sensor acquisition and display updates periodically.
7. Monitor critical sensor conditions and activate the emergency alarm when required.

## Project Files

| File | Description |
|---|---|
| Multi-Tasking RTOS Firmware Scheduler (sketch).txt | Project source / sketch file |
| Multi-Tasking RTOS Firmware Scheduler diagram.json.txt | System diagram file |
| working image.png | Project working image / evidence |

## Applications

- Industrial automation
- Real-time embedded systems
- Sensor monitoring systems
- Safety and alarm systems
- Multitasking firmware applications

## Project Status

FreeRTOS-based multitasking firmware project with source code, system diagram, and working image.

---

**Author:** Sumit
