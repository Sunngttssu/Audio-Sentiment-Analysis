# Audio-Sentiment-Analysis using DL & NLP

## 🎙️ Overview

Understanding emotions through voice is a key aspect of building human-centered AI systems. This project explores Speech Emotion Recognition (SER) using Machine Learning and Deep Learning techniques, trained on the RAVDESS and TESS datasets. The goal is to automatically detect emotions from speech signals and enhance emotional intelligence in AI applications.

## 📊 Feature Set and Dataset Details

The dataset for this project consists of 5,252 audio samples, sourced from:

🗂️ RAVDESS (Ryerson Audio-Visual Database of Emotional Speech and Song)
* Includes 1,440 speech and 1,012 song recordings.
* Performed by 24 professional actors (12 male, 12 female).
* Covers 8 emotions: neutral, calm, happy, sad, angry, fearful, disgust, and surprised.
* Each file is validated on emotional accuracy, intensity, and genuineness by over 200 participants.
* [Dataset source](https://www.kaggle.com/datasets/uwrfkaggler/ravdess-emotional-speech-audio)

🗂️ TESS (Toronto Emotional Speech Set)
* Contains 2,800 speech recordings.
* Spoken by 2 female actors, aged 26 and 64.
* Emotions include: anger, disgust, fear, happiness, pleasant surprise, sadness, and neutral.
* Data collected in a controlled environment, both actors are musically trained and fluent in English.
* [Dataset source](https://www.kaggle.com/datasets/ejlok1/toronto-emotional-speech-set-tess)

## 🧠 Model Summary
* Features extracted using MFCCs (Mel-Frequency Cepstral Coefficients) via Librosa.
* Classification using Machine Learning models like SVM, KNN, and Random Forest.
* Performance metrics include accuracy score, confusion matrix, and classification report.

## 📉 Model Metrics
* Loss and Accuracy plots: Track training progress and convergence.
* Classification report: Includes precision, recall, and F1-score for each emotion class.
* Confusion matrix: Visualizes model predictions vs. actual labels.

## 🎧 Testing the Model
Example audio files are provided to demonstrate prediction performance.

You can also test the model with your own voice samples by placing them in a test directory and following the feature extraction format.
📌 Note: Emotion classes are label-encoded from 0 to 7, corresponding to:
        0: neutral, 1: calm, 2: happy, 3: sad, 4: angry, 5: fearful, 6: disgust, 7: surprised
