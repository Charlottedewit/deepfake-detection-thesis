# Deepfake Detection Using Deep Learning

This repository contains the Jupyter Notebook supporting the master's thesis:

**"Detecting Deepfake Images Using Deep Learning"**  
*Charlotte de Wit* – Tilburg University, 2025  
*MSc in Data Science & Society*

---

## 📘 Thesis Overview

This thesis investigates and compares the performance of three deep learning models for deepfake image detection:

- **XceptionNet**
- **EfficientNetB0**
- **Vision Transformer (ViT)**

These models are evaluated on the Face Deepfake Detection Challenge (FDDC) dataset through:

- Stratified K-Fold Cross-Validation
- Bias analysis across GAN architectures
- Saliency map visualizations for interpretability
- Effect size estimation using Cohen’s *d*
- Performance testing under image distortions (blur, noise, compression, rotation)

---

## 🚀 How to Use

You can run the notebook in [Google Colab](https://colab.research.google.com) (recommended) or locally in Jupyter Lab.

### ✅ To run locally:
```bash
pip install -r requirements.txt
```

Then launch Jupyter:
```bash
jupyter notebook
```

---

## 📂 Dataset

This project uses the **Face Deepfake Detection Challenge (FDDC)** dataset.

Due to licensing restrictions, the dataset is not included in this repository.  
You must request access at:  
➡️ [FDDC Dataset – GitHub Page](https://github.com/aimagelab/Face-Deepfake-Detection-Challenge)

---

## 🧪 Main Dependencies

- `tensorflow==2.12.0`  
- `scikit-learn==1.3.0`  
- `opencv-python`  
- `numpy`, `pandas`, `matplotlib`, `scipy`

For full details, see [`requirements.txt`](./requirements.txt).

---

## 🤖 AI Assistance Disclosure

This codebase was developed by the author with support from **ChatGPT (OpenAI, GPT-4)** for code generation and debugging. All outputs were manually reviewed and integrated by the author. The use of AI tools is disclosed in accordance with academic integrity guidelines.

---

## 📄 License

This repository is released under the [MIT License](./LICENSE), unless otherwise specified.  
Pretrained models used from TensorFlow Keras Applications are licensed under the Apache 2.0 License.

---

## 📎 Citation

If you use this work in your research, please cite the thesis or repository as follows (example):

```
de Wit, C. (2025). Detecting Deepfake Images Using Deep Learning. MSc Thesis, Tilburg University. GitHub Repository: https://github.com/YOUR-USERNAME/deepfake-detection-thesis
```
