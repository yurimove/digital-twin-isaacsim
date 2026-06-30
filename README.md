# Digital Twin of Real-World Objects using NVIDIA Isaac Sim

This project demonstrates the creation of digital twins of real-world peripherals using **Polycam** and **NVIDIA Isaac Sim**.

## Project Overview

The objective of this project was to scan real-world objects and recreate them inside NVIDIA Isaac Sim as digital twins.

The scanned objects include:

- Keyboard
- Mouse

The resulting models were imported into Isaac Sim, scaled appropriately, and positioned within the simulation environment.

---

## Workflow

1. Capture objects using Polycam on an iPhone 13 Pro Max (LiDAR).
2. Process the scan into a 3D model.
3. Export the model.
4. Import the model into NVIDIA Isaac Sim.
5. Adjust scaling and placement.
6. Validate the imported digital twin.

---

## Technologies Used

- NVIDIA Isaac Sim
- Polycam
- NVIDIA Omniverse
- USD

---

## Repository Structure

```
assets/
    keyboard.usd
    mouse.usd

demo/
    demo.mp4
```

---

## Demo

A demonstration video of the imported digital twin is included in the `demo` folder.

---

## Learning Outcomes

- Digital Twin creation
- LiDAR-based 3D scanning
- USD asset handling
- Asset import into NVIDIA Isaac Sim
- Scene scaling and placement

---

## Author

Aria
Engineering Student (AI & ML)
