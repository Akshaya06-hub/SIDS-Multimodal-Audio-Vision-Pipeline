# Multimodal SIDS Risk Prediction System

A real-time infant health monitoring system architecture combining computer vision posture tracking (YOLOv8) and acoustic classification (CNN) to assess physiological risk factors and trigger instant alerts.

## 🚀 Features
* **Vision Pipeline:** Utilizes YOLOv8 for real-time infant posture and prone-position detection.
* **Audio Pipeline:** Processes acoustic cry streams using a custom Convolutional Neural Network (CNN) feature extractor.
* **Multimodal Decision Fusion:** Combines vision and audio confidence scores with temporal smoothing to drastically minimize false positives.

## 🛠️ Tech Stack
* Python
* Ultralytics YOLOv8
* OpenCV Headless / NumPy / PyTorch concepts

## ⚙️ How to Run
1. Clone the repository:
   ```bash
   git clone [https://github.com/Akshaya06-hub/SIDS-Multimodal-Audio-Vision-Pipeline.git](https://github.com/Akshaya06-hub/SIDS-Multimodal-Audio-Vision-Pipeline.git)
