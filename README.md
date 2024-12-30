# Image-SuperResolution-SRCNN-EDSR
# **Image Super-Resolution: SRCNN vs. EDSR**

## **Overview**
This project showcases a comparison between two powerful models for image super-resolution: SRCNN (Super-Resolution Convolutional Neural Network) and EDSR (Enhanced Deep Super-Resolution Network). The goal is to upscale low-resolution images into high-resolution versions while evaluating the strengths and limitations of each model.

Through this project, I gained practical insights into:
- Training convolutional neural networks for image super-resolution.
- Handling large datasets for vision tasks.
- omparing and visualizing results using key evaluation metrics like PSNR and SSIM.
  
---

## **Project Details**
### **Framework**
- PyTorch

### **Dataset**
- **DIV2K Dataset**: [Link](https://data.vision.ee.ethz.ch/cvl/DIV2K/)
  - **Training Data**: 800 image pairs.
  - **Validation Data**: 100 image pairs.
  - **Low-Resolution Input**: Downscaled to 128x128.
  - **High-Resolution Target**: Resized to 512x512.
  - Model Architectures:

SRCNN: Lightweight and fast, designed for basic super-resolution tasks.
EDSR: Advanced, deeper architecture for sharper and more detailed results using residual connections.

---## **Code and Notebook**
You can also open the notebook in Google Colab for interactive execution:  
[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1-A3UHjZyNZNhmodw6cZ4gXwa-AA-_pLb?usp=drive_link)

---
### **Learning Outcomes**
- Understood and implemented two distinct architectures for super-resolution tasks.
- Preprocessed and handled large image datasets efficiently.
- Evaluated models using both visual outputs and metrics like PSNR and SSIM.
- Preprocessed and handled large image datasets efficiently.
- Learned the importance of residual connections in enhancing image quality.


---

### **Future Improvements** 
- Extend the comparison by implementing SRGAN for perceptual-quality super-resolution.
- Experiment with larger datasets and fine-tune hyperparameters for better results.
- Optimize inference for real-time applications in streaming and healthcare.

### **Contributors**
Teja Gopal Reddy Vaka - Aspiring to become a top 1% AI professional.
