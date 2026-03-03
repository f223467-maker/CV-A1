# Assignment 1 – Introduction to Computer Vision

## Student Information
Name: Muhammad Zohaib Saleem  
Roll Number: 22F-3467  
Course: Introduction to Computer Vision  
Department: Electrical Engineering  

---

## 📌 Project Overview

This assignment focuses on implementing fundamental computer vision algorithms from scratch using NumPy and Matplotlib.

The following major topics are covered:

1. Image Enhancement (Histogram Equalization, Contrast Stretching, Gamma Correction)
2. 2D Convolution and Filtering
3. Edge Detection (Gradients and Canny Edge Detector)

All core algorithms are implemented manually without using built-in OpenCV functions. OpenCV is used only for comparison purposes.

---

## 🛠 Environment Setup

### Step 1: Create Virtual Environment

python -m venv venv

### Step 2: Activate Environment

Windows:
venv\Scripts\activate

Mac/Linux:
source venv/bin/activate

### Step 3: Install Required Libraries

pip install -r requirements.txt

---

## ▶ How to Run the Notebook

1. Open Jupyter Notebook or Google Colab.
2. Open the file:

Zohaib_22F-3467_A1.ipynb

3. Run all cells sequentially.
4. Make sure test images are inside the `test_images` folder.

---

## 🖼 Test Images

The `test_images` folder contains:

- Low contrast images
- Dark/underexposed images
- Images used for edge detection experiments

All images are grayscale unless otherwise specified.

---

## 📊 Implementation Details

- Histogram Equalization implemented from scratch using CDF.
- Contrast Stretching implemented using min-max normalization.
- Gamma Correction implemented using power-law transformation.
- 2D Convolution implemented manually using nested loops.
- Gaussian Kernel generated using 2D Gaussian formula.
- Sobel, Prewitt, Roberts operators implemented manually.
- Complete Canny Edge Detector implemented step-by-step.

---

## ⚠ Assumptions

- Images are grayscale for processing.
- Pixel values range from 0–255.
- NumPy is used for all mathematical operations.
- OpenCV functions are used only for comparison, not core implementation.

---

## 📁 Repository Structure

Computer_Vision_Basics/
├── README.md
├── requirements.txt
├── Zohaib_22F-3467_A1.ipynb
├── test_images/
└── report.pdf

---

## 📌 Notes

- Code follows modular structure.
- Functions are separated for reusability.
- Execution time comparisons are included.
- All results and analysis are provided in the report.
