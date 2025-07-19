# 🖼️ Image Super-Resolution using Deep Learning

This project demonstrates a custom deep learning-based approach for enhancing low-resolution images using PyTorch. It focuses on single-image super-resolution (SISR), leveraging convolutional neural networks and classical image processing tools.

## 🧰 Key Features

- 📷 Image loading and preprocessing using `PIL`, `NumPy`, and `scikit-image`
- 🧠 Model built with PyTorch for super-resolution tasks
- 📊 Loss tracking and visualization of model outputs
- 🖼️ Evaluation on test samples and PSNR measurement
- 📁 Batch processing of images from folders

## 📦 Dependencies

```bash
pip install numpy matplotlib pillow torch torchvision scikit-image
```

## 🗂️ Project Structure

- **Image Preparation**: Loads and downscales high-res images for supervised training
- **Model Architecture**: Custom CNN or upsampling network in PyTorch
- **Training Loop**: Supports configurable epochs, optimizers, and PSNR evaluation
- **Evaluation**: Saves restored images and logs PSNR comparison

## 🚀 How to Run

1. Install dependencies
2. Organize your training/testing image folders
3. Run the notebook cell-by-cell
4. Visualize outputs and evaluate PSNR performance

## 📌 License

This notebook is intended for educational and research use only.
