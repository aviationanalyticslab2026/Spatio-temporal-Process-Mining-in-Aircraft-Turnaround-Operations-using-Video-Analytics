# Spatio-temporal Process Mining in Aircraft Turnaround Operations using Video Analytics
A video-analytics framework that extracts temporal and spatial operational data from apron surveillance videos. It automatically derives activity service times, process precedence relationships, and birds eye view vehicle trajectories to optimize resources, analyze turnaround performance, and power apron simulations.

## Dataset Description
```text
Location: Gate 59, Haneda Airport.
Collection Period: Between October 21 – November 18, 2024
Sample Size: 149 aircraft turnarounds.
```
## Repository Structure
```text
├── data/
│   ├── raw_video/               # Surveillance video streams
│   ├── ground_truth/ 
│   └── processed/               # Standardized operational datasets (CSV)
├── models/
│   └── yolo26_apron.pt          # YOLO-26 object detection weights
├── src/
│   └── detection_tracking.py    # Detection and object tracking pipeline
├── requirements.txt
└── README.md
```
