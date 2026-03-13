
# 🚗 Object Identifier and Surveillance Rover using ESP32-CAM & OpenCV

## 📌 Project Overview

This project implements a **surveillance rover capable of detecting and identifying objects in real-time** using the **ESP32-CAM module and OpenCV with a pretrained Machine Learning model**.

The rover captures live video through the ESP32-CAM, streams it to a computer, and processes the frames using **OpenCV object detection algorithms**. The detected objects are highlighted and labeled automatically.

This system can be used for:

* Security surveillance
* Remote monitoring
* Smart robotics applications
* Educational AI & IoT projects

---

## ⚙️ Technologies Used

### Hardware

* ESP32-CAM
* L298N Motor Driver
* DC Motors
* Rover Chassis
* Power Supply / Battery Pack
* FTDI Programmer

### Software

* Python
* OpenCV
* Pretrained ML Model (COCO dataset / MobileNet SSD / YOLO)
* Arduino IDE
* ESP32 Camera Web Server

---

## 🧠 System Architecture

```
ESP32-CAM  →  WiFi Video Streaming  →  Computer
                                      ↓
                                 OpenCV
                                      ↓
                          Object Detection Model
                                      ↓
                         Bounding Box + Label Display
```

---

## 🔧 Features

* 📷 Live video streaming from ESP32-CAM
* 🤖 Real-time object detection using OpenCV
* 📦 Uses pretrained ML models (no training required)
* 🚗 Mobile rover platform for surveillance
* 🌐 Wireless monitoring via WiFi

---

## 📁 Project Structure

```
Object-Identifier-Rover
│
├── esp32_cam_code
│   └── esp32_camera_stream.ino
│
├── object_detection
│   └── detect_objects.py
│
├── models
│   ├── MobileNetSSD_deploy.prototxt
│   └── MobileNetSSD_deploy.caffemodel
│
├── images
│   └── project_setup.png
│
└── README.md
```

---

## 🚀 Installation

### 1️⃣ Clone Repository

```bash
git clone https://github.com/yourusername/object-identifier-rover.git
cd object-identifier-rover
```

---

### 2️⃣ Install Python Dependencies

```bash
pip install opencv-python numpy imutils
```

---

### 3️⃣ Upload ESP32-CAM Code

1. Open **Arduino IDE**
2. Select **ESP32-CAM board**
3. Upload the camera streaming code
4. Connect ESP32-CAM to WiFi

---

### 4️⃣ Run Object Detection

```bash
python detect_objects.py
```

---

## 🖥 Example Output

* Bounding boxes around detected objects
* Object name displayed
* Real-time frame processing

Example detected objects:

* Person
* Bottle
* Chair
* Car

---

## 📊 Applications

* Home security robot
* Military surveillance rover
* Smart agriculture monitoring
* Autonomous inspection robot

---

## 🔮 Future Improvements

* Add **autonomous navigation**
* Integrate **GPS tracking**
* Deploy **custom trained ML models**
* Add **mobile app control**

---

## 👨‍💻 Author

**Govarthan K**

---

## 📜 License

This project is open-source and available under the **MIT License**.

---

If you want, I can also give you:

* ⭐ **Better GitHub README with badges and screenshots**
* 📊 **System architecture diagram**
* 🔧 **Complete OpenCV Python code**
* 🚗 **ESP32-CAM rover control code**

Just tell me.
