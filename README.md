## Supplier Class Forecast Project (Machine Learning)

**Package:** numpy, pandas, matplotlib, tensorflow, keras

**Business Goal:** Using CycNorm(Normalization of Cycletime), DefNorm(Normalization of DefactRate), and CosNorm(Normalization of Cost) to predict the class level(Gold, Silver, Tin, Platuinum)

### Model Deployment
Deep neural networks learn by adjusting the strengths of their connections to better convey input signals through multiple layers
In this project, I utilized the Keras package to design and implement deep neural network models, experimenting with various layers and dense units to optimize accuracy.

## Complie Model
Visualized a bar chart for each training data point. A blue bar represents a correct prediction, while a red bar indicates an incorrect prediction made by the model.

![image](https://github.com/user-attachments/assets/6f95c89b-5635-437e-86f8-daafdfbfc948)

## Model Evaluation
Created confusion_matrix to understand the accuracy and sensitivity

## Model Prediction
Developed arrays for CycNorm, DefNorm, and CosNorm to scale values between 0 and 1, improving future predictions.
