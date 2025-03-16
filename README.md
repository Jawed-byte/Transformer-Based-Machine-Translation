# Transformer-Based Machine Translation (EN-IT)

## Overview

This project implements a Transformer-based machine translation model from scratch for English-to-Italian translation. The model is trained on the OPUS Books dataset from Hugging Face and follows the architecture introduced in the seminal paper "Attention Is All You Need".

## Features

- Custom Transformer Model: Implemented from scratch using PyTorch.

- Support for Multiple Language Pairs: The model can be adapted to other language pairs beyond English-Italian.

- Inference & Evaluation: Compares model-generated translations with target sentences.

- Attention Map Visualization: Displays attention weights to interpret translation behavior.

- End-to-End Training Pipeline: Data preprocessing, tokenization, model training, and evaluation.

## Dataset

The model is trained on the OPUS Books dataset available on Hugging Face.

## Model Architecture

The Transformer model consists of:

- Encoder-Decoder Structure: Both composed of multi-head self-attention and feed-forward layers.

- Positional Encoding: Adds information about word positions.

- Multi-Head Attention: Enables the model to focus on different parts of the input.

- Layer Normalization & Dropout: For stable training.

- Beam Search for Inference: Improves translation quality.