# Banker's Algorithm

## Introduction

Resource allocation is a critical aspect of operating systems, involving the distribution of limited resources among competing processes. The Banker's Algorithm serves as a deadlock avoidance mechanism, preventing deadlock occurrences by carefully considering resource requests. This project explores the principles, assumptions, and execution steps of the Banker's Algorithm, providing practical insights into resource management challenges in operating systems.

## Problem Statement

The project aims to implement the Banker's Algorithm in a multithreaded program simulating a banking system. The program represents concurrent execution, preventing race conditions and avoiding deadlocks. It combines three key topics: multithreading, race condition prevention, and deadlock avoidance, offering a practical application of these concepts. The goal is to develop a program that effectively manages resource allocation and prevents deadlocks in a concurrent environment.

## Project Description

This project involves writing a multithreaded program implementing the Banker's Algorithm for resource allocation and deadlock avoidance. The simulation represents a banking system where customers request and release resources, with the banker ensuring requests leave the system in a safe state. The project combines multithreading, race condition prevention, and deadlock avoidance to create a robust resource management system.

## Key Features

- **Multithreading:** Representing concurrent execution of multiple customers and their resource requests.
- **Race Condition Prevention:** Synchronizing access to shared resources to ensure data consistency and avoid conflicts.
- **Deadlock Avoidance:** Utilizing the Banker's Algorithm logic to grant or deny resource requests based on system safety.

## Assumptions of Bankers Algorithm

1. **Fixed Number of Resources:** Assumes a constant number of resources throughout execution.
2. **Preemptive Resource Allocation:** Allows resources to be allocated preemptively.
3. **Deterministic Resource Requirements:** Assumes fixed and known resource requirements for each process.
4. **No Resource Sharing:** Resources cannot be shared between processes.
5. **Safety Assumption:** Assumes processes will eventually release held resources after execution.

## Algorithm Overview

The Banker's Algorithm allocates resources based on maximum requirements, current allocations, and available resources. It proactively prevents deadlocks by considering resource needs and availability. The algorithm optimizes resource utilization and ensures system stability.

## Getting Started

1. Download the project files.
2. Run the multithreaded program using the provided command:

```bash
python bankers_algorithm.py
```

By completing this project, practical experience is gained in working with multithreaded programs, preventing race conditions, and applying the Banker's algorithm for deadlock avoidance in real-world scenarios.

## Contributing

Contributions are welcome! Feel free to open issues, submit pull requests, or provide feedback to enhance the functionality and usability of the Prisoner Management System.

## Reporting Issues

If you encounter any errors or face problems related to this program, please feel free to contact me via jvlpranathi@gmail.com.
