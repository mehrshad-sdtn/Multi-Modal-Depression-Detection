# Multi-Modal-Depression-Detection
Automatic Depression Detection Using An Interpretable Audio-textual Multi-modal Transformer-based Model

## Overview
This repository contains the implementation for a multi-modal depression detection model that combines audio and textual data using a Transformer-based architecture. The model is designed to detect depression levels in subjects based on their speech recordings and corresponding transcriptions. The approach leverages interpretability techniques to analyze attention mechanisms within the model.

## Features
- **Multi-modal integration**: Combines audio and text data for enhanced depression detection.
- **Transformer-based architecture**: Uses BERT embeddings for text and a custom Transformer encoder for audio.
- **Interpretable design**: Visualizes attention weights to provide insights into model decision-making.

## Report
A detailed report of the project, including the methodology, experiments, and results, is available [here](https://github.com/mehrshad-sdtn/Multi-Modal-Depression-Detection/blob/master/NLP-Report.pdf).

## Dataset
The model uses the DAIC-WOZ dataset, which includes:
- Audio embeddings for each sentence (256-dimensional vectors).
- Transcriptions of participant responses.

## Implementation
The repository includes:
1. **Data preprocessing**:
   - Text preprocessing with BERT tokenizer.
   - Audio embeddings processed for each sentence.
2. **Model architecture**:
   - A Transformer-based multi-modal model integrating both audio and text features.
   - Separate encoders for audio and text, with a shared fully connected classification layer.
3. **Training and evaluation pipeline**:
   - Cross-entropy loss and AdamW optimizer.
   - Metrics: Accuracy and loss tracking during training and evaluation.
4. **Interpretability**:
   - Visualization of attention weights for insights into model focus during predictions.



