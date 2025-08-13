# AI-based-Garbage-detection-using-roboflow
Deep learning-based garbage detection model trained with Roboflow dataset and implemented in PyTorch
# AI-Based Garbage Detection using Roboflow & PyTorch

##  Overview
This project implements a deep learning model for detecting garbage objects in images using a dataset prepared in **Roboflow**. The model is trained in **PyTorch** and can be deployed for real-time garbage detection.

---

##  Tools & Technologies
- **Framework:** PyTorch  
- **Dataset:** Custom garbage detection dataset from Roboflow  
- **Language:** Python  
- **Model:** YOLOv5 / CNN (specify what you used)  
- **Hardware:** GPU-enabled system for training  

---

##  Features
- Detects garbage items from images or live video stream  
- Trained on custom annotated dataset from Roboflow  
- High accuracy with minimal false positives  

---

## Files in this Repository
- `garbage_detection.py` → Main script for detection  
- `garbage_model.pt` → Trained PyTorch model (link if >100MB)  
- `sample_output.jpg` → Example detection image  

---

##  How to Run
```bash
# Install dependencies
pip install torch torchvision opencv-python

# Run detection
python garbage_detection.py --source test_image.jpg
