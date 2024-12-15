# Lego-Dataset-600 Counting and Detecting LEGO Pieces

## Overview
This project explores classical computer vision techniques to detect and classify LEGO pieces based on their **color** and **shape**. It focuses on image segmentation methods, a key component in computer vision, to divide images into meaningful segments for better analysis and understanding.

---

## Objective
The project aims to:
1. Experiment with **three segmentation techniques**.
2. Evaluate their effectiveness in detecting and classifying LEGO pieces.
3. Determine the most suitable method for the LEGO dataset provided.

---

## Techniques Explored
1. **Thresholding**:
   - Converts images to binary format using a threshold value.
   - Separates objects from the background for simpler analysis.

2. **Edge Detection**:
   - Identifies edges in the image to outline the shapes of LEGO pieces.
   - Useful for structural analysis of objects.

3. **Color-Based Segmentation**:
   - Segments the image based on color regions.
   - Ideal for detecting distinct LEGO piece colors.

Each method is applied to the provided LEGO dataset to assess its performance, strengths, and limitations.

---

## Tools and Libraries
- **OpenCV**: For image processing and segmentation.
- **Python**: Programming language for implementation.
- **Jupyter Notebook**: For interactive development and visualization.

---

## Steps to Run the Project
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/lego-detection.git
