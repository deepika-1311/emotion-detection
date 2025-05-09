
# Multilingual Emotion Detection in Voice

## Overview
This project focuses on detecting emotions from voice recordings across multiple languages. It leverages deep learning techniques and audio processing to classify speech into predefined emotional categories.

## Features
- Multilingual speech emotion recognition.
- Preprocessing of audio files using Mel-Frequency Cepstral Coefficients (MFCCs).
- Training and evaluation of deep learning models (e.g., CNN, LSTM).
- Visualization of training results and confusion matrices.

## Datasets
The model uses publicly available multilingual emotional speech datasets such as:
- **CREMA-D**
- **TESS**
- **RAVDESS**

## Requirements
- Python 3.x
- TensorFlow / Keras
- Librosa
- NumPy
- Pandas
- Matplotlib
- Scikit-learn

Install dependencies:
```bash
pip install librosa tensorflow pandas matplotlib scikit-learn
```

## Usage
1. **Preprocess Data**: Extract MFCCs from audio files.
2. **Train Model**: Use a CNN/LSTM model to train on extracted features.
3. **Evaluate Model**: Assess performance on validation and test datasets.
4. **Predict Emotions**: Run inference on new audio clips.

## Results
The notebook provides:
- Accuracy and loss curves.
- Confusion matrix.
- Emotion prediction samples.

## Future Work
- Improve generalization across more languages.
- Incorporate attention mechanisms.
- Deploy model in a real-time application.
