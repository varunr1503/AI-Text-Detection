# AI-Generated Text Detection with DistilBERT

This repository contains an implementation of a **DistilBERT-based model** for detecting AI-generated text. The model is trained on labeled datasets of human-written and AI-generated text, making it capable of classifying text into one of these two categories.

## Features
- **Tokenizer:** Custom Byte Pair Encoding (BPE) tokenizer trained with a vocabulary size of 10,000.
- **Model:** DistilBERT-based architecture with 3 Transformer layers.
- **Training:** Includes class balancing, early stopping, and efficient training with the Hugging Face `Trainer` API.
- **Inference:** Provides utilities for testing the model on unseen data and generating real-time predictions.
- **Portability:** Trained model and tokenizer saved as `.tar.gz` archives for easy deployment.

---
