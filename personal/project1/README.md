# RoverNet Chatbot – AI-Powered Visual Assistant

RoverNet is a cutting-edge AI assistant that merges real-time computer vision with natural language processing. It uses Detectron2 for object and instance detection and integrates with Ollama-powered LLMs (like LLaMA 3.2 or LLaVA) to answer natural language questions about images. The chatbot is build using streamlitt

## Key Features:
🔍 Detects and labels objects in images using pretrained or custom models

💬 Answers visual questions about scenes, combining CV and LLMs

⚡ Built with CUDA-accelerated PyTorch and optimized for Windows systems

🌐 Modular backend that can be extended to robotics, surveillance, and geospatial analysis

## 🛠️ Tech Stack
- Detectron2 (Instance Segmentation)
- Ollama (LLMs like LLaMA 3.2, LLaVA)
- Python, PyTorch, FastAPI, Streamlit (optional)
- CUDA 12.8, OpenCV, COCO Dataset(custom dataset)

## 📸 Screenshots

Home Screen
![Demo](../images/initial_screen.png)

Chatbot with uploaded image, detected objects on right and chatbot with answers based on detected surface
![Demo](../images/results.png)
![Demo](../images/results2.png)

The model deteted output
![Demo](../images/detection_result.png)


## 🔗 Links
- [Code Repository](https://github.com/jhanvizala230/Rovernet-chatbot)
