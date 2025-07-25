# CodeDeployGitHubDemo

# 🛠️ Surface Defect Detection using Deep Learning

[![Build Status](https://img.shields.io/badge/build-passing-brightgreen.svg)](https://github.com/niharika3425/Surface_Defect_Detection/actions)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange.svg)
![OpenCV](https://img.shields.io/badge/OpenCV-4.x-green.svg)

This repository presents a comprehensive approach to detecting surface defects (such as scratches, dents, pits, and cracks) using deep learning and computer vision. It combines preprocessing, defect classification, and result visualization for industrial quality control applications.

![Defect Detection Example](https://github.com/niharika3425/Surface_Defect_Detection/assets/example.jpg)

---

## 📌 Features

- ✅ Real-time surface defect detection
- 📷 Image preprocessing using OpenCV
- 🧠 Deep learning model for defect classification (`defect_model.h5`)
- 📊 Visualization of defect regions with bounding boxes
- 🧪 Easy-to-modify and test new images
- 💡 Modular structure for scalability

---

## 🧾 Table of Contents

1. [Dataset](#-dataset)
2. [Requirements](#-requirements)
3. [Usage](#-usage)
4. [Project Structure](#-project-structure)
5. [Results](#-results)
6. [To-Do](#-to-do)
7. [License](#-license)

---

## 📁 Dataset

- You can use any labeled dataset of surface defects.
- Example categories: `Scratch`, `Crack`, `Dent`, `Pitting`, etc.
- [Optional] You can integrate your own industrial surface image dataset with proper annotations.

---

## 💻 Requirements

Install dependencies using pip:

```
pip install -r requirements.txt
```



🚀 Usage
Clone the repository:
```
git clone https://github.com/niharika3425/Surface_Defect_Detection.git
cd Surface_Defect_Detection
```
Place your test images in the test_images/ folder.

Run the detection script:

```
python detect_defects.py
```
Output: The model will display and save images with defect regions highlighted.

🧾 Project Structure
```
Surface_Defect_Detection/
│
├── defect_model.h5           # Trained defect detection model
├── detect_defects.py         # Main script for detection
├── utils.py                  # Utility functions for preprocessing
├── test_images/              # Folder for input images
├── results/                  # Output folder for processed images
├── requirements.txt          # Python dependencies
└── README.md                 # This file
```
📷 Results
Example outputs:
```
Red boxes indicate predicted defect areas.

Classification labels are shown with confidence scores.

Original Image	Detected Defects
```

📌 To-Do
```
 Integrate YOLOv8 or Faster R-CNN for real-time detection

 Add support for video input

 Implement GUI for image upload and result display

 Evaluate on more diverse industrial datasets

 Add multilingual support for industrial deployment
```
🪪 License
```
This project is licensed under the MIT License.
```
🙋‍♀️ Author
```
Niharika Chauhan
📍 Amanvihar, Dehradun, India
📫 chauhanniharika254@gmail.com
🔗 LinkedIn | GitHub
```
