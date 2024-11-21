# Simple Operating System Simulation

This repository contains a simulation project for CO2017 (Operating Systems) - HCMUT, aimed at implementing and understanding core components of a simple operating system. The simulation focuses on three major aspects of an OS: scheduling, synchronization, and memory management.

---

## Features

### Core Components
1. **Scheduler and Dispatcher**:
   - Implements a multi-level queue (MLQ) scheduling algorithm.
   - Manages process scheduling and CPU assignment.

2. **Synchronization**:
   - Ensures safe access to shared resources in a multi-processor environment.
   - Implements lock mechanisms for resource protection.

3. **Memory Management**:
   - Simulates virtual-to-physical memory translation using paging.
   - Includes memory allocation, deallocation, and swapping mechanisms.
   - Supports multi-segment virtual memory with isolated address spaces for processes.

---

## Goals and Learning Objectives
This simulation helps to:
- Understand the principles of scheduling, memory management, and synchronization.
- Analyze and visualize OS behaviors like Gantt charts for process scheduling and RAM usage status.
- Explore how virtual and physical memory interact in a paging-based system.

---

## File Structure
- **Header Files**:
  - `timer.h`, `cpu.h`, `sched.h`, `mem.h`, etc.: Define key structures and functions for the OS components.
- **Source Files**:
  - `cpu.c`, `sched.c`, `mem.c`: Implement scheduler, memory management, and virtual CPU functionalities.
  - `paging.c`, `loader.c`: Handle memory paging and process loading.
- **Makefile**: Automates the build process.
- **Input Files**:
  - Configure the simulation environment, including process details, priorities, and memory configurations.
- **Output Files**:
  - Sample outputs for validation and comparison.

---

## How to Run
1. **Compile the Source Code**:
   ```bash
   make all
   ```

2. **Run the Simulation**:
   ```bash
   ./os [configure_file]
   ```
   Replace `[configure_file]` with the path to a configuration file in the `input` directory.

3. **Analyze Outputs**:
   - Outputs are generated in the `output` directory. Compare your results with provided samples.

---

## Requirements
- **Language**: C
- **Development Tools**: GCC, Make
- **Platform**: Linux-based environment recommended.

---

## Contribution
Quang Minh Tien Nguyen @justarandomnameduh
Hoang An Nguyen @hoangan-03
