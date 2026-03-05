# FPGA-Based Edge Detection for Brain Tumor Analysis

## Overview
Medical image analysis plays a crucial role in the early detection of brain tumors. However, identifying tumor boundaries in MRI images is difficult due to noise, low contrast, and intensity variations.  

This project explores an adaptive edge detection system designed for **FPGA-based implementation** to improve the detection of tumor boundaries in MRI images. The system applies image preprocessing techniques followed by multiple edge detection algorithms to enhance the visibility of tumor regions.

---

## Problem Statement
MRI images often contain noise and unclear boundaries, which makes it difficult to accurately identify tumor regions. Traditional image processing techniques may fail to highlight edges clearly in such conditions.

The objective of this project is to design an **efficient edge detection system** that enhances tumor boundaries and can be implemented on FPGA hardware for real-time medical image processing.

---

## Proposed Approach
The proposed system follows a multi-stage image processing pipeline:

1. **Image Preprocessing**
   - Contrast enhancement using CLAHE (Contrast Limited Adaptive Histogram Equalization)

2. **Noise Reduction**
   - Bilateral filtering to preserve edges while removing noise

3. **Edge Detection Algorithms**
   - Sobel Operator
   - Prewitt Operator
   - Canny Edge Detection

4. **Adaptive Operator Selection**
   - The system analyzes image characteristics and selects the most suitable edge detection operator.

---

## System Architecture
The system consists of the following main modules:

- Image preprocessing module  
- Line buffer architecture for image data handling  
- Edge detection modules (Sobel, Prewitt, Canny)  
- Thresholding and edge enhancement module  
- Adaptive operator selection logic  

The architecture is designed for **FPGA implementation to support parallel processing and real-time performance**.

---

## Technologies Used
- Python (for image processing testing and algorithm validation)
- FPGA architecture design
- Digital image processing techniques
- MRI image datasets

---

## Applications
- Medical image analysis
- Brain tumor detection
- Real-time healthcare imaging systems
- Edge detection for biomedical images

---

## Future Scope
- Full hardware implementation on FPGA board
- Integration with tumor segmentation algorithms
- AI-assisted medical diagnostic systems
- Real-time medical image processing pipelines

---

## Project Report
The detailed project report explaining the methodology, architecture, and analysis can be found in the repository.
