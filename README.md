# 🌾 Golden64 Rice Field Dataset

## 📌 Overview

The Golden64 Rice Field Dataset is a multimodal agricultural dataset designed for crop analysis and field condition prediction. It includes field images, IoT sensor data, laboratory measurements, and crop features.

---

## 📂 Dataset Structure

```
Dataset/
├── images/                # Field images
│   ├── img_001.jpg
│   ├── img_002.jpg
│   └── ...
│
├── sensor_data.csv        # IoT sensor data
├── lab_data.csv           # Laboratory measurements
├── crop_features.csv      # Crop-related features
├── metadata.json          # Dataset metadata
└── README.md              # Documentation
```

---

## 📊 Data Description

### 🖼️ Images

* Captured using onboard camera modules
* Represents Golden64 rice crop fields
* Used for visual analysis and model training

---

### 🌡️ Sensor Data (`sensor_data.csv`)

Contains IoT sensor measurements:

* Temperature
* Humidity
* Soil moisture
* Light intensity
* Rain status
* GPS coordinates (latitude, longitude, altitude)

---

### 🧪 Lab Data (`lab_data.csv`)

Contains laboratory measurements:

* Soil pH value
* pH classification

---

### 🌾 Crop Features (`crop_features.csv`)

Includes crop-specific attributes:

* Crop height
* Crop spacing/distance

---

## ⚙️ Usage

### 📥 Download

Clone or download this dataset:

```
git clone https://github.com/your-username/golden64-dataset.git
```

Or download ZIP from repository.

---

### 🧠 Applications

* Crop health prediction
* Anomaly detection in agriculture
* Multimodal machine learning (image + sensor + lab data)
* Precision farming research

---

## 📏 Preprocessing

* Images may be resized to 128×128 for model training
* Data normalization recommended before training

---

## 📜 License

This dataset is intended for academic and research purposes.

---

## 👤 Author

Your Name
Your Institution

---

## 📅 Version

v1.0 (2026)
