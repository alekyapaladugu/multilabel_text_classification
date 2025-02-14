# Multi-Label Text Classification with Graph Neural Networks & BERT

## Overview
This project implements **multi-label text classification** using **Graph Neural Networks (GNNs)** and **BERT**. The goal is to improve classification accuracy by leveraging both attention-based GNNs and transformer-based models.

## Features
- **Graph Neural Networks (GNNs)**: Implements an attention-based GNN for text classification.
- **BERT Transformer**: Enhances feature extraction and improves classification accuracy.
- **Multi-Label Classification**: Predicts multiple labels for each input text.
- **Performance Improvement**: Achieved a **0.5% accuracy boost** by integrating BERT with the existing GNN model.

## Technology Stack
- **Deep Learning Framework**: PyTorch
- **Transformer Model**: BERT
- **Graph Neural Networks**: Implemented using PyTorch Geometric
- **Dataset**: Processed multi-label classification dataset

## Implementation Highlights
- Designed the **base model** following a research paper on **multi-label classification using attention-based GNNs**.
- Integrated **BERT embeddings** into the model, leading to an **accuracy improvement of 0.5%**.
- Experimented with **different graph structures** and **attention mechanisms** to optimize the classification performance.

## Results
- The BERT-enhanced model outperformed the base GNN model by **0.5%** in accuracy.
- Demonstrated improved multi-label classification capabilities with real-world datasets.

## Future Work
- **Exploring Other Transformers**: Experiment with RoBERTa, T5, and XLNet.

