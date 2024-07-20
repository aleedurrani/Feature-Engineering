# Feature Selection Using Genetic Algorithm on RAVDESS Facial Landmark Tracking Dataset

## Overview
This project implements feature selection using a Genetic Algorithm (GA) on the RAVDESS (Ryerson Audio-Visual Database of Emotional Speech and Song) Facial Landmark Tracking dataset. The goal is to enhance a neural network's ability to classify emotions by selecting the most discriminative facial landmarks. The focus is on the emotions "happy" and "sad".

## Dataset
The RAVDESS Facial Landmark Tracking dataset includes facial landmark movements tracked using OpenFace 2.1.0. For this project, the emotions "happy" (emotion code 03) and "sad" (emotion code 04) from the speech modality (modality code 03) are used.

## Steps
- Loads the dataset.
- Extracts data for the emotions "happy" and "sad".
- Preprocesses the data.
- Implements a Genetic Algorithm to select the most discriminative features.
- Trains a neural network with the selected features.
- Evaluates the model's accuracy.

## Results
The final accuracy of the neural network with the selected features is printed.
The selected features are also printed for further analysis.

## Dataset Link
Link to the dataset: https://www.kaggle.com/datasets/uwrfkaggler/ravdess-facial-landmark-tracking
