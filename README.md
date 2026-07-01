Real-Time Indian Currency Detection System

```markdown
# Real-Time Indian Currency Detection System 💵

An advanced, real-time computer vision application designed to detect, classify, and calculate the value of Indian currency notes, built to improve accessibility for visually impaired individuals.

---

## ✨ Features

- **Object Detection:** Implements the state-of-the-art YOLOv5 object detection framework to identify various denominations of Indian currency notes accurately.
- **Accessibility Integration:** Engineered with bilingual (English & Hindi) Text-to-Speech output to provide instant audio feedback to users upon successful note detection.
- **Value Aggregation:** Features real-time, automatic currency calculation logic that computes the total monetary value displayed inside the camera frame.
- **Optimized Pipeline:** Streamlined image preprocessing routines, inference loops, and confidence thresholds to ensure ultra-low prediction latency on standard webcams.
- **Web-Based Controller:** Built a clean Flask web interface mapping real-time webcam inference to live video bounding box visualizations.

## 🛠️ Tech Stack

- **Core Language:** Python
- **Computer Vision & ML:** YOLOv5, OpenCV, NumPy, PyTorch
- **Web Framework:** Flask
- **Interface Mechanics:** Live Webcam Stream Integration, Web Speech Synthesis / Audio API

---

## 💻 Local Installation & Setup

1. **Clone the Repository:**
   ```bash
   git clone [https://github.com/jaswanthneelam/Indian-Multiple-currency-notes-detection-using-yolov5.git](https://github.com/jaswanthneelam/Indian-Multiple-currency-notes-detection-using-yolov5.git)
   cd Indian-Multiple-currency-notes-detection-using-yolov5
   Set Up Environment & Dependencies:
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
pip install -r requirements.txt
Download Model Weights:
Ensure your custom trained YOLOv5 weights (best.pt) are placed inside the specified weights directory.
Launch the Flask Application:
python app.py
Open your browser and navigate to http://127.0.0.1:5000 to start the local webcam inference.
