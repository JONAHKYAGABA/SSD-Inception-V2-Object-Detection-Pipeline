# 🎯 SSD Inception V2 Object Detection Pipeline

This project demonstrates how to use a pre-trained **SSD Inception V2 object detection model** with TensorFlow to perform real-time or static image object detection. It uses OpenCV for image I/O and visualization and TensorFlow’s object detection API to load the frozen inference graph and run predictions.

---

## 📦 Features

- 🧠 Loads TensorFlow SSD Inception V2 pre-trained model from `.pb` file
- 📷 Supports image input and displays detection results
- 📏 Draws bounding boxes and labels for detected classes
- ✅ Uses COCO label mapping for human-readable class names
- 💡 GPU-compatible inference if TensorFlow-GPU is installed

---

## 🧰 Dependencies

Install required packages:

```bash
pip install tensorflow opencv-python numpy
