# Emotion Detection from Text

> Detecting emotions in text using a **GloVe + LSTM** deep learning model built with PyTorch — achieving **84.4% test accuracy** across 5 emotion categories.

[![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)](https://python.org)
[![PyTorch](https://img.shields.io/badge/PyTorch-Deep%20Learning-EE4C2C?logo=pytorch)](https://pytorch.org)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)](https://jupyter.org)
[![TCS iON](https://img.shields.io/badge/Internship-TCS%20iON-blue)](https://ionilearning.com)

---

## Overview

Social media generates vast amounts of text expressing emotions that are difficult to detect automatically. This project builds an NLP pipeline that classifies any input text into one of **5 emotion categories** using pretrained GloVe word embeddings fed into a 2-layer LSTM network.

**Developed during a TCS iON Remote Internship** under the mentorship of Mr. Debashis Roy.

## Emotion Classes

| Label | Emotion |
|---|---|
| 0 | ❤️ Loving |
| 1 | ⚽️ Playful |
| 2 | 😄 Happy |
| 3 | 😞 Annoyed |
| 4 | 🍽 Foodie |

## Model Architecture

```
Input Text → GloVe Embeddings (50d, frozen)
           → 2-layer LSTM (hidden size: 128, dropout: 0.5)
           → Fully Connected Layer
           → Softmax → Emotion Class
```

| Component | Details |
|---|---|
| Word Embeddings | GloVe 50-dimensional (pretrained, frozen) |
| LSTM | 2 layers, hidden size 128, dropout 0.5 |
| Optimizer | Adam (lr=0.002) |
| Loss | CrossEntropyLoss |
| Epochs | 50 |
| Batch size | 32 |

## Results

| Metric | Value |
|---|---|
| Test Accuracy | **84.4%** |
| Test Loss | 1.060 |

Training converged steadily from 33.3% accuracy at epoch 1 to 84.4% at epoch 50.

## Tech Stack

- **Python 3** — core language
- **PyTorch** — model definition, training loop, GPU support
- **NumPy / Pandas** — data loading and preprocessing
- **Matplotlib** — training/loss curve visualization
- **GloVe** — pretrained 50-dimensional word embeddings

## How to Run

**1. Clone the repo and install dependencies**
```bash
git clone https://github.com/aman7401/Emotion-Detection-From-Text-or-Paragraph.git
cd Emotion-Detection-From-Text-or-Paragraph
pip install torch numpy pandas matplotlib
```

**2. Download GloVe embeddings**
```bash
# Download glove.6B.50d.txt and place in data/
mkdir data
# https://nlp.stanford.edu/projects/glove/ → glove.6B.zip
```

**3. Add datasets**
Place `train.csv` and `test.csv` in the `data/` folder.

**4. Run the notebook**
```bash
jupyter notebook project.ipynb
```

**5. Predict on custom text**
```python
predict("I had such an amazing day!")
# Input Text:   I had such an amazing day!
# Emotion:      😄 Happy
```

## Certificate

[View TCS iON Internship Certificate](./Certificate.pdf)
