# Hough Transform for Line Detection with GUI

This project implements the Hough Transform algorithm for line detection, allowing users to either manually place points or upload an image with edge detection. The algorithm is implemented from scratch without using predefined functions. The project includes a GUI to visualize the process, making it interactive and user-friendly.

## Features

- **Manual Point Placement**: Users can place points on a screen by clicking, and the Hough Transform will connect those points by detecting the line(s).
- **Edge Detection Image Upload**: Users can upload an image containing edge points (e.g., from an edge detector), and the Hough Transform will detect and connect the edges to form lines.
- **Custom Hough Transform Algorithm**: The algorithm is developed from scratch and does not rely on any predefined functions for the Hough Transform.
- **Graphical User Interface**: A GUI built using Tkinter allows users to interact with the system and visualize the line detection process.

## Requirements

- Python 3.x
- Tkinter (for GUI)
- NumPy (for numerical calculations)
- OpenCV (for edge detection and image processing)

To install the necessary dependencies, run:

```bash
pip install tkinter numpy opencv-python
