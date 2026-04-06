# 🖼️ Image Processing – Computer Vision Tasks

Implementation of core image processing algorithms from scratch using Python and Jupyter Notebooks.

## 📚 Tasks Overview

### Task 1 – Image Binarization
- Implemented **Global Adaptive Thresholding** using iterative epsilon-based convergence
- Implemented **Local Adaptive Thresholding** using neighbourhood window (Ww × Hw)

### Task 2 – Histogram of Oriented Gradients (HOG)
- Computed **HOG feature descriptors** for grayscale images
- Estimated **image similarity** using cosine similarity between HOG histograms

### Task 3 – Sliding Window Object Detection
- Detected object occurrences across images using the **sliding window technique**
- Combined HOG descriptors for template matching and object localization

## 🛠️ Tech Stack
- Python
- NumPy
- Matplotlib
- Jupyter Notebook

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/bludvista/image-processing-cv.git
   ```
2. Install dependencies:
   ```bash
   pip install numpy matplotlib jupyter
   ```
3. Open any notebook:
   ```bash
   jupyter notebook
   ```

## 📄 Task Description
Full task specification available in `image.processing.task.pdf`

## ⚠️ Note
This project was completed as part of the Image Processing course at SRH University of Heidelberg.
Code is shared for portfolio purposes only — please do not copy for academic submission.
