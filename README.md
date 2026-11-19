# Smart Traffic Management System

## Overview
The Smart Traffic Management System is a Java-based traffic simulation project that demonstrates how vehicles move through a road network while following traffic signals and traffic management rules.

The project includes a graphical user interface (GUI) that visualizes traffic movement in a digital twin-style environment.

## Features

- **Traffic Simulation:** Simulates vehicle movement on a 10 × 10 grid.
- **Traffic Signals:** Supports RED, YELLOW, and GREEN signal states.
- **Stop Sign Management:** Vehicles stop briefly at stop signs.
- **Collision Prevention:** Prevents vehicles from occupying the same position.
- **Queue Management:** Vehicles wait when another vehicle blocks their path.
- **Traffic Density Detection:** Automatically identifies LOW, NORMAL, and HIGH traffic density.
- **Vehicle Management:** Add and remove vehicles during simulation.
- **Simulation Controls:** Start, pause, and reset the simulation.
- **Graphical Visualization:** Displays roads, vehicles, traffic signals, and traffic statistics.

## Technologies Used

- Java
- Java Swing
- AWT
- Object-Oriented Programming
- IntelliJ IDEA
- Git and GitHub

## Project Structure

```text
TrafficManagementSystem/
│
├── src/
│   └── TrafficManagement/
│       ├── App.java
│       ├── Grid.java
│       ├── Car.java
