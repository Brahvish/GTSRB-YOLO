# 🚦 Traffic Sign Detection Using YOLOv8

A custom-trained YOLOv8 model for real-time traffic sign detection on the German Traffic Sign Recognition Benchmark (GTSRB) dataset.

---

## 📌 Features
- ✅ Real-time detection from webcam.
- ✅ Image detection on test dataset.
- ✅ Trained YOLOv8n model on 43 traffic sign classes.

---

## Dependencies
- Python 3.10+
- CUDA 12.1 (for GPU support)
- PyTorch 2.5.1 with cu121 build
- YOLOv8 (Ultralytics 8.3.0)
- OpenCV, Numpy

---

## 📁 Project Structure
GTSRB-YOLO/
├── detect_camera.py
├── traffic-sign.yaml
├── best.pt
├── requirements.txt
├── README.md
├── data/
│ ├── images/
│ │ ├── train_png/
│ │ └── test_png/
│ └── labels/
│ ├── train_png/
│ └── test_png/
└── runs/ (auto-created during training and predictions)