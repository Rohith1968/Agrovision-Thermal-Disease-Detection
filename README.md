# 🌱 Agrovision: Early Detection of Chili Plant Diseases Using Deep Learning & Thermal Imaging

Agrovision is a final-year B.Tech project developed to detect **chili plant diseases** such as **Early Blight** and **Anthracnose** using **thermal imaging** and advanced **deep learning** techniques. Our approach captures daily thermal images and uses CNN + LSTM hybrid models to identify disease progression **before visible symptoms appear**, enabling **proactive intervention** in agriculture.

---

## 📘 Project Summary

🌿 Traditional disease detection methods rely on visible symptoms — by then, the disease has already impacted yield.

🚀 Agrovision solves this by using **thermal cameras** and a **hybrid deep learning pipeline** to:
- Monitor chili leaf temperature daily
- Detect disease patterns early
- Forecast future risk using time-series modeling

Our system achieves over **95% accuracy**, providing farmers and researchers with a **non-invasive, real-time early warning system**.

---

## 🧪 Problem Statement

> "Can we detect plant disease *before* the plant looks sick?"

Yes — by measuring **thermal anomalies** caused by physiological stress **days before symptoms are visible**. This project proves that concept using Fluke Ti480 PRO cameras and deep learning.

---

## 🔍 Key Features

- 🌡️ Captures daily thermal patterns of chili leaves
- 📊 Trains on a labeled dataset: Healthy, Early Blight, Anthracnose
- 🧠 Uses 5 DL models: VGG19, DenseNet201, MobileNetV2, InceptionResNetV2, CNN+LSTM
- 📈 CNN+LSTM achieves 95.8% accuracy and AUC-ROC of 0.96
- 🧠 Predicts risk trends across 9-day windows
- 📄 Includes experimental results, code, and final academic report

---

## 🧠 Deep Learning Models Used

| Model              | Description                                  |
|-------------------|----------------------------------------------|
| VGG19             | Deep CNN with fine-grained image features    |
| DenseNet201       | Feature reuse via dense connections          |
| MobileNetV2       | Lightweight, mobile-optimized CNN            |
| InceptionResNetV2 | Residual + multiscale image understanding    |
| CNN + LSTM        | Spatial + Temporal analysis (time-series)    |

---

## 🗂️ Folder Structure

```
Agrovision-Thermal-Disease-Detection/
├── notebooks/               # Jupyter notebooks for data, training, and evaluation
│   ├── data_preprocessing.ipynb
│   ├── model_training.ipynb
│   └── results_visualization.ipynb
├── models/                  # Saved Keras/TF model files (.h5)
├── results/                 # ROC curves, accuracy/loss graphs, and risk trend plots
├── dataset/                 # Thermal images and labels (not public)
├── FINAL_REPORT.pdf         # Full academic documentation
├── requirements.txt         # Python dependencies
└── README.md                # This file
```

---

## 🛠️ How to Run Locally

1. **Clone this repository**
```bash
git clone https://github.com/Rohith1968/Agrovision-Thermal-Disease-Detection.git
cd Agrovision-Thermal-Disease-Detection
```

2. **Install required packages**
```bash
pip install -r requirements.txt
```

3. **Launch Jupyter Notebook**
```bash
jupyter notebook
```

4. Open and run the following notebooks in order:
   - `notebooks/data_preprocessing.ipynb`
   - `notebooks/model_training.ipynb`
   - `notebooks/results_visualization.ipynb`

---

## 🖼️ Sample Results

- ✅ CNN+LSTM achieved **95.8% accuracy** in multi-class classification
- 📈 AUC-ROC: 0.96 for Early Blight vs Healthy
- 🔥 Thermal patterns revealed stress **4–6 days earlier** than visible signs
- 🧪 Daily temperature graphs successfully predicted disease onset

> All results and visuals are shown in `results/` and detailed in `FINAL_REPORT.pdf`.

---

## 📄 Report

📘 [FINAL_REPORT.pdf](./FINAL_REPORT.pdf)  
Includes:  
- Abstract, Motivation, Literature Survey  
- Dataset Collection Process  
- Model Architectures  
- ROC Curves, Graphs, Tables  
- Limitations & Future Work

---

> **Agrovision** – Precision Agriculture meets Deep Learning.
