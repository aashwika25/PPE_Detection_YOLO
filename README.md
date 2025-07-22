# PPE Detection using YOLO 

<p align="center">
  <img src="https://img.shields.io/badge/YOLOv5-blue.svg?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Computer%20Vision-purple.svg?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Flask-black.svg?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Object%20Detection-green.svg?style=for-the-badge" />
  <img src="https://img.shields.io/badge/PPE-orange.svg?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Safety-red.svg?style=for-the-badge" />
  <img src="https://img.shields.io/badge/AI-grey.svg?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Deep%20Learning-yellow.svg?style=for-the-badge" />
</p>

---
A real-time **Personal Protective Equipment (PPE) detection system** built with **YOLOv5**, **Flask**, and **OpenCV**. This system identifies and classifies safety gear violations in industrial environments — helping ensure workplace safety by detecting:

- ✅ Hardhat / ❌ No Hardhat  
- ✅ Mask / ❌ No Mask  
- ✅ Safety Vest / ❌ No Safety Vest  
- 👷 Person  
- 🚧 Safety Cone  
- 🏗 Machinery  
- 🚗 Vehicle

---

## 🎯 Project Goal

To build a lightweight, scalable, and accurate object detection system that can help organizations monitor employee safety compliance on-site using video/image input.

---

## 🧠 What It Detects

- `Hardhat`, `NO-Hardhat`  
- `Mask`, `NO-Mask`  
- `Safety Vest`, `NO-Safety Vest`  
- `Person`, `Safety Cone`, `Machinery`, `Vehicle`

---
## 📂 Dataset

- Source: [Roboflow PPE Detection Dataset](https://roboflow.com)
- **Classes**: 10 (as listed above)
- **Training**: 2600 images  
- **Validation**: 114 images  
- **Test**: 82 images  
- **Input Dimension**: 640 × 640 px

---

## 🧰 Tech Stack

- **Model:** YOLOv5 (Ultralytics)  
- **Frameworks:** OpenCV, Flask  
- **Languages:** Python  
- **Environment:** Jupyter, Localhost  
- **Hardware:** Intel i7 CPU, GPU optional (CUDA supported)  
- **Libraries:** PyTorch, NumPy, Matplotlib
- Git LFS (for large model files)

---


## 🚀 Installation & Setup

1. **Clone the repository**
```bash
git clone https://github.com/aashwika25/PPE_Detection_YOLO.git
cd PPE_Detection_YOLO
```
2. **Create a Conda environment (or use virtualenv)**
```bash
conda create -n myyolo python=3.10 -y
conda activate myyolo
```

3. **Install requirements**
```bash
pip install -r requirements.txt
```

4. **Run the application**
```bash
python app.py
```

5. **Open in your browser:**
```bash
Go to http://localhost:5000
```

---
## Results : 

![1](https://user-images.githubusercontent.com/103372852/233774695-ad3b800b-5d8e-4583-a395-e70ac86f2dda.PNG)

![3](https://user-images.githubusercontent.com/103372852/233774758-180186a2-8267-495b-8c04-0d43778299d2.PNG)

---
## ✅ Features

- Upload image or video for real-time PPE detection  
- Live webcam stream with safety gear classification  
- Fast and accurate inference using YOLOv5  
- Web interface built using Flask  
- Tracks compliance for hardhats, masks, and vests  
- Supports detection of multiple people and objects simultaneously  
- Lightweight and easy to deploy locally

---

## 📈 Performance Benchmarks

| Mode       | FPS (YOLOv5s) | FPS (YOLOv5m) | Observations                       |
|------------|----------------|----------------|------------------------------------|
| Image      | 35+           | 25+           | Fastest mode                       |
| Video      | 18–25         | 12–18         | CPU bottleneck for heavier models |
| Webcam     | ~20           | ~14           | Stable for real-time detection     |

---

## 🔮 Future Improvements

- Integrate IP camera for remote/real-time surveillance  
- Add automatic alerts (email/SMS/buzzer) for violations  
- Export detection logs and statistics (CSV/JSON format)  
- Deploy on edge devices like NVIDIA Jetson or Raspberry Pi  
- Dockerize the app for portable deployment  
- Enable multilingual interface and accessibility features

---




