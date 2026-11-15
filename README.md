# DD Car Rental System

A first-year university project demonstrating Object-Oriented Programming (OOP) through a car rental simulation built entirely in Java.

## Overview

**DD Car Rental System** is a desktop-based Java application that simulates a car rental workflow.
Users can **book**, **rent**, and **pay** for vehicles within the same interface.

Developed using **Java Swing** and **Eclipse IDE**, the project applies key **OOP concepts** for cleaner, modular, and reusable code —
making it an excellent foundation for learning real-world Java architecture.

## Features

### Car Booking

- Browse and select available cars
- Book by preferred date and time

### Car Rental Simulation

- Convert booked cars to "rented" state
- Track rental status dynamically

### In-App Payment Simulation

- Simulate payments for rentals within the app

### OOP Architecture

Implements essential OOP principles:

- **Classes & Objects**
- **Inheritance**
- **Polymorphism**
- **Encapsulation**
- **Abstraction**

## Tech Stack

| Category | Technology |
|-----------|-------------|
| Language | **Java (JDK 17, matching the Eclipse project configuration)** |
| UI Framework | **Java Swing** |
| IDE | **Eclipse IDE** |

## Run locally

1. Install JDK 17 and Eclipse IDE for Java Developers.
2. Clone this repository and choose **File → Import → Existing Projects into Workspace** in Eclipse.
3. Select the repository root, which contains `.project` and `.classpath`.
4. Keep the bundled JAR dependencies available at the paths declared in `.classpath`.
5. Run **`src/main/Launcher.java`** as a Java Application. It initializes the look and feel and opens the main window.
6. Set the run configuration's working directory to the repository root so relative files such as `carinfo.txt`, `register.txt`, and `billpayment.txt` resolve correctly.

Use a disposable copy of the sample text files when exploring booking and payment flows: this academic simulation can update its local records. Payments are simulated; no real payment integration is documented.
