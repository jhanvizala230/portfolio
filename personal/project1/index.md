---
layout: page
title: "RoverNet - Visual QA Assistant"
description: "AI assistant combining computer vision and natural language processing"
---

# RoverNet  
*Visual Question Answering with Detectron2 + LLM Integration*

## Project Description

RoverNet is a cutting-edge AI assistant that merges real-time computer vision with natural language processing. The system:

- Processes images through Detectron2 for object and instance detection
- Generates comprehensive scene understanding using Ollama-powered LLMs (LLaMA 3.2/LLaVA)
- Provides natural language answers to visual questions through a Streamlit interface

## Key Features

**Advanced Visual Understanding**  
Detects and labels objects in images using pretrained or custom Detectron2 models with high accuracy

**Natural Language Interface**  
Answers complex questions about visual scenes by combining CV detection with LLM reasoning

**High Performance**  
Built with CUDA-accelerated PyTorch and optimized for Windows systems

**Modular Architecture**  
Extensible backend suitable for robotics, surveillance, and geospatial applications

## Tech Stack

- Detectron2 (Instance Segmentation)
- Ollama (LLMs like LLaMA 3.2, LLaVA)
- Python, PyTorch, FastAPI, Streamlit
- CUDA 12.8, OpenCV, COCO Dataset (custom dataset)

## Demonstration

![Home Screen](/personal/project1/images/initial_screen.png)  
*Home Screen Interface*

![Image Analysis](/personal/project1/images/results.png)  
*Image analysis with object detection overlay*

![Chat Example](/personal/project1/images/results2.png)  
*Natural language Q&A about the scene*

![Detection Output](/personal/project1/images/detection_result.png)  
*Detailed object detection results*

## Project Links

[View on GitHub](https://github.com/jhanvizala230/Rovernet-chatbot)