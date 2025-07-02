# 🐜 Ant Type Classifier

This project uses deep learning to classify different types of ants from images, such as **carpenter ants**, **fire ants**, and **bullet ants**. The model is trained using your own curated dataset of ant images collected from the web.

## 📁 Project Structure

```
type_of_an_ant/
├── data/               # Contains subfolders of ant images by category
│   ├── carpenter_ant/
│   ├── fire_ant/
│   └── bullet_ant/
├── models/             # Trained models and checkpoints
├── type_of_an_ant__Creating_a_model_from_your_own_data.ipynb
├── README.md
└── requirements.txt    # Python dependencies
```

## 🧠 Model Overview

- **Model Type**: Convolutional Neural Network (CNN)
- **Framework**: FastAI (built on PyTorch)
- **Input**: Ant images (.jpg)
- **Output**: Ant type label
- **Training Data**: Images downloaded using `duckduckgo_search` and verified with `fastai.vision.verify_images`

## 🚀 How to Run

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/ant-type-classifier.git
cd ant-type-classifier
