# MMBT-based Multi-Aspect Classification ( Multi Tasking Central Net )

This repository contains an implementation of a **Multi-Modal Bitransformer (MMBT)** model for multi-aspect classification of textual complaints. The approach leverages both text and image modalities to identify multiple aspects in financial complaint data, enabling fine-grained understanding and explainability.

## 📄 Project Overview

Many real-world financial complaints contain textual descriptions along with supporting images or screenshots. Classifying these complaints into multiple aspects (e.g., billing issues, loan problems, fraud detection) helps financial institutions prioritize and resolve cases efficiently.

In this notebook, we:

- Use the MMBT model to integrate text and image modalities.
- Perform multi-label aspect classification on complaint data.
- Visualize and analyze model performance.

## ⚡ Key Features

- **Multi-modal learning:** Combines textual and image representations using a Bitransformer-based architecture.
- **Multi-aspect prediction:** Supports assigning multiple aspects to each complaint.
- **Explainability:** Provides insights into model decisions using attention mechanisms and interpretability tools.

## 🧑‍💻 Technical Details

- **Architecture:** MMBT (Multi-Modal Bitransformer) combining BERT (for text) and ResNet (for image embeddings).
- **Data:** Financial complaints dataset with annotated aspects and optional image attachments.
- **Loss function:** Multi-label classification loss (Binary Cross-Entropy).
- **Evaluation metrics:** F1-score, accuracy, and aspect-level performance metrics.

## 🚀 Getting Started

### Prerequisites

- Python 3.8+
- PyTorch
- Transformers (Hugging Face)
- torchvision
- Other standard scientific Python libraries (numpy, pandas, matplotlib)

### Running the Notebook

```bash
git clone https://github.com/yourusername/MMBT-Multi-Aspect-Classification.git
cd MMBT-Multi-Aspect-Classification
jupyter notebook
