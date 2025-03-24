
### **YOLOv8 Object Detection - Image Inference with Ultralytics** 🚀  

![YOLOv8 Detection](https://github.com/muhammadrizwan11/YOLOv8-Object-Detection---Image-Inference-with-Ultralytics/blob/main/zidane%20(2).jpg)  

## **📌 Overview**  
This repository demonstrates **object detection** using **YOLOv8** by Ultralytics. It allows you to perform real-time inference on images using a pre-trained YOLO model with just a few lines of code.  

## **⚡ Features**  
✅ Real-time object detection  
✅ Uses **YOLOv8n** (lightweight and fast)  
✅ Supports image inference from a URL or local files  
✅ Simple and easy-to-run Python script  

## **📂 Repository Structure**  
```
📁 YOLOv8-Object-Detection
│── 📜 yolov11n.pt      # Pre-trained YOLOv8 model
│── 📜 detect.py             # Python script for object detection
│── 📜 requirements.txt      # List of dependencies
│── 📜 README.md             # Project documentation
```

## **🛠 Installation**  
1️⃣ Clone this repository:  
```bash
git clone https://github.com/muhammadrizwan11/YOLOv8-Object-Detection---Image-Inference-with-Ultralytics.git
cd YOLOv8-Object-Detection---Image-Inference-with-Ultralytics
```
2️⃣ Install dependencies:  
```bash
pip install -r requirements.txt
```
3️⃣ Run object detection:  
```bash
YOLO11 Detection.ipynb
```

## **📸 Example Usage**  
You can perform inference on an image using YOLOv8 with:  
```python
from ultralytics import YOLO  

model = YOLO("yolov8n.pt")  
results = model("https://cdn.pixabay.com/photo/2017/03/28/12/11/chairs-2181960_960_720.jpg", save=True)
```



## **📌 References**  
- [Ultralytics YOLOv8 Documentation](https://docs.ultralytics.com/)  
- [YOLOv8 GitHub Repository](https://github.com/ultralytics/ultralytics)  

## **⭐ Like This Project?**  
Give this repo a ⭐ if you find it useful! 🚀  

---

