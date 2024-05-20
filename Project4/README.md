# Project 4: Speech Emotion Recognition

The purpose of this project is to perform speech emotion recognition on the SHemo Persian dataset. The goal is to extract relevant features from speech data, utilize neural networks that maintain temporal dependencies, classify the emotions, and investigate the impact of gender on emotion recognition.

## Steps Involved
1. Feature Extraction

    Objective: Extract meaningful features from the speech data.

   Actions:
        Extract MFCC: Use Mel-Frequency Cepstral Coefficients (MFCC) to capture the power spectrum of the speech signal.
        Additional Features: Optionally extract other features such as pitch, energy, and formants to enrich the feature set.

3. Data Preprocessing

    Objective: Prepare the data for training and evaluation.

   Actions:
        Normalize or standardize the extracted features.
        Split the dataset into training, validation, and test sets ensuring a balanced distribution of emotions across these sets.

5. Neural Network Model Training

    Objective: Train neural networks that can maintain temporal dependencies in the speech data.

   Actions:
        LSTM and GRU: Design and train Long Short-Term Memory (LSTM) and Gated Recurrent Unit (GRU) networks to capture the temporal dependencies in the speech data.
        Tune hyperparameters such as the number of layers, units per layer, learning rate, and batch size.

7. Classification

    Objective: Classify the emotions using the trained models.

   Actions:
        Use the trained LSTM and GRU models to predict emotions on the test set.
        Evaluate the classification performance using metrics such as accuracy, precision, recall, and F1-score.

9. Gender Impact Analysis

    Objective: Investigate the impact of gender on speech emotion recognition.

   Actions:
        Analyze the performance of the emotion recognition model separately for male and female speakers.
        Compare the results to identify any significant differences in model performance based on gender.
        Visualize the findings to understand the gender-related variations in emotion recognition.

11. Model Evaluation and Interpretation

    Objective: Assess the performance and interpret the results of the models.

    Actions:
        Evaluate the models on the test set to measure their accuracy in emotion recognition.
        Analyze confusion matrices to understand misclassifications.
        Visualize the results to interpret how well the models distinguish between different emotions.
