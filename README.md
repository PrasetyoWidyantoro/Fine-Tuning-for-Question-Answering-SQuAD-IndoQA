# Fine-Tuning-for-Question-Answering-SQuAD-IndoQA

This repository contains code and resources for fine-tuning NLP models on the SQuAD and IndoQA datasets for question answering tasks. The aim is to leverage advanced transformer-based models to improve performance on these popular QA benchmarks.

## Key Features
- Fine-tuning scripts for SQuAD and IndoQA datasets
- Preprocessing and data augmentation techniques
- Evaluation metrics and performance

## Datasets and Models
### Bahasa Indonesia
- **Dataset**: [Jakartaresearch/IndoQA](https://huggingface.co/datasets/jakartaresearch/indoqa)
- **Model**: [IndoBERT-Base-P2](https://huggingface.co/indobenchmark/indobert-base-p2) for tokenizer and modeling question answering

### English
- **Dataset**: [SQuAD](https://rajpurkar.github.io/SQuAD-explorer/)
- **Model**: [DistilBERT-Base-Uncased](https://huggingface.co/distilbert-base-uncased) for tokenizer and modeling question answering

## Getting Started
### Prerequisites
- Python 3.7+
- PyTorch
- Transformers library by Hugging Face