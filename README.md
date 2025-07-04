# Computer Vision with Deep Learning (Kaggle Course Project)

Welcome to my project repository for the **Computer Vision** course completed on [Kaggle Learn](https://www.kaggle.com/learn/computer-vision). This course provided a hands-on introduction to the core components of convolutional neural networks (CNNs), including convolution, pooling, classification, and object detection using sliding windows.

---

## Course Breakdown

The course is divided into six core modules, each focusing on a specific concept essential to computer vision and CNNs:

1. **Convolution and ReLU**  
   - How convolution layers detect patterns  
   - The role of ReLU in introducing non-linearity

2. **Custom ConvNet**  
   - Building CNNs from scratch using Keras  
   - Layer stacking, filter design, and flattening

3. **Max Pooling**  
   - Reducing spatial dimensions  
   - Improving feature robustness to translation

4. **Maximum Pooling**  
   - Hands-on implementation of pooling layers  
   - Difference from average pooling and its effect

5. **The Convolutional Classifier**  
   - Fully connected layers after convolutions  
   - Training end-to-end classifiers on image data

6. **The Sliding Window**  
   - Object detection using sliding windows  
   - Heatmaps and class activation for localization

---

## Environment & Execution

- All code was developed and executed on **Google Colab**, allowing fast prototyping with GPU acceleration.
- Each lesson has a separate notebook and Python script version for reproducibility and modular design.

---

## Repository Structure

```bash
computer_vision/
│
├── notebooks/               # Google Colab Notebooks
│   ├── 01_convolution_relu.ipynb
│   ├── 02_custom_convnet.ipynb
│   ├── 03_max_pooling.ipynb
│   ├── 04_maximum_pooling.ipynb
│   ├── 05_conv_classifier.ipynb
│   └── 06_sliding_window.ipynb
│
├── python/                  # Equivalent Python scripts
│   ├── convolution_relu.py
│   ├── custom_convnet.py
│   ├── max_pooling.py
│   ├── maximum_pooling.py
│   ├── conv_classifier.py
│   └── sliding_window.py
│
├── data/                    # Sample images or preprocessed datasets
│
├── images/                  # Output visualizations
│   └── filters_example.png
│
├── README.md
└── requirements.txt
