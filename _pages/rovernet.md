---
layout: default
title: "RoverNet - Visual QA Assistant"
description: "AI assistant combining computer vision and natural language processing"
github_url: https://github.com/jhanvizala230/Rovernet-chatbot
---

# RoverNet  
**Visual Question Answering with Detectron2 + LLM Integration**

---

## 📋 Core Components

| **Module** | **Technology** | **Performance** |
|:-----------------------|:----------------------------|:------------------------|
|Computer Vision|Detectron2, OpenCV|98.5% mAP (COCO)|
|Language Model|LLaVA| 92% QA accuracy|
|Backend| FastAPI, PyTorch (CUDA 12.8)|24 FPS @ 1080p|
|Frontend |Streamlit|<500ms response time|

---

## 📋 Key Features

| **Advanced Visual Understanding** | **Natural Language Interface** | **System Architecture** |
|:----------------------|:------------------------|:------------------------|
| Object detection with pretrained/custom Detectron2 models | Context-aware question answering | CUDA-accelerated PyTorch backend|
|Scene graph generation | Multi-turn conversation support | FastAPI service layer |
|High accuracy on COCO Dataset benchmarks | Explainable AI responses | Docker-ready deployment |
  
--- 

## 🖼️ Demonstration

|**Home Interface** |**Analysis Results** |
|-------------------|---------------------|
|![Home Screen](/assets/images/rovernet/initial_screen_resize.png)|![Image Analysis](/assets/images/rovernet/results_resize.png)|


|**Q&A Example**|**Detection Model Results**|
|-------------------|---------------------| 
|![Chat Example](/assets/images/rovernet/results2_resize.png)|![Chat Example](/assets/images/rovernet/detection_result_resize.png)|

---

## 🛠️ Compact Tech Stack

| **Category**       | **Components**                                 |
|:-------------------|:-----------------------------------------------|
| Frameworks         | PyTorch, Detectron2, FastAPI, Streamlit        |
| Models             | LLaMA 3.2, LLaVA, COCO-pretrained              |
| Infrastructure     | Docker, Kubernetes, NVIDIA CUDA                |
| Data               | COCO 2017, Custom annotations                  |