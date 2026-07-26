# PPE Compliance Checker

## Project Overview

The PPE Compliance Checker is a computer vision project designed to automatically determine whether construction workers are wearing the required Personal Protective Equipment (PPE). Using YOLO11 object detection, the system identifies workers and detects safety equipment such as hard hats, safety vests, and safety goggles to determine compliance with workplace safety requirements.

This project was completed as the **Midterm Project** for **ITAI 1378 – Computer Vision** at **Houston City College**. The project proposal and design were presented as part of the course requirements. :contentReference[oaicite:0]{index=0}

---

## Problem Statement

Workers in construction and industrial environments do not always wear the required protective equipment, increasing the risk of workplace injuries. Manual inspections can be time-consuming and inconsistent.

This project explores how computer vision can automate PPE compliance monitoring to improve workplace safety and reduce operational risks. :contentReference[oaicite:1]{index=1}

---

## Objectives

- Detect workers in construction site images.
- Identify Personal Protective Equipment (PPE).
- Determine whether each worker is PPE compliant.
- Demonstrate the use of object detection for workplace safety applications.

---

## Technologies Used

- Python
- Google Colab
- Jupyter Notebook
- YOLO11
- PyTorch
- Ultralytics
- Roboflow
- Kaggle

---

## Computer Vision Techniques

- Object Detection
- Deep Learning
- Bounding Box Detection
- Image Processing
- Real-Time Inference

---

## Dataset

The project proposal planned to use PPE datasets collected from:

- Roboflow Universe
- Kaggle PPE datasets

The datasets include labeled images containing:

- Person
- Hard Hat
- Safety Vest
- Safety Goggles

Data preparation included annotation verification, image resizing, data augmentation, and train/validation/test splitting. :contentReference[oaicite:2]{index=2}

---

## Proposed Workflow

The planned detection pipeline consists of:

1. Capture or upload an image.
2. Detect workers using YOLO11.
3. Detect required PPE.
4. Determine compliance for each worker.
5. Display detection results with bounding boxes and labels. :contentReference[oaicite:3]{index=3}

---

## Success Metrics

The project proposed evaluating the system using:

- Accuracy
- Precision
- Recall
- Inference Speed (Latency)

Target performance included achieving at least **90% overall accuracy** with inference times under **1 second per image**. :contentReference[oaicite:4]{index=4}

---

## Project Deliverables

This folder contains:

- `MD_Group_A_ITAI1378.pdf` — Midterm project presentation.

The complete implementation is available in the original team repository.

---

## Team Repository

https://github.com/zainahm713/ITAI-1378-Midterm_PPEComplianceChecker

---

## My Contribution

As a member of the project team, I participated in planning, researching, designing, and presenting the PPE Compliance Checker project. This project strengthened my understanding of how deep learning–based object detection can be applied to solve real-world workplace safety problems while collaborating within a development team.

---

## Skills Demonstrated

- Computer Vision
- Object Detection
- Deep Learning
- YOLO11
- PyTorch
- Image Processing
- Dataset Planning
- AI Project Design
- Technical Presentation
- GitHub Collaboration

---

## Key Learning Outcomes

Through this project, I learned how to design a computer vision solution for a real-world safety application. I gained experience selecting appropriate datasets, choosing an object detection model, defining evaluation metrics, planning a machine learning workflow, and communicating technical ideas through both GitHub documentation and a formal project presentation.
