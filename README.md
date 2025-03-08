# Speech Recognition System

## Overview
This project focuses on building a speech recognition system using machine learning and deep learning techniques. The system converts spoken language into text by processing audio input and applying speech-to-text algorithms.

## Dataset 
The dataset consists of labeled audio recordings with corresponding transcriptions. It includes features such as:
- Audio waveforms and spectrograms
- Speaker metadata (if applicable)
- Transcriptions of spoken words

## Feature Engineering
Feature engineering was performed to improve model accuracy. This includes:
- Converting audio signals into spectrograms (MFCC, Mel-spectrogram, STFT)
- Noise reduction and audio preprocessing
- Normalization and feature scaling
- Data augmentation techniques such as time-stretching and pitch shifting

## Machine Learning Models
Several models were implemented for speech recognition:
- **Traditional Models**:
  - Hidden Markov Models (HMM)
  - Gaussian Mixture Models (GMM)
- **Deep Learning Models**:
  - Recurrent Neural Networks (RNN)
  - Long Short-Term Memory (LSTM)
  - Convolutional Neural Networks (CNN)
  - Transformer-based models (Wav2Vec, DeepSpeech)

## Model Evaluation
The models were evaluated using various performance metrics, including:
- Word Error Rate (WER)
- Character Error Rate (CER)
- Accuracy
- Perplexity (for language models)

## Requirements
To run this project, install the necessary dependencies:
```bash
pip install numpy pandas librosa torch tensorflow speechrecognition transformers
```

## How to Run
1. Load the dataset.
2. Preprocess and extract features from audio files.
3. Train and evaluate speech recognition models.
4. Convert audio input into text using the trained model.

## Conclusion
This project demonstrates the use of machine learning for speech recognition. Future improvements could include integrating attention mechanisms, improving noise robustness, or fine-tuning transformer models for better accuracy.

## Author 
Gunjan Mishra

