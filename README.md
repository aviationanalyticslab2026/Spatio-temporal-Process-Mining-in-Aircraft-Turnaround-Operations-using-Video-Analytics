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
├── README.md                         # Project overview and main documentation
├── repo_structure.txt                # Raw folder directory listing
└── data/                             # Data directory
    ├── Haneda_Flight_Tracker_Ground_Truth.xlsx  # Haneda flight tracking & ground operational data
    └── yolo26_apron_dataset/         # YOLO-formatted apron object detection dataset
        ├── data.yaml                 # YOLO dataset path and class configuration
        ├── README.dataset.txt        # Dataset version and source information
        ├── README.roboflow.txt       # Roboflow export metadata
        ├── test/                     # Model testing split
        │   ├── images/               # Test image frames (.jpg)
        │   └── labels/               # YOLO format bounding box annotations (.txt)
        └── train/                    # Model training split
        │   ├── images/               # Training image frames (.jpg)
        │   └── labels/               # YOLO format bounding box annotations (.txt)
        └── valid/                    # Model Validation split
            ├── images/               # Validation image frames (.jpg)
            └── labels/               # YOLO format bounding box annotations (.txt)
   └── models/
        └── yolo26_apron.pt           # YOLO model(.pt)
   └── src/

```
