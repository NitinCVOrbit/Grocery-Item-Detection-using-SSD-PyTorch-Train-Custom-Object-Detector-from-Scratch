# 🛒 Grocery Items Object Detection using SSD (PyTorch)

This project demonstrates how to train a **custom object detection model** to detect grocery products using **SSD (Single Shot Detector) with a VGG16 backbone** in PyTorch.

We build a complete end-to-end pipeline from dataset download to training, visualization, and inference.

---

## 📌 Project Overview

The goal of this project is to detect multiple grocery store items such as:

- Biscuits  
- Chips  
- Chocolate  
- Soft Drinks  
- Soaps  
- Tea Packs  
- Tooth Items  
- And many more...

We use a **pretrained SSD300 VGG16 model** and fine-tune it on a **custom dataset exported from Roboflow**.

---

## 🚀 Features

✅ Dataset download using **Roboflow API**  
✅ Supports **YOLO format annotations**  
✅ Custom **PyTorch Dataset class**  
✅ Modified **SSD Classification Head** for custom classes  
✅ Training loop with:
- SGD Optimizer  
- Learning Rate Scheduler  

✅ Bounding box visualization  
✅ Training loss graph plotting  
✅ Model saving & loading  
✅ Inference on test images  

---

## 🧠 Tech Stack

- Python  
- PyTorch  
- Torchvision  
- OpenCV  
- Matplotlib  
- Roboflow  
