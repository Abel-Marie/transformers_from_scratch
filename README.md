# transformers_from_scratch# Amharic-to-English Transformer

This repository contains the source code for a Transformer model built with PyTorch to translate text from Amharic to English. The model architecture is based on the "Attention Is All You Need" paper.

## 📂 Repository Structure

- `src/`: Main source code directory.
  - `model.py`: Contains all `nn.Module` classes for the Transformer architecture.
  - `dataset.py`: Handles data loading, preprocessing, and tokenization.
  - `utils.py`: Helper functions for tasks like managing model weight files.
- `config.py`: A centralized file for all hyperparameters and settings.
- `train.py`: The main script to start the training process.
- `translate.py`: A script to perform inference (translate sentences) using a trained model.
- `requirements.txt`: A list of all Python dependencies.

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone <https://github.com/Abel-Marie/transformers_from_scratch>
cd transformers_from_scratch