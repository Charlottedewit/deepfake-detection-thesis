# Deepfake Detection Using Deep Learning

This repository contains the Jupyter Notebook for the master's thesis:

**"Detecting Deepfake Images Using Deep Learning"**  
*Charlotte de Wit* – Tilburg University, 2025  
*MSc in Data Science & Society*

---

## 📘 Thesis Overview

This thesis compares three deep learning models:
- XceptionNet
- EfficientNetB0
- Vision Transformer

These models are evaluated on the Face Deepfake Detection Challenge (FDDC) dataset using:
- Stratified K-Fold Cross-Validation
- GAN-specific bias analysis
- Saliency maps for interpretability
- Effect size calculation (Cohen’s d)
- Evaluation under distortion (blur, noise, compression, rotation)

---

## ▶️ How to Use

You can run the notebook in Google Colab or locally in Jupyter Lab.

### Requirements (Local)

Install packages with:
```bash
pip install -r requirements.txt
```

---

## 📦 Dataset

We use the **Face Deepfake Detection Challenge (FDDC)** dataset. You must request access via:  
➡️ [FDDC Dataset](https://github.com/aimagelab/Face-Deepfake-Detection-Challenge)

*Note: The dataset is not included in this repo due to license restrictions.*

---

## 🔧 Main Dependencies

- tensorflow==2.12.0  
- scikit-learn==1.3.0  
- opencv-python  
- numpy, pandas, matplotlib, scipy

---

## 📜 License

MIT License *(optional)*

## 🤖 AI Assistance Disclosure

ChatGPT (OpenAI, GPT-4) was used to help write and debug code. All output was manually reviewed and revised.
