# 🧠 Biomedical Image Analysis – MRI Segmentation

## 📌 Overview
This project focuses on analyzing cardiac MRI images and applying classical image processing techniques to segment and extract the left ventricle region.  
The workflow includes image loading, visualization, filtering, morphological operations, segmentation, and region extraction.

---

## 🎯 Objective
To demonstrate how basic image processing techniques can be used in biomedical imaging to identify and extract meaningful anatomical structures from MRI scans.

---

## 📊 Dataset
The dataset used in this project is the Sunnybrook Cardiac MRI dataset:

🔗 https://www.kaggle.com/datasets/salikhussaini49/sunnybrook-cardiac-mri

A sample MRI image (`SCD2001_MR_117.dcm`) was used for processing.

---

## 🛠️ Technologies Used
- Python 🐍
- NumPy
- SciPy
- Matplotlib
- ImageIO

---

## ⚙️ Project Pipeline

### 1. Image Loading & Visualization
- Loaded DICOM MRI image
- Displayed grayscale intensity representation

### 2. Image Analysis
- Checked image properties (shape, dtype, intensity range)
- Generated histogram of pixel intensities

### 3. Image Transformations
- Applied rotation and shifting to test spatial transformations

### 4. Segmentation
- Used intensity-based thresholding
- Created binary masks for region extraction

### 5. Morphological Operations
- Applied dilation and closing to improve segmentation quality

### 6. Edge Detection
- Used convolution filters to detect vertical edges

### 7. Region Labeling
- Applied connected component analysis
- Identified multiple anatomical regions

### 8. Left Ventricle Extraction
- Selected specific labeled region
- Extracted region of interest using bounding box

---

## 📷 Results
- Successfully segmented cardiac structures from MRI images
- Extracted left ventricle region using connected components
- Improved mask quality using morphological operations

*(Add output images here in your GitHub repo for better presentation)*

---

## 📌 Key Learnings
- Basics of medical image processing
- Importance of thresholding and morphological operations
- Connected component labeling for region detection
- Working with real MRI datasets

---

## 🚀 Future Improvements
- Apply deep learning (CNN / U-Net) for more accurate segmentation
- Automate ventricle detection without manual selection
- Improve robustness across different MRI scans

---

## 👩‍💻 Author
Faten Safi  
Data Science and AI Student  
Interest: AI, Data Science, and Biomedical Image Processing

---

## 📄 Note
This project was developed for educational purposes as part of data science learning journey.
