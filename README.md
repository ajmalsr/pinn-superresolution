# 🎨✨ Physics-Informed Neural Network for SR Microscopy 🔬

## 🌟 Overview
This project reconstructs **sub-diffraction images** for **super-resolution (SR) microscopy** without requiring a training dataset. By leveraging a **deep neural network** paired with the **structured illumination process**, we optimize a **Physics-Informed Neural Network (PINN)** using a single set of diffraction-limited sub-images. This innovative approach eliminates the need for a pre-collected training set.

## 🚀 Key Features
✅ **No Training Data Required** – Unlike traditional methods, our approach optimizes directly from raw sub-images.  
✅ **Physics-Informed Learning** – The PINN is guided by the forward model of structured illumination.  
✅ **Super-Resolution Reconstruction** – Enhances image resolution beyond diffraction limits.  
✅ **Validated on Experimental Data** – Successfully tested using real microscopy images.  

## 🔍 How It Works
1️⃣ **Structured Illumination Model** – Incorporates physical constraints to guide the network.  
2️⃣ **Deep Neural Network Optimization** – Learns directly from sub-images without external training data.  
3️⃣ **Super-Resolved Image Generation** – Produces high-quality images with improved resolution.  

## ⚙️ Installation & Usage
To get started, clone this repository and install the required dependencies:
```sh
pip install numpy tensorflow matplotlib opencv-python scipy scikit-image
```
🎯 Run the main script:
```sh
jupyter notebook pinn_sim.ipynb
```

