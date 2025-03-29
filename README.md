# Sports Video Tracking using Deep Learning

## Overview
This project implements a tracking model for sports videos using the SportsMOT dataset. The goal is to detect and track players and the ball in sports footage using deep learning and tracking algorithms. The pipeline includes:

- **Object Detection**: Fine-tuned a YOLO model for detecting players and the ball.
- **Single-Object Tracking**: Implemented CSRT tracking and generated heatmaps for tracked players.
- **Multiple-Object Tracking (MOT)**: Used ByteTrack and DeepSORT for robust multi-object tracking.
- **Challenges & Solutions**: Addressed challenges such as occlusions, varying lighting conditions, and tracking consistency.

## Features
- Fine-tuned **YOLO** for sports object detection.
- Implemented **CSRT tracker** for single-player tracking with heatmap visualization.
- Used **ByteTrack** and **DeepSORT** for multiple-object tracking.
- Processed SportsMOT dataset to test and validate tracking performance.
- Optimized tracking pipeline for real-time processing.

## Dataset
The **SportsMOT** dataset is used for training and evaluation. It consists of annotated sports footage with labeled player and ball positions.

## Results
Sample outputs, including detection and tracking visualizations, can be found in the `phase 2 sample outputs/` directory.

## Challenges Faced
- **Occlusion Handling**: Improved tracking robustness using DeepSORT with re-identification features.
- **Tracking Consistency**: Tuned hyperparameters to maintain stable object tracking.
- **Speed Optimization**: Balanced accuracy and efficiency for real-time inference.

## Future Improvements
- Train a **custom tracking model** to enhance accuracy.
- Experiment with **transformer-based tracking** approaches.
- Improve tracking under **challenging lighting conditions**.

## Contributing
Feel free to submit pull requests or open issues to improve the project!

## License
SUT License

---

📌 **Author:** Adel 
movahedian

