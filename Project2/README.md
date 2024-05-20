# Project 3-1 : Traffic Sign Classification and 

The purpose of this project is to classify traffic signs into 43 distinct classes accurately. The project involves several steps to ensure the robustness and accuracy of the classification model.

## Steps Involved
1. Investigate Class Balance

    Objective: Check if the dataset has a balanced distribution of classes.
    Action: If an imbalance is detected, apply techniques such as assigning weights to each class to address this issue.

2. Analyze Impact of Color on Accuracy

    Objective: Determine whether colored images or grayscale images yield better accuracy.
    Action: Compare the accuracy and computational costs of using colored images versus grayscale images.

3. Assess Image Situations and Enhancement Techniques

    Objective: Ensure uniform image conditions, such as lighting.
    Action: If variations are found, use image enhancement techniques like histogram equalization to improve image quality and consistency.

4. Data Augmentation

    Objective: Evaluate the impact of data augmentation on model generalization and accuracy.
    Action: Apply various data augmentation techniques and analyze their effects on the model's performance.

5. Run Best Model and Analyze Confusion

    Objective: Train the best-performing model and investigate any confusion between different traffic signs.
    Action: Generate and analyze a confusion matrix to understand misclassifications.

6. Use Grad-CAM Algorithm

    Objective: Visualize the model's focus on different parts of the images.
    Action: Apply the Grad-CAM algorithm to identify which areas of the images the model is focusing on during classification.

7. Extract and Analyze Layer Outputs

    Objective: Understand the internal workings of the model.
    Action: Extract outputs from each layer of the model and analyze them to gain insights into how the model processes information.





# Project 3-2 : House Price Estimation form Image and Text Features 

The purpose of this project is to predict the price of a house based on both its image and various numerical features such as street, city, number of bedrooms, number of bathrooms, and square footage (sqft). Additionally, the project aims to investigate the importance of the house image in the final prediction result.



## Steps Involved

1. Data Preprocessing

    Objective: Prepare the data for analysis and modeling.
    Action: Clean the dataset by handling missing values, encoding categorical variables, and normalizing numerical features.

2. Exploratory Data Analysis (EDA)

    Objective: Understand the dataset and identify any patterns or correlations.
    Action: Perform EDA to visualize distributions, relationships between features, and potential outliers.

3. Image Processing

    Objective: Prepare house images for input into the model.
    Action: Resize, normalize, and augment images to ensure they are in a suitable format for model training.

4. Model Development

    Objective: Develop a model to predict house prices using both images and numerical features.
    Action: Create and train a neural network that combines a Convolutional Neural Network (CNN) for image processing with a feedforward neural network for numerical features.

5. Model Evaluation

    Objective: Assess the performance of the model.
    Action: Evaluate the model using appropriate metrics such as Mean Absolute Error (MAE) or Root Mean Squared Error (RMSE).

6. Investigate Importance of Images

    Objective: Determine the contribution of house images to the prediction accuracy.
    Action: Compare the performance of models trained with and without images and analyze the impact of images on the final predictions.





