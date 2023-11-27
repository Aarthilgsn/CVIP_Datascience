## Speech Emotion Recognition

## Overview

* This Python script ```(speech_emotion_recognition.py) ``` is designed for Speech Emotion Recognition (SER), a branch of affective computing focused on automatically identifying emotions expressed in spoken language. The script utilizes machine learning techniques to build a Speech Emotion Recognition system and demonstrates its application in various fields such as human-computer interaction, customer service, mental health monitoring, and entertainment.

## Table of Contents

* [Introduction](#Introduction)
* [ProblemStatement](#ProblemStatement)
* [Solution](#Solution)
* [AboutDataset](#AboutDataset)
* [GettingStarted](#GettingStarted)
* [Prerequisites](#Prerequisites)
     * [Installation](#Installation)
     * [Usage](#Usage)
* [DataAugmentation](#DataAgumentation)
* [FeatureExtraction](#FeatureExtraction)
* [DataPreparation](#DataPreparation)
* [Modelling](#Modelling)
* [Results](#Results)
* [Conclusion](#Conclusion)

## Introduction

* Speech Emotion Recognition (SER) is a crucial aspect of affective computing, aiming to identify emotions expressed in spoken language. 
This script demonstrates the development of an effective SER system using machine learning techniques.

## ProblemStatement

* The Problem Statement of this project is to develop a robust speech emotion recognition system capable
of accurately classifying the emotional states conveyed in spoken language. By analyzing the
acoustic features of speech signals, the system should be able to categorize emotions such as
happiness, sadness, anger, fear, and more.

## Solution

* Developing an effective Speech Emotion Recognition system using machine learning to enhance applications 
in human-computer interaction, customer service, mental health monitoring, and entertainment by accurately 
identifying and responding to emotional states in spoken language

## AboutDataset

* The dataset used for this project is sourced from Kaggle: https://www.kaggle.com/datasets/uwrfkaggler/ravdess-emotional-speech-audio/data
It includes emotional speech audio data that is essential for training and evaluating the Speech Emotion Recognition model.

# Getting Started

## Prerequisites

* Python 3.7.4

* Libraries: pandas, numpy, librosa, seaborn, matplotlib, scikit-learn, keras

## Installation

```bash
pip install pandas numpy librosa seaborn matplotlib scikit-learn keras
```

## Usage

* Clone the repository:

 ```bash
[git clone https://github.com/yourusername/speech-emotion-recognition.git](https://github.com/Aarthilgsn/CVIP_DataScience.git)
```
* Navigate to the project directory:

```bash
cd speech_emotion_recognition
```

## DataAugmentation

* The script incorporates data augmentation techniques, including noise injection, stretching, shifting, 
and pitch modification, to enhance the training dataset and prevent overfitting.

## FeatureExtraction

* Feature extraction is a crucial step in SER. The script extracts features such as zero-crossing rate,
chroma_stft, MFCC, and Mel spectrogram to represent the acoustic characteristics of speech data.

## DataPreparation

* The data preparation section includes scaling and encoding the dataset to make it 
compatible with the machine learning model.

## Modelling

The script utilizes a Convolutional Neural Network (CNN) model for Speech Emotion Recognition. 
The model is trained, evaluated, and its performance is visualized.

## Result

* The results section includes visualizations of training and testing accuracy, as well as a 
confusion matrix and classification report for evaluating the model's performance.

## Acknowledgment

* We would like to express our gratitude to the open-source community and contributors who have
provided valuable resources and support for this project.

## Conclusion

* Speech Emotion Recognition through advanced machine learning techniques, addressing challenges 
for improved accuracy. The proposed system has the potential to significantly impact applications
in human-computer interaction, customer service, mental health monitoring, and entertainment.











