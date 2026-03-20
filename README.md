# 🧍‍♂️ Real-Time Pose Detector using PoseNet

A browser-based **real-time human pose detection system** built using PoseNet, capable of identifying body keypoints and analyzing human movements through a webcam.

This project demonstrates the practical application of **computer vision + deep learning** for interactive pose recognition systems.

---

## 🚀 Project Overview

This application uses **PoseNet**, a deep learning model that detects human body keypoints (like shoulders, elbows, knees, etc.) in real time.

Pose estimation enables machines to understand human movement without identifying the person—only the position of joints is tracked ([GitHub][1]).

The system processes webcam input and outputs:

* Body keypoints (x, y coordinates)
* Skeleton structure
* Real-time pose visualization

---

## ✨ Features

* 🎥 **Real-time pose detection via webcam**
* 🧠 **PoseNet-based keypoint extraction (17 body points)**
* 🦴 **Skeleton visualization**
* ⚡ **Runs directly in the browser**
* 🧩 Lightweight and interactive UI
* 🔍 Supports **single-person pose detection**

---

## 🛠️ Tech Stack

* **JavaScript**
* **PoseNet (TensorFlow.js / ml5.js)**
* **p5.js**
* **HTML/CSS**

---

## 📂 Project Structure

```id="3y8x2k"
pose-detector-posenet/
│── index.html        # Main UI
│── sketch.js         # Core logic for pose detection
│── posedata.json     # Pose data storage (if applicable)
│── model/            # Trained model files (if any)
│── README.md
```

---

## ⚙️ Installation & Setup

1. Clone the repository:

```bash id="r9s2kd"
git clone https://github.com/subhimaheshwari/pose-detector-posenet.git
cd pose-detector-posenet
```

2. Open the project:

* Simply open `index.html` in your browser
  *(or use Live Server in VS Code for better performance)*

---

## ▶️ Usage

* Allow webcam access
* Stand in front of the camera
* Observe real-time pose detection
* Body keypoints and skeleton will be displayed

---

## 🧠 How It Works

### 1. Input Capture

* Webcam feed is captured using browser APIs

### 2. PoseNet Model

* Detects **17 keypoints** of the human body
* Each keypoint contains:

  * X, Y coordinates
  * Confidence score

### 3. Visualization

* Keypoints plotted as dots
* Skeleton drawn by connecting joints

### 4. Output

* Real-time pose tracking on screen

PoseNet works using deep learning (CNN-based architecture) to estimate body posture from images or video streams ([GitHub][2]).

---

## 📸 Output

* Live video feed
* Body keypoints overlay
* Skeleton structure
* Real-time motion tracking

---

## 🎯 Use Cases

* Fitness & workout tracking
* Gesture-based applications
* Interactive games
* Human-computer interaction
* AI learning projects

---

## 📈 Future Improvements

* Multi-person detection support
* Gesture classification (e.g., wave, salute)
* Exercise recognition (squats, push-ups)
* Integration with mobile/web apps
* Performance optimization

---

## 🤝 Contributing

Contributions are welcome!

* Fork the repo
* Create a feature branch
* Submit a pull request

---

## 📜 License

This project is open-source and available under the **MIT License**.

---

## 👩‍💻 Author

**Subhi Maheshwari**

* GitHub: [https://github.com/subhimaheshwari](https://github.com/subhimaheshwari)
