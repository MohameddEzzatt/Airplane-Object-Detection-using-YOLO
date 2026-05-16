# 🚗 Car Detection using YOLO

## 📌 Overview
This project implements a **Car Detection System** using the **YOLO (You Only Look Once)** object detection algorithm.  
The system can detect cars in images, videos, and real-time webcam streams with high accuracy and speed.

YOLO is one of the most popular real-time object detection models because it processes the image in a single pass, making it efficient for applications like:
- Traffic Monitoring
- Smart Parking Systems
- Autonomous Driving
- Surveillance Systems

---

# ✨ Features
- Real-time car detection
- Image and video processing
- Webcam support
- Fast and accurate detection using YOLO
- Bounding box visualization
- Easy-to-use training and testing pipeline

---

# 🛠️ Technologies Used
- Python
- YOLOv8 / YOLOv5
- OpenCV
- PyTorch
- NumPy

---

# 📂 Project Structure
```bash
car-detection-yolo/
│
├── dataset/
│   ├── images/
│   └── labels/
│
├── models/
│   └── best.pt
│
├── results/
│   ├── images/
│   └── videos/
│
├── detect.py
├── train.py
├── requirements.txt
└── README.md
