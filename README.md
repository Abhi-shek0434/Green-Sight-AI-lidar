# 🌱 Green Sight – Smart Vegetation Monitoring using AI

## 📌 Project Overview
Green Sight is an AI-based vegetation monitoring system that analyzes aerial or satellite
images to detect vegetation coverage and classify forest or crop types.
The project uses image processing and machine learning techniques to support
environmental monitoring, agriculture analysis, and smart land management.

This project focuses on:
- Forest coverage estimation
- Forest type classification
- Crop type identification based on visual features

---

## 🧠 Key Features
- Vegetation detection using HSV color segmentation
- Forest coverage percentage calculation
- Forest type classification (Tropical, Temperate, Dry, Plantation, etc.)
- Crop type identification (Rice, Ragi, Tobacco, Tea, etc.)
- Feature extraction using color, texture, and density analysis
- Visual outputs including masks, overlays, and charts

---

## 🛠️ Technologies Used
- Python
- OpenCV
- NumPy
- Matplotlib
- Scikit-image
- Scikit-learn
- Google Colab (for execution)

---

## 🔍 Methodology
1. Input image is uploaded (satellite / aerial / field image)
2. Image converted to HSV color space
3. Green vegetation regions segmented using thresholding
4. Morphological operations applied for noise removal
5. Vegetation coverage percentage calculated
6. Features extracted:
   - Color statistics (RGB, HSV, LAB)
   - Texture features (GLCM, edges)
   - Density and color variety
7. Rule-based + ML-assisted classification performed
8. Results visualized using charts and overlays
