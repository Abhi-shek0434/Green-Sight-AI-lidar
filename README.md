# 🌱 Green Sight – Smart Vegetation Monitoring using AI

## 📌 Project Overview
Green Sight is an AI-based vegetation monitoring project designed to analyze aerial, satellite,
or ground images to detect vegetation coverage and classify forest and crop types.
The system uses image processing and machine learning techniques to support
environmental monitoring, agriculture analysis, and smart land management applications.

This project demonstrates practical implementation of computer vision concepts
using Python and open-source libraries.

---

## 🎯 Objectives
- Detect vegetation areas from input images
- Calculate vegetation / forest coverage percentage
- Classify forest types based on visual features
- Identify crop types using color and texture analysis
- Visualize results using masks, overlays, and charts

---

## 🧠 Key Features
- HSV-based vegetation (green region) detection
- Forest coverage estimation
- Forest type classification (Tropical, Temperate, Dry, Plantation, etc.)
- Crop type classification (Rice, Ragi, Tobacco, Tea, etc.)
- Feature extraction using:
  - Color statistics (RGB, HSV, LAB)
  - Texture features (GLCM, edge density)
  - Vegetation density and color variety
- Clear graphical visualizations for analysis

---

## 🛠️ Technologies Used
- Python
- OpenCV
- NumPy
- Matplotlib
- Scikit-image
- Scikit-learn
- Google Colab

---

## 🔍 Methodology
1. Input image is uploaded (satellite / aerial / field image)
2. Image is converted to HSV color space
3. Vegetation regions are segmented using green color thresholds
4. Morphological operations are applied to remove noise
5. Vegetation coverage percentage is calculated
6. Features are extracted from vegetation regions
7. Rule-based and ML-assisted classification is performed
8. Results are visualized using plots and image overlays



