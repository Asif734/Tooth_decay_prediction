# 🦷 Dental Caries Detection — Custom CNN vs VGG16/VGG19
## 📌 Overview

This project performs comparative analysis between a custom CNN architecture and transfer learning models (VGG16, VGG19) for dental caries (tooth decay) detection from X-ray images.
All models were trained, evaluated, and exported for deployment.

## ⚙️ Features

Preprocessing with resizing, rescaling, and augmentation

Dataset partitioning (train/val/test)

Custom CNN (5 Conv layers + Dense)

Transfer Learning with VGG16 and VGG19

Accuracy/Loss visualization

.h5 models saved for deployment

 ## 📂 Dataset

Two classes:

caries

no-caries

~1.5K images total

## 📊 Results (Comparative Analysis)
Model	Val Accuracy	Test Accuracy
Custom CNN	~85.9%	79.7%
VGG16	~90.6%	86.5%
VGG19	~88.3%	82.8%

## ✅ VGG16 outperformed both the custom CNN and VGG19, showing the power of transfer learning on small datasets.

### 🚀 Usage

Clone repo and install dependencies:
```bash
git clone https://github.com/yourusername/Dental-Caries-Detection.git
cd Dental-Caries-Detection
pip install -r requirements.txt
```


Run models in Colab or locally:
```bash

CustomCNN.ipynb → Train custom CNN

VGG16_implementation.ipynb → Train VGG16

VGG19_implementation.ipynb → Train VGG19
``` 
### 🔮 Future Work

Fine-tuning deeper layers of VGG

Try EfficientNet or MobileNet for lightweight deployment

Build a web app (Streamlit/Gradio + FastAPI backend)

### 👨‍💻 Author

Asifuzzaman Asif
GitHub
 • LinkedIn
