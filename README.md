
# Object Identifier and Surveillance Rover using ESP32-CAM & OpenCV

## Project Overview

This project implements a **surveillance rover capable of detecting and identifying objects in real-time** using the **ESP32-CAM module and OpenCV with a pretrained Machine Learning model**.

The rover captures live video through the ESP32-CAM, streams it to a computer, and processes the frames using **OpenCV object detection algorithms**. The detected objects are highlighted and labeled automatically.

This system can be used for:

* Security surveillance
* Remote monitoring
* Smart robotics applications
* Educational AI & IoT projects

---

## Technologies Used

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
Example detected objects:

* Person
* Bottle
* Chair
* Car

---

## Applications

* Home security robot
* Military surveillance rover
* Smart agriculture monitoring
* Autonomous inspection robot


Just tell me.
