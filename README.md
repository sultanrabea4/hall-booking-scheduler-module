# Hall Booking Management System: Scheduler Module (Java Swing)

The **Scheduler** module of a desktop **Hall Booking Management System** built with **Java Swing** and object-oriented design.

> Object-Oriented Development group project (4 members, one user role each). This repository contains **my part: the Scheduler role**. I also designed the system's **class diagram** and co-developed the additional features. The Customer, Administrator and Manager modules were built by teammates and are not included here.

---

## Scheduler Features
| Screen | What it does |
|---|---|
| **Scheduler Home** | Main navigation for the scheduler role |
| **Hall Management** | Add, edit, delete and clear hall records (ID, type, hourly rate, capacity) |
| **Hall Availability Schedule** | Set the date and time windows when each hall is available for booking |
| **Maintenance Schedule** | Block halls for maintenance and prevent clashes with availability |

Data is saved in text files (`view_halls.txt`, `availability_schedule.txt`, `maintenance_schedule.txt`).

## OOP Concepts Applied
Encapsulation · inheritance (Swing `JFrame` subclasses) · event-driven programming · file-based persistence · input validation

## Tech Stack
Java · Swing (NetBeans GUI Builder) · File I/O

## Run
```bash
javac -d out src/*.java
java -cp out HomePage
```
Or open the `src` folder in **NetBeans**. Run it from the project root so the `.txt` data files are found.

> In the full system, Logout returns to the shared login screen built by a teammate. In this standalone module it simply closes the window.

## Author
**Sultan Mohammed Rabea** · [LinkedIn](https://www.linkedin.com/in/sultan-rabea/) · [GitHub](https://github.com/sultanrabea4)
