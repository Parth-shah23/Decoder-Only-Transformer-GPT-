# Decoder-Only Transformer (GPT) from Scratch

Implemented a GPT-style decoder-only Transformer architecture from scratch using **PyTorch**.

## Architecture

The implementation follows the decoder-only Transformer architecture illustrated below.

![Decoder-Only Transformer Architecture](https://github.com/user-attachments/assets/4c697cfa-e48c-4f53-81bc-df515087e83d)

## Dataset

Used the **Tiny Shakespeare** dataset to train a character-level language model.

The model learns to generate text by predicting the next character based on a sequence of previously observed characters.

## Implementation

All major architectural components were implemented manually using PyTorch, with a focus on understanding the underlying mathematical operations and how the individual components work together.

Key components implemented:

- Character Embeddings
- Positional Embeddings
- Masked Self-Attention
- Multi-Head Self-Attention
- Feed-Forward Neural Network
- Residual Connections
- Layer Normalization
- Transformer Decoder Blocks
- Language Modelling Head
- Autoregressive Next-Character Prediction

## Objective

The primary objective of this project was not to achieve a high validation score or build a production-level language model.

Instead, the focus was on developing a deeper understanding of the GPT architecture by implementing its individual components from scratch, including the mathematical concepts behind attention mechanisms, causal masking, and the overall Transformer architecture.

## Training

The model was trained on the Tiny Shakespeare dataset using **character-level next-character prediction**.

Given a sequence of input characters, the model learns to predict the next character autoregressively. Training and validation loss were monitored to evaluate the learning process.

## Tech Stack

- Python
- PyTorch
- Google Colab
- Tiny Shakespeare Dataset
## Training

The model was trained on the Tiny Shakespeare dataset using next-token prediction.

Training and validation loss were monitored to evaluate the learning process.

