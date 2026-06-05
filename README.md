# Mini Task Manager

## Overview

Mini Task Manager is a Windows-based process management application developed in C++. The project simulates the core functionalities of an operating system's Task Manager by providing real-time monitoring and control of system processes.

The application allows users to view active processes, terminate unwanted tasks, suspend and resume process execution, monitor resource usage, and safely exit the application. It is designed to provide practical experience with Windows Process Management APIs and real-time system operations.

---

## Features

### 1. List Running Processes

* Displays all active processes currently running on the system.
* Shows Process ID (PID) and executable name.
* Updates process information in real time.

### 2. Kill Process

* Terminates a selected process using its PID.
* Useful for handling unresponsive or resource-intensive applications.
* Frees system resources immediately after termination.

### 3. Suspend Process

* Temporarily pauses a running process.
* Preserves the process state without terminating it.
* Implemented through Windows thread suspension APIs.

### 4. Resume Process

* Restarts execution of a suspended process.
* Allows continuation from the exact point where execution was paused.

### 5. Process Resource Monitoring

* Retrieves process memory consumption.
* Calculates cumulative CPU execution time.
* Provides insight into system resource utilization.

### 6. Safe Exit

* Ensures proper application shutdown.
* Prevents unstable process states before termination.

---

## Technologies Used

* C++
* Windows API
* Tool Help Library
* Process Management Functions
* Thread Management APIs
* Console-Based User Interface

---

## Windows APIs Utilized

* CreateToolhelp32Snapshot()
* Process32First()
* Process32Next()
* OpenProcess()
* TerminateProcess()
* OpenThread()
* SuspendThread()
* ResumeThread()
* GetProcessMemoryInfo()
* GetProcessTimes()

---

## Project Objectives

* Understand real-time process management concepts.
* Explore Windows operating system internals.
* Implement process control using system-level APIs.
* Develop practical experience with thread and resource management.
* Simulate a simplified version of the Windows Task Manager.

---

## Learning Outcomes

Through this project, the following concepts were explored:

* Process Creation and Management
* Process Enumeration
* Thread Manipulation
* Resource Monitoring
* Real-Time System Operations
* Windows System Programming
* API Integration in C++

---

## How to Run

### Prerequisites

* Windows Operating System
* Dev-C++ / Visual Studio
* C++ Compiler with Windows API support

### Steps

1. Open the project in Dev-C++ or Visual Studio.

2. Compile and run the source code.

3. Use the menu options to:

   * View running processes
   * Kill processes
   * Suspend processes
   * Resume processes
   * Monitor resource usage
   * Exit the application

---

## Future Improvements

* Graphical User Interface (GUI)
* Process priority management
* Multi-threaded monitoring dashboard
* CPU and RAM usage graphs
* Search and filter processes
* Process history logging

---
