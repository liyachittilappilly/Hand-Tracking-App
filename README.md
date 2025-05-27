# 🖐️ Real-Time Hand Tracking using OpenCV & MediaPipe

This Python project uses **OpenCV** and **MediaPipe** to detect and track hands in real time via webcam. It identifies hand landmarks and displays them with visual markers. Ideal for gesture recognition, sign language applications, and human-computer interaction projects.

---

## 📸 Demo

[https://github.com/liyachittilappilly/Hand-Tracking-App/blob/main/1748324324069.mp4)]

<!-- Replace this with a screen recording or GIF link -->

---

## 🚀 Features

* Real-time hand detection using MediaPipe
* Hand landmark drawing on the video feed
* Support for detecting up to 2 hands simultaneously
* Customizable parameters for detection & tracking confidence
* FPS (Frames Per Second) display for performance monitoring

---

## 🛠️ Installation

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/hand-tracking-mediapipe.git
cd hand-tracking-mediapipe
```

### 2. Create a Virtual Environment (Optional but Recommended)

```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

If `requirements.txt` is missing, install manually:

```bash
pip install opencv-python mediapipe
```

---

## 📄 Usage

Run the script:

```bash
python hand_tracking.py
```

* Press **`d`** to exit the program.

---

## 📁 File Structure

```bash
hand-tracking-mediapipe/
│
├── hand_tracking.py     # Main script
├── README.md            # Project documentation
└── requirements.txt     # Dependencies list (optional)
```

---

## ✏️ Customize

Inside `HandDetector` class, you can tweak:

* `maxHands`: Max number of hands to detect
* `detectionConf`: Minimum confidence for detection
* `trackingConf`: Confidence for tracking hands over time

Example:

```python
detector = HandDetector(maxHands=1, detectionConf=0.7, trackingConf=0.7)
```

---

## 🧠 Based On

* [MediaPipe Hands by Google](https://google.github.io/mediapipe/solutions/hands)
* [OpenCV](https://opencv.org/)

---

## 🙌 Acknowledgements

Special thanks to [AI with Noor]((https://youtu.be/gko4WnAgzz4?feature=shared)) for the tutorial inspiration.

