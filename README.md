# 🧠 Object & Face Detection

This project demonstrates real-time **Object Detection** and **Face Detection** using OpenCV and pre-trained models. It serves as a compact and beginner-friendly implementation of core computer vision techniques for detecting faces and general objects from live camera feeds or video files.

---

## 🎯 Objectives

- Detect human faces using Haar Cascades and DNN models
- Detect general objects using YOLOv3 or MobileNet SSD
- Enable real-time video processing with bounding box overlays
- Support webcam input or video file streams

---

## 🔍 Features

- ✅ Face detection using:
  - Haar Cascades (lightweight and fast)
  - OpenCV DNN-based face detection (more accurate)
- ✅ Object detection using:
  - YOLOv3 or MobileNet SSD models
  - Class label annotations with confidence scores
- ✅ Real-time visualization with bounding boxes and labels
- ✅ Easy model switching via config flags

---

## 📁 Project Structure

```bash
Object-Face-Detection/
├── face_detection/
│   ├── haar_cascade_face.py
│   └── dnn_face_detection.py
├── object_detection/
│   ├── yolo_object_detection.py
│   └── mobilenet_ssd.py
├── models/
│   ├── haarcascade_frontalface_default.xml
│   ├── deploy.prototxt
│   └── res10_300x300_ssd_iter_140000.caffemodel
├── utils/
│   └── draw_utils.py
├── requirements.txt
└── README.md

⚙️ Installation
1. Clone the Repository
git clone https://github.com/siddarthx07/Object-Face-Detection.git
cd Object-Face-Detection

2. Create a Virtual Environment (optional but recommended)
python -m venv env
source env/bin/activate  # Windows: env\Scripts\activate

3. Install Dependencies
pip install -r requirements.txt
Or manually:
pip install opencv-python numpy imutils
🧪 Usage
🧍 Face Detection (Haar Cascade)

python face_detection/haar_cascade_face.py
🧍‍♂️ Face Detection (DNN)
python face_detection/dnn_face_detection.py
📦 Object Detection (YOLO or SSD)
python object_detection/yolo_object_detection.py
# OR
python object_detection/mobilenet_ssd.py
⚠️ Make sure corresponding model weights and config files are in the models/ directory.

📸 Sample Output
<table> <tr> <td><img src="docs/sample_face.png" width="300"/></td> <td><img src="docs/sample_object.png" width="300"/></td> </tr> </table>
🧰 Tools & Libraries
Python

OpenCV

NumPy

YOLO / Haar Cascades / MobileNet SSD

