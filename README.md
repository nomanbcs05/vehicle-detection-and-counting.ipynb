# vehicle-detection-and-counting.ipynb
This project uses YOLOv8 for real-time vehicle detection and counting from traffic videos or live feeds. It accurately identifies various vehicle types in diverse conditions, enabling efficient traffic management and smart city applications through fast, automated analysis.
Here’s a **complete, professional `README.md`** for your project **`vehicle-detection-and-counting.ipynb`**, ready to upload to GitHub 🚗📊

---

# 🚘 Vehicle Detection and Counting using YOLOv8

## 📘 Overview

This project implements **real-time vehicle detection and counting** using the **YOLOv8** deep learning model. It processes traffic surveillance videos or live camera feeds to automatically detect and classify vehicles such as **cars, buses, trucks, and motorcycles**.

By leveraging YOLOv8’s **speed** and **accuracy**, the system operates efficiently in various lighting, weather, and traffic conditions. It provides a foundation for **smart traffic monitoring**, **urban planning**, and **intelligent transportation systems (ITS)**.

---

## 📊 Dataset

* **Source:** Traffic monitoring datasets from [Kaggle](https://www.kaggle.com/) or custom video feeds.
* **Format:** YOLO annotation format (images + labels).
* **Classes:** Car, Bus, Truck, Motorcycle, and other vehicle types.

---

## 🧠 Model Details

* **Architecture:** YOLOv8 (Ultralytics)
* **Framework:** PyTorch
* **Image Size:** 640 × 640
* **Epochs:** 100
* **Training Environment:** GPU recommended (Google Colab / Kaggle Notebooks)

---

## ⚙️ How to Run

1. **Clone the repository:**

   ```bash
   git clone https://github.com/<your-username>/Vehicle-Detection-and-Counting.git
   cd Vehicle-Detection-and-Counting
   ```

2. **Install dependencies:**

   ```bash
   pip install ultralytics opencv-python torch
   ```

3. **Run the notebook:**
   Open `vehicle-detection-and-counting.ipynb` in Jupyter or Google Colab and execute all cells.

4. **View results:**
   Output videos and images with bounding boxes and vehicle counts will be saved in the `runs/detect/` directory.

---

## 📈 Results

* Real-time detection at >30 FPS (depending on hardware).
* High accuracy across multiple vehicle classes.
* Suitable for both static cameras and aerial drone footage.

---

## 🌍 Applications

* 🚦 Traffic management and monitoring
* 🏙️ Smart city data analytics
* 🧭 Urban planning and transport optimization
* 🚗 Automated toll and parking systems

