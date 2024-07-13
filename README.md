# Abstractive Text Summarization with Transformer Model

This project demonstrates an implementation of abstractive text summarization using a transformer model, specifically the BART (Bidirectional and Auto-Regressive Transformers) model, fine-tuned on a subset of the CNN/Daily Mail dataset.

## Project Overview

1. **Dataset Loading and Preprocessing**: Load the CNN/Daily Mail dataset, select a subset of samples, and preprocess them for training.
2. **Data Visualization**: Visualize the distribution of text and summary lengths.
3. **Custom Dataset Class**: Define a custom PyTorch Dataset class to handle the tokenization and preparation of input data for the model.
4. **Model Training**: Fine-tune the BART model on the preprocessed dataset.
5. **Model Evaluation**: Evaluate the model using ROUGE scores to measure the quality of the generated summaries.
6. **Result Visualization**: Visualize the ROUGE scores using bar plots.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/princemsd007/abstractive-text-summarization.git
   cd abstractive-text-summarization
