# AI-Powered E-Waste Detection and Sorting System

##  Overview

The **AI-Powered E-Waste Detection and Sorting System** is an intelligent waste management solution that leverages **YOLOv8** and a **4-DOF robotic arm** to automatically detect, classify, and segregate electronic waste in real time.

The system captures live video using a USB camera, detects e-waste objects with a custom-trained YOLOv8 model, classifies them into **High**, **Moderate**, and **Low** hazard categories, and sends commands to an **Arduino Uno** to control the robotic arm for automated pick-and-place operations.

By reducing manual intervention, the system improves recycling efficiency, minimizes human exposure to hazardous materials, and promotes sustainable e-waste management.

---

##  Key Features

- Real-time e-waste detection using **YOLOv8**
- Automatic classification into **High**, **Moderate**, and **Low** hazard categories
- AI-based object detection through a live USB camera
- Automated robotic arm pick-and-place mechanism
- Fast and accurate deep learning inference
- Arduino Uno integration for robotic arm control
- Real-time waste segregation with minimal human intervention
- Modular and scalable system architecture

---

## 🛠️ Technologies Used

- Python
- YOLOv8 (Ultralytics)
- OpenCV
- Computer Vision
- Arduino Uno
- 4-DOF Robotic Arm
- USB Camera
- NumPy
- PySerial
- Roboflow
- Custom Dataset Training

---

## 📂 Dataset

The model was trained on a **custom e-waste dataset** collected and annotated using **Roboflow**.

### Dataset Link
https://app.roboflow.com/manab-jyoti-goswami-lqvan/e-waste-oeexv/8

### Object Classes

- Mobile Phone
- Laptop
- Mouse
- PCB
- Cable
- Bulb
- Battery
- Other E-Waste Components

### Hazard Categories

Each detected object is assigned to one of the following hazard levels:

- 🔴 High Hazard
- 🟡 Moderate Hazard
- 🟢 Low Hazard

---

## 📊 Experimental Results

The proposed system achieved:

- High-accuracy real-time e-waste detection using YOLOv8
- Reliable hazard-level classification
- Fast inference suitable for real-time deployment
- Successful robotic arm-based pick-and-place operation
- Reduced manual handling of hazardous electronic waste
- Improved sorting efficiency and workplace safety

---

## 🔄 Project Workflow

1. Capture live video using a USB camera.
2. Process each video frame with the YOLOv8 object detection model.
3. Detect and classify e-waste objects.
4. Assign each object to its corresponding hazard category.
5. Send the classification result to the Arduino controller.
6. Control the robotic arm to pick the detected object.
7. Place the object into the corresponding hazard-specific bin.
8. Continue the detection and sorting process in real time.

---

##  Applications

- Smart E-Waste Recycling Plants
- Automated Waste Segregation Systems
- Industrial Recycling Facilities
- Research and Academic Projects
- Smart City Initiatives
- Sustainable Waste Management

---

##  Future Improvements

- Expand the dataset with additional e-waste categories.
- Improve model accuracy using larger and more diverse datasets.
- Deploy the system on embedded platforms such as **NVIDIA Jetson** or **Raspberry Pi**.
- Integrate a conveyor belt system for large-scale industrial automation.
- Optimize inference speed for edge-device deployment.

---

##  System Architecture

```
USB Camera
      │
      ▼
YOLOv8 Object Detection
      │
      ▼
Hazard Classification
      │
      ▼
Arduino Uno Controller
      │
      ▼
4-DOF Robotic Arm
      │
      ▼
E-Waste Sorting Bin
```

---

## 🎯 Project Objective

The primary objective of this project is to develop an AI-powered automated system capable of detecting, classifying, and sorting electronic waste with minimal human intervention. The system aims to improve recycling efficiency, enhance operational safety, and contribute to sustainable e-waste management practices.

---

