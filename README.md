# **DIO Challenge: Image Dimensionality Reduction**

-----

This project demonstrates the manual implementation of fundamental image processing algorithms in Python. The main objective is to convert a color image to grayscale and then to a black-and-white version, highlighting the concept of **dimensionality reduction**.

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/11Whp_pj1F0Da0Xv60TPLaNAf-gusWC05?usp=sharing)

-----

### **Objective**

The project's goal is to implement two classic image processing algorithms from scratch. The focus is on demonstrating, through direct manipulation of pixel data, how grayscale conversion and binarization are performed without relying on high-level library functions that automate these tasks.

-----

### **Methodology**

The implementation followed a sequential image transformation process, using a manual approach for pixel calculations and decisions.

  * **Grayscale Conversion:** For each pixel in the color image (represented by its R, G, and B values), a **weighted average formula** was applied to calculate a single intensity value. This process transformed the image from a three-dimensional color space to a one-dimensional space.

  * **Image Binarization:** Starting from the grayscale image, a **threshold** was defined. Each pixel was compared to this threshold, and its value was replaced by `0` (black) or `255` (white), resulting in a two-color image.

-----

### **Technologies Used**

  - `Python`
  - `Pillow` (Used exclusively for loading and saving image files)
  - `Google Colab`
