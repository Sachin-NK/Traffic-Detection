# Traffic Detection with YOLOv8

This project implements a traffic detection system using the YOLOv8 model to detect and count vehicles in a video stream. The system also provides a visual representation of vehicle distribution across three lanes using a pie chart and additional graphical overlays.

## Features

- **Vehicle Detection**: Detects vehicles such as cars trucks and motorcycles in the video stream.
- **Lane Counting**: Divides the frame into three regions (left, middle, and right) and counts the vehicles passing through each region.
- **Visual Overlays**: Displays graphical overlays such as:
  - Vehicle count for each lane.
  - Pie chart representing vehicle distribution.
  - Direction indicators for vehicles (up and down).
- **Tracking**: Simple tracker to maintain vehicle IDs and track their movements across frames.
