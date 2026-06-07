# YOLO
# 🚀 SmartVisionSearch-YOLO11
SmartVisionSearch-YOLO11 is a computer vision search engine that leverages YOLO11 for real-time object detection and Streamlit for an interactive web interface. Upload an image, instantly identify objects from the COCO dataset (80 classes), and view bounding boxes with predictions in real time.

# 📘 1. Project Title
SmartVisionSearch-YOLO11 – Real-time Object Detection & Search Engine

# 📖 2. Abstract / Introduction
This project combines YOLO11 with Streamlit to create a lightweight, interactive search engine for object detection. It enables users to upload images, detect objects from the COCO dataset, and visualize results with bounding boxes. The modular design makes it easy to extend and customize for research or production use.

# 📊 3. Dataset & YOLO Model Details (COCO)
• Dataset: COCO (Common Objects in Context)

• Classes Supported: 80 object categories (e.g., person, car, dog, chair, etc.)

• Model: YOLO11 – optimized for real-time detection with high accuracy

• Detection Output: Bounding boxes, confidence scores, and class labels

# ⚙️ 4. Environment Setup
## Create a new Conda environment and install dependencies:
```
conda create -n smartvision_env python=3.11 -y
conda activate smartvision_env
```
#  💻 5. GPU Installation Steps or CPU Installation Steps
## GPU Setup (Recommended)
```
conda install pytorch==2.5.1 torchvision==0.20.1 pytorch-cuda=12.4 -c pytorch -c nvidia
pip install -r requirements.txt
```
## CPU Setup
```
conda install pytorch==2.5.1 torchvision==0.20.1 cpuonly -c pytorch
pip install -r requirements.txt
```
# 🖥️ 6. How to Run in VS Code using Conda
## Open VS Code
Select the Conda environment: • Press Ctrl+Shift+P → Search for Python: Select Interpreter → Choose smartvision_env
Run the app in the integrated terminal:
```
streamlit run app.py
```
# 🌐 7. How to Deploy using Streamlit
## Simply run:
```
streamlit run app.py
```
This will launch a local server and open the app in your browser. You can upload images, select COCO categories, and view detection results interactively.

# 📂 8. Output Screenshots (UI + detection + VS Code terminal)
WhatsApp Image 2025-11-22 at 09 11 37 WhatsApp Image 2025-11-22 at 09 11 37 (1) WhatsApp Image 2025-11-22 at 09 11 38 WhatsApp Image 2025-11-22 at 09 11 38 (1) WhatsApp Image 2025-11-22 at 09 11 38 (2)

# 🔧 9. Enhancements / Innovations Added
• Modular architecture for easy extension

• Support for both CPU and GPU environments

• Real-time detection with bounding boxes and confidence scores

• Streamlit-based interactive search interface

• Configurable thresholds and parameters via config.py

# 🏆 10. Results & Conclusion
• Successfully detects and visualizes objects from the COCO dataset in real time

• Provides an intuitive interface for uploading and searching images

• Demonstrates the power of combining YOLO11 with Streamlit for rapid prototyping and deployment

• Can be extended for custom datasets, advanced search features, or production-ready applications

# 📦 Dependencies
• torch

• torchvision

• streamlit

• Other required packages listed in requirements.txt
