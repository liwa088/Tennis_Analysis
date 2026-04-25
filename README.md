# Tennis Analysis System 

A Computer Vision and Deep Learning project designed to track players and tennis balls in match footage, detect court boundaries, and calculate player statistics. This project was developed as part of my Third Year (Semester 2) studies in Computer Engineering.

## Overview
This system utilizes **YOLOv8** for object detection and **PyTorch** for custom tracking logic. It processes raw tennis match videos to produce annotated footage with real-time tracking data.

## Tech Stack
* **Deep Learning:** PyTorch, YOLOv8
* **Computer Vision:** OpenCV
* **Data Handling:** Pandas, NumPy
* **Large File Management:** Git LFS (for models and video assets)

## Project Structure
* `trackers/`: Logic for player and ball tracking.
* `utils/`: Helper functions for video processing and bounding box calculations.
* `models/`: Pre-trained YOLO models and custom weights (`yolov8x.pt`).
* `input_videos/`: Raw match footage.
* `output_videos/`: Processed videos with tracking overlays.
* `analysis/`: Jupyter notebooks for data exploration and ball trajectory analysis.

## Installation

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/liwa088/Tennis_Analysis.git](https://github.com/liwa088/Tennis_Analysis.git)
   cd Tennis_Analysis
