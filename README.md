# Tennis Analysis System 


A Deep Learning and Computer Vision project developed to automate player and tennis ball tracking, court line detection, and player performance analysis. 

## Overview
This project leverages **YOLOv8** and **PyTorch** to process tennis match footage. It doesn't just track objects; it maps player movements onto a 2D mini-court to calculate distance covered, speed, and positioning.



## Key Features
* **Player Detection & Tracking:** Real-time tracking of players using YOLOv8 and Sort-based tracking.
* **Ball Detection:** Specialized model fine-tuned for high-speed tennis ball movement.
* **Court Segmentation:** Automated detection of court lines for spatial normalization.
* **Tactical Mapping:** 2D top-down projection (mini-court) of player and ball coordinates.
* **Speed & Distance Analytics:** Automatic calculation of player stats throughout the match.

## Project Structure
```text
├── analysis/               # Jupyter notebooks for data exploration
├── court_line_detector/    # Logic for identifying court boundaries
├── trackers/               # Core tracking algorithms for ball and players
├── mini_court/            # Transformation logic for 2D mapping
├── utils/                  # Video processing & conversion helpers
├── input_videos/           # Raw match footage (LFS managed)
├── output_videos/          # Final annotated footage (LFS managed)
├── yolo_inference.py       # Main inference script
└── yolov8x.pt              # Pre-trained YOLOv8 weights (LFS managed)
