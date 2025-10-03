# 21days21projects

  All the projects I have made till now in my 21Days21Projects journey

# Day 10
  Creative AI Generating Art with Neural Style Transfer.

# Download This Folder

You can download this project folder using any of the following methods:

**Method 1: Using GitHub Web Interface**
1. Navigate to the [Project 9 folder](https://github.com/AbhishekPandey2005/21days21projects/tree/main/Project%209) on GitHub
2. Click the green "Code" button
3. Select "Download ZIP" to download the entire repository, then extract the Project 9 folder

**Method 2: Using Git Clone (Recommended for developers)**
```bash
# Clone the entire repository
git clone https://github.com/AbhishekPandey2005/21days21projects.git

# Navigate to Project 9
cd 21days21projects/Project\ 9
```

**Method 3: Using Git Sparse Checkout (Download only this folder)**
```bash
# Initialize a new git repository
mkdir 21days21projects && cd 21days21projects
git init

# Add the remote repository
git remote add origin https://github.com/AbhishekPandey2005/21days21projects.git

# Enable sparse checkout
git config core.sparseCheckout true

# Specify the folder to download
echo "Project 9/*" >> .git/info/sparse-checkout

# Pull the folder
git pull origin main
```

**Method 4: Direct Download Links**
- [Jupyter Notebook](https://github.com/AbhishekPandey2005/21days21projects/raw/main/Project%209/10_Gender_Style_Transfer.ipynb)
- [Female Images (ZIP)](https://github.com/AbhishekPandey2005/21days21projects/raw/main/Project%209/female_images.zip)
- [Male Images (ZIP)](https://github.com/AbhishekPandey2005/21days21projects/raw/main/Project%209/male_images.zip)
- [Female Images Data (CSV)](https://github.com/AbhishekPandey2005/21days21projects/raw/main/Project%209/female_images_data.csv)
- [Male Images Data (CSV)](https://github.com/AbhishekPandey2005/21days21projects/raw/main/Project%209/male_images_data.csv)

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
