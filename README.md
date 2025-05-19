Infrastructure Crack Detection and Localization Using YOLOv11

This repository showcases an automated system for crack detection and classification in civil infrastructure leveraging YOLOv11. It addresses the critical need for efficient, reliable, and scalable methods to monitor the structural integrity of infrastructure such as bridges, roads, and buildings.

Project Highlights:

Real-time Detection: Utilizes YOLOv11 architecture for rapid detection and localization of cracks.

Comprehensive Dataset: Employs a robust dataset of 2,159 annotated images covering various crack types and severities.

Advanced Preprocessing: Includes histogram equalization, grayscale conversion, and extensive data augmentation.

Multi-Class Classification: Classifies cracks into 11 distinct categories (e.g., diagonal, horizontal, vertical, tile damage).

Performance:

YOLOv11n: Achieved an mAP50 of 70.7% and mAP50-95 of 49.5%.

YOLOv11x: Demonstrated superior performance with enhanced detection capabilities for severe cracks.

Technologies:

YOLOv11 (Ultralytics): https://docs.ultralytics.com/models/yolo11/#supported-tasks-and-modes

PyTorch and OpenCV

Matplotlib for visualization

Demo Videos:

Detailed Walkthrough :https://www.youtube.com/watch?v=TGYzXQFG7sI

Setup and Usage:

Instructions for setting up the environment, training the models, and interpreting the results are detailed within the provided Jupyter notebook in the repository.

Dataset Source:https://universe.roboflow.com/iiti/civil-faults-detection

Civil Fault Detection Dataset
