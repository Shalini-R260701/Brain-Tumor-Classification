# 🧠 Deep Learning Based Brain Tumour Classification

This project presents a deep learning approach for classifying brain tumours using MRI images. It leverages a **Recursive Sigmoid Neural Network based on Multi-Scale Neural Segmentation (RSN2-MSNS)** and **Enhanced Deep Clustering U-Net (EDCU-net)** for precise segmentation and classification of tumour regions.

---

## 📌 Project Highlights

- **Model**: Recursive Sigmoid Neural Network (RSN2-MSNS)
- **Segmentation**: Enhanced Deep Clustering U-Net (EDCU-net)
- **Feature Extraction**: Convolution Deep Feature Spectral Similarity (CDFS²)
- **Dataset**: 1500 MRI images (1000 training, 500 testing)
- **Accuracy**: 97%
- **Sensitivity**: 96.4%
- **Specificity**: 95.2%
- **F1 Score**: 95.9%

---

## 🧠 Problem Statement

Brain tumours are life-threatening and require early and accurate diagnosis. Manual segmentation is time-consuming and error-prone. This project proposes an automated, deep learning-based solution to classify and segment brain tumours from MRI scans.

---

## 🛠️ Technologies Used

- Python
- TensorFlow & Keras
- Google Colab
- Anaconda
- Jupyter Notebook
- OpenCV, NumPy, Matplotlib
---

## 🧪 Methodology

1. **Data Preprocessing**  
   - Noise removal using Stretched Weighted Median Filtering (SWMF)

2. **Image Segmentation**  
   - EDCU-net for clustering and boundary detection

3. **Feature Extraction**  
   - CDFS² for extracting spectral similarity features
4. **Classification**  
   - RSN2-MSNS for final tumour classification

---

## 📊 Results

| Metric        | Value     |
|---------------|-----------|
| Accuracy      | 97.0%     |
| Sensitivity   | 96.4%     |
| Specificity   | 95.2%     |
| F1 Score      | 95.9%     |

---


