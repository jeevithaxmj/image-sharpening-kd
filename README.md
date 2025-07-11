# image-sharpening-kd
Image sharpening using knowledge distillation with student-teacher CNN models
# Image Sharpening using Knowledge Distillation 🧠🔍

This project uses a **teacher-student CNN architecture** to perform **image sharpening** through **knowledge distillation**.

## 📁 Contents
- `image_sharpening_kd.ipynb`: Full training + evaluation code
- Sample results (SSIM ~ 0.92, PSNR ~ 19 dB)

## 🧠 Models
- **Teacher**: Deep CNN (Conv+ReLU)
- **Student**: Light CNN trained using:
  - MSE loss
  - Distillation loss
  - SSIM-based loss

## ✅ Results
- **SSIM**: 0.9209
- **PSNR**: 19.19 dB

## 🔧 Tech Stack
- PyTorch
- Google Colab
- `pytorch_msssim` for SSIM


