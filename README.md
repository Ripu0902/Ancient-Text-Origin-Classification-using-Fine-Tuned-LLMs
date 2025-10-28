# 🏺 Ancient Text Origin Classification using Fine-Tuned LLMs

This repository explores how **Large Language Models (LLMs)** and **deep learning architectures** can be fine-tuned to classify the **origin of ancient texts** based on linguistic and semantic cues.  
The project compares multiple approaches — transformer-based and hybrid neural models — to understand how AI can capture subtle linguistic patterns in low-resource or ancient language datasets.

---

## 📘 Project Overview

Ancient texts hold deep cultural and linguistic significance. However, identifying their **geographical or cultural origin** is challenging due to limited labeled data and cross-linguistic variance.  
This project leverages **fine-tuned LLMs** to predict text origin and evaluate how different architectures generalize across ancient and classical languages.

Three different models were trained and compared for this task:
1. **DistilBERT (with Focal Loss)** — optimized for class imbalance.  
2. **XLM-RoBERTa** — a multilingual transformer capable of understanding cross-language semantics.  
3. **CNN + BiLSTM Hybrid** — deep neural model combining convolutional and recurrent learning for contextual representation.

---

## 🧩 Notebooks and Models

| Model | Notebook | Description |
|--------|-----------|-------------|
| DistilBERT (Focal Loss) | `distillbert-focal-loss.ipynb` | Lightweight transformer fine-tuned using Focal Loss to manage class imbalance. |
| XLM-RoBERTa | `XLMRobertaForSequenceClassification.ipynb` | Multilingual model designed to capture semantic relationships across language families. |
| CNN + BiLSTM | `CNN+BiLSTM.ipynb` | Neural hybrid architecture that merges spatial (CNN) and temporal (BiLSTM) features for sequence understanding. |

---

## 🧠 Techniques and Concepts

- **Transformer Fine-Tuning:** DistilBERT, XLM-RoBERTa  
- **Loss Optimization:** Focal Loss for handling imbalanced datasets  
- **Tokenization:** Byte-Pair Encoding (BPE), SentencePiece  
- **Deep Learning:** CNN, BiLSTM, Attention mechanisms  
- **Evaluation Metrics:** Accuracy, Precision, Recall, F1-Score  
- **Data Preprocessing:** Text normalization, stopword removal, and ancient script handling  

---

## ⚙️ Setup Instructions

To run these notebooks locally or on Google Colab:

```bash
# Clone this repository
git clone https://github.com/<your-username>/ancient-text-origin-classification.git
cd ancient-text-origin-classification

# Install dependencies
pip install -r requirements.txt
