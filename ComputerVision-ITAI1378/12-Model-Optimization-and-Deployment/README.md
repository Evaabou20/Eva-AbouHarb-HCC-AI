# Model Optimization and Deployment

## Overview

This project was completed as part of **ITAI 1378 – Computer Vision** at Houston City College. The goal of this lab was to learn how to deploy computer vision models as web APIs so they can be accessed by other applications instead of being used only as local Python scripts.

The lab demonstrates two deployment examples. The first uses a pre-trained Vision Transformer (ViT) model from Hugging Face for image classification, while the second deploys a YOLOv8 object detection model using FastAPI. Both APIs were tested locally by sending image requests and receiving prediction results in JSON format.

---

## Learning Objectives

- Explain the importance of model deployment.
- Understand how APIs enable communication between machine learning models and other applications.
- Build a REST API using FastAPI.
- Deploy a pre-trained computer vision model as a local API.
- Create an object detection API using YOLOv8.
- Test API endpoints using HTTP requests.
- Understand the role of MLOps in deploying and maintaining AI models.

---

## Technologies Used

- Python
- Google Colab
- FastAPI
- Uvicorn
- Hugging Face Transformers
- Vision Transformer (ViT)
- Ultralytics YOLOv8
- PyTorch
- Pillow (PIL)
- Requests

---

## Project Files

- **L11_AbouHarb_Eva_ITAI1378.ipynb** – Completed notebook containing all code, outputs, and written responses.
- **L11_AbouHarb_Eva_ITAI1378.pdf** – PDF version of the completed notebook.

---

## Project Summary

### Part 1 – Image Classification API

A FastAPI application was created using a pre-trained Vision Transformer model (`google/vit-base-patch16-224`) from Hugging Face. The API accepts an uploaded image and returns image classification predictions with confidence scores.

The test image was successfully classified as a **Beagle** with the highest confidence score.

### Part 2 – YOLO Object Detection API

A second FastAPI application was developed using the **YOLOv8 Nano** (`yolov8n.pt`) model from Ultralytics. The API accepts an uploaded image, performs object detection, and returns:

- Detected object labels
- Confidence scores
- Bounding box coordinates
- JSON-formatted results

The API successfully detected a **dog** with approximately **90.7% confidence**.

---

## Skills Demonstrated

- Computer Vision
- Model Deployment
- API Development
- FastAPI
- Object Detection
- Image Classification
- YOLOv8
- REST APIs
- JSON Data Handling
- Model Inference
- MLOps Concepts
- Technical Documentation

---

## Learning Outcomes

Through this lab, I learned how trained computer vision models can be deployed as APIs, making them accessible to other software applications. I gained practical experience building and testing FastAPI services, integrating pre-trained deep learning models, and returning prediction results through HTTP requests. This project also strengthened my understanding of model deployment, API development, and the importance of MLOps for maintaining AI systems in production environments.

---

## Course Information

**Course:** ITAI 1378 – Computer Vision  
**Institution:** Houston City College  
**Term:** Summer 2026


