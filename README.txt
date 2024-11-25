# YOLO Model Training

This project demonstrates how to train a YOLO model using the `ultralytics` library in Python. The code is designed to fine-tune the YOLOv10x architecture on a custom dataset for object detection tasks.

## Prerequisites

Ensure you have the following installed:

- Python 3.10 or above
- `torch` (PyTorch 2.4.1 or compatible version)
- `ultralytics` library (`pip install ultralytics`)
- NVIDIA GPU with CUDA enabled

Dataset/
├── images/
│   ├── Train/
│   ├── Val/
│   ├── Test/
├── labels/
│   ├── Train/
│   ├── Val/
│   ├── Test/

Step 1: Place the YOLOv9 pre-trained model weights (yolov9.pt) in the project directory.
Step 2: Start training
Step 3: After training, you can find the results (metrics, predictions, model weights) in the runs/detect directory.