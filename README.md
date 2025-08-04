# 🌊 Flood Segmentation in Satellite Imagery using U-Net

This computer vision project utilizes a U-Net architecture for semantic segmentation of flood-affected areas in satellite images. The workflow includes image quality analysis, model training, and performance evaluation to detect and segment flooded regions accurately.

---

## 🔗 Dataset Access

[![Download Dataset](https://img.shields.io/badge/Download%20Dataset-003366?style=for-the-badge)](https://drive.google.com/file/d/1nyNF4jgF0vFHCbMwiVe7LlBvkiedF0aM/view?usp=sharing)

---

## 🔧 Features

- **Image Quality Analysis**
  - Sharpness evaluation to detect blurry images
  - Duplicate image removal
  - Color distribution and resolution checks

- **Segmentation Model**
  - U-Net architecture built with `TensorFlow` and `Keras`
  - Custom preprocessing and generator pipelines
  - Loss function: `Binary Crossentropy`
  - Metrics: Intersection over Union (IoU), Accuracy

- **Model Evaluation**
  - Visualization of training & validation loss, accuracy, and IoU over epochs
  - Final model evaluation with:
    - **Train Loss**: 0.1971
    - **Validation Loss**: 0.2359
    - **Train Accuracy**: 0.9089
    - **Validation Accuracy**: 0.8945
    - **Train IoU**: 0.8161
    - **Validation IoU**: 0.7999
  - Sample predictions visualized alongside ground truth masks

---

## 📊 Concepts Used

- Semantic Segmentation with U-Net
- Image denoising and quality control
- Data generators for image-mask pairs
- Binary segmentation using satellite imagery
- Evaluation using IoU, accuracy, and loss trends
4. Run `train_unet.py` to train the model.
5. Visualize results with the provided notebook or script.
