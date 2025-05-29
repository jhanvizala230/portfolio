---
layout: default
title: "RoverNet - Visual QA Assistant"
description: "AI assistant combining computer vision and natural language processing"
github_url: https://github.com/jhanvizala230/Rovernet-chatbot
---

# RoverNet  
**Visual Question Answering with Detectron2 + LLM Integration**

---

## Project Overview
RoverNet merges real-time computer vision with natural language processing to:
- Analyze images using Detectron2 (object/instance detection)
- Answer questions about visual content using LLaMA 3.2/LLaVA
- Provide intuitive interaction via Streamlit interface

---

## Key Features
### Advanced Visual Understanding
- Object detection with pretrained/custom Detectron2 models
- Scene graph generation
- High accuracy on COCO Dataset benchmarks

### Natural Language Interface
- Context-aware question answering
- Multi-turn conversation support
- Explainable AI responses

### System Architecture
- CUDA-accelerated PyTorch backend
- FastAPI service layer
- Docker-ready deployment

---

## Technology Stack
• Computer Vision: Detectron2, OpenCV
• Language Models: Ollama (LLaMA 3.2, LLaVA)
• Framework: PyTorch, FastAPI, Streamlit
• Hardware: CUDA 12.8, NVIDIA GPUs


---

## Demonstration

**Home Interface**  
![Home Screen](/assets/images/rovernet/initial_screen.png{:width="400" height="300" }
 
<!-- *Streamlit UI with image upload capability* -->

**Analysis Results**  
![Image Analysis](/assets/images/rovernet/results.png)  
<!-- *Object detection overlay with confidence scores* -->

**Q&A Example**  
![Chat Example](/assets/images/rovernet/results2.png)  
<!-- *Natural language interaction about scene content* -->

---

## Project Links
[![GitHub Repository](https://img.shields.io/badge/View_on_GitHub-181717?style=flat&logo=github)]({{ page.github_url }})

[← Back to Portfolio](/portfolio)