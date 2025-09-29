# 21days21projects

  All the projects I have made till now in my 21Days21Projects journey

# Day 10
  Creative AI Generating Art with Neural Style Transfer.

# Overview: 
  This project implements a neural style transfer approach where stylistic attributes from gender-specific reference images are applied to content images while preserving their structure. The method leverages pretrained CNNs for feature extraction and optimization to generate stylized outputs.

# Workflow

  1) Data Loading & Preprocessing — Upload and prepare content/style images (Colab file utilities, imageio). Normalize and resize them for processing.

  2) Feature Extraction — Use pretrained CNN layers (tensorflow.keras.applications) to obtain content and style representations.
  
  3) Loss Functions —
  
  Content loss: Maintain key structures of the input image.
  
  Style loss: Capture stylistic gender patterns.
  
  Total variation loss: Ensure smoothness in generated results.
  
  4) Optimization — Iteratively refine the generated image with gradient descent to minimize combined losses.
  
  5) Visualization — Use Matplotlib and IPython display utilities to observe intermediate and final outputs.
  
  6) Conclusion — The notebook demonstrates practical style transfer; improvements could involve multiple style images, adaptive normalization, or GAN-based      architectures.

# Tech Stack
    Python  
    TensorFlow  
    NumPy, Pandas  
    Matplotlib  
    tqdm  
    imageio  
    IPython.display  
    Google Colab (for file handling)
