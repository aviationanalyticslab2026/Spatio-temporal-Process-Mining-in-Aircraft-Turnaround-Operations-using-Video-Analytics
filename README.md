# Spatio-temporal Process Mining in Aircraft Turnaround Operations using Video Analytics
A video-analytics framework that extracts temporal and spatial operational data from apron surveillance videos. It automatically derives activity service times, process precedence relationships, and birds eye view vehicle trajectories to optimize resources, analyze turnaround performance, and power apron simulations.

## Dataset Description
Location: Gate 59, Haneda Airport.
Collection Period: 26 days (October 21 – December 9, 2024).
Sample Size: 146 aircraft turnarounds.

## Repository Structure
```text
├── data/
│   ├── raw_video/               # Surveillance video streams
│   ├── ground_truth/            # Manual timestamp annotations (n=146)
│   └── processed/               # Standardized operational datasets (CSV)
├── models/
│   └── yolo26_apron.pt          # YOLO-26 object detection weights
├── src/
│   └── detection_tracking.py    # Detection and object tracking pipeline
├── requirements.txt
└── README.md
