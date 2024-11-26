# deep-learning-challenge


# Performance Report: Deep Learning Model for Alphabet Soup
### Overview of the Analysis
The purpose of this analysis is to build and evaluate a deep learning model to predict the likelihood of successful funding for applicants in the Alphabet Soup dataset. The objective is to classify applications effectively, guiding the company in making better funding decisions.

### Results
#### Data Preprocessing
Target Variable:

IS_SUCCESSFUL: Indicates whether the funding was successful.
Features:

Categorical variables such as APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, and others.
Numerical variables like ASK_AMT.
Removed Variables:

EIN and NAME: These identifiers do not contribute meaningful information for predictions.
Compiling, Training, and Evaluating the Model
Model Architecture:

Neurons:
Layer 1: 80 neurons to capture a broad range of features.
Layer 2: 30 neurons for refined learning.
Activation Functions:
ReLU for hidden layers to handle non-linear relationships.
Sigmoid for the output layer to generate probabilities for binary classification.
Reasoning: This architecture balances model complexity and computational efficiency.
Model Performance:

The model did not meet the target accuracy of 75%, achieving approximately 72%.
Steps to Improve Performance:

Experimented with different numbers of neurons and layers.
Tried additional epochs during training to improve learning.
Adjusted the learning rate and optimizer settings.
Applied dropout layers to reduce overfitting.
Summary
The deep learning model achieved an accuracy of 72%, falling short of the target performance. While the model shows potential, improvements may require advanced techniques or alternative approaches.

### Recommendation:
Consider using a random forest or gradient boosting model for this classification problem. These models handle imbalanced datasets well, provide feature importance insights, and can achieve higher accuracy with less tuning compared to neural networks.

