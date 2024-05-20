# Fraud Detection Using Autoencoder

The purpose of this project is to detect fraudulent transactions using an autoencoder on the IEEE-CIS Fraud Detection dataset. By training the autoencoder on normal (non-fraudulent) data, the model learns the normal patterns and distribution of the data. Therefore, we expect that for normal data, the reconstruction error will be low. Conversely, if the reconstruction error is high for certain data points, they are likely to be fraudulent

## Steps Involved
1. Exploratory Data Analysis (EDA)

    Objective: Understand the dataset and prepare it for modeling.

   Actions:
        Fill Null Values: Handle missing values appropriately.
        Delete Irrelevant Features: Remove features that are irrelevant or have a high percentage of missing values.
        Feature Extraction: Analyze relationships between features to create new, beneficial features.

3. Data Preprocessing

    Objective: Prepare the data for training the autoencoder.

   Actions:
        Normalize or standardize numerical features.
        Encode categorical variables if necessary.
        Split the dataset into training and test sets, ensuring the training set contains only normal (non-fraudulent) transactions.

5. Autoencoder Model Training

    Objective: Train an autoencoder to learn the normal data patterns.

   Actions:
        Design an autoencoder architecture suitable for the dataset.
        Train the autoencoder on the normal dataset.
        Monitor the training process and adjust hyperparameters as needed.

7. Anomaly Detection

    Objective: Identify fraudulent transactions using the trained autoencoder.

   Actions:
        Compute the reconstruction error for the test set.
        Set a threshold for the reconstruction error above which transactions are classified as fraudulent.
        Evaluate the model's performance using appropriate metrics such as Precision, Recall, and F1-score.

9. Model Evaluation and Interpretation

    Objective: Assess the performance and interpret the results of the model.

   Actions:
        Evaluate the model on a labeled test set to measure its accuracy in detecting fraud.
        Analyze the reconstruction error distribution to refine the fraud detection threshold.
        Visualize the results to understand the model's effectiveness and identify areas for improvement.


