# Churn Prediction Classification using ANN

## Model Architecture

This churn prediction model is built using an Artificial Neural Network (ANN) and consists of the following layers:

1. **Input Layer**:
   - Takes multiple features as input (e.g., customer details such as age, balance, credit score, etc.).
   
2. **Hidden Layers**:
   - **First Hidden Layer**: Fully connected layer with a specific number of neurons, activation function: ReLU.
   - **Second Hidden Layer**: Fully connected layer with a specific number of neurons, activation function: ReLU.
   
3. **Output Layer**:
   - A single neuron with a sigmoid activation function, outputting the probability of churn (1 for churn, 0 for no churn).

## Live Version

You can access the live version of the churn prediction model here: [Live Version - Churn Prediction](https://app-churn-ann.streamlit.app/)

## Summary of Model Layers

- **Input Layer**: Receives the feature set.
- **Hidden Layer 1**: Fully connected, ReLU activation.
- **Hidden Layer 2**: Fully connected, ReLU activation.
- **Output Layer**: Single neuron, sigmoid activation.


