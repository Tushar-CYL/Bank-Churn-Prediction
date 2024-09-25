# Bank-Churn-Prediction
Problem Overview:
Customer churn is when a customer stops doing business with a company. Identifying these customers ahead of time allows the bank to take corrective actions, such as offering retention strategies. The dataset contains customer information like age, tenure, balance, and credit score, which are used to predict churn.

Model Approach:
We have implemented a Deep Learning Artificial Neural Network (ANN) to perform binary classification (churn or no churn). The ANN model is designed to capture complex patterns from the input features, which can help in accurate predictions.

Input Layer:        Features (Credit score, Age, Balance, etc.)
                   | 
                   ▼
Hidden Layer 1:    64 neurons, ReLU activation
                   |
                   ▼
Hidden Layer 2:    32 neurons, ReLU activation
                   |
                   ▼
Output Layer:      1 neuron, Sigmoid activation
