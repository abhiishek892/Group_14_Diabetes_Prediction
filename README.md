# Group_14_Diabetes_Prediction

Overview
This project involves data analysis and prediction related to health metrics (such as diabetes prediction) using machine learning. It uses Python with libraries like `pandas`, `matplotlib`, and `scikit-learn` to build and evaluate a logistic regression model.

Features
- Clean and preprocess health-related data
- Visualize distribution of diabetes outcomes
- Train a logistic regression classifier
- Evaluate model accuracy and confusion matrix
- Show feature importance to understand key health indicators

Libraries Used
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

Logistic Regression:
Used for binary classification — predicting whether something belongs to Class 0 or Class 1 (e.g., diabetes: yes or no).
How It Works:
1.Takes input features (like age, glucose level, BMI).
2.Applies a linear equation to compute a value z:
              𝑧=w1x1+w2x2+......+wnxn+b
3.Uses the sigmoid function to convert z into a probability:
                    Sigmoid(z) = 1/(1+e^-z)
4.If probability ≥ 0.5, predict Class 1
  If probability < 0.5, predict Class 0

Why Use It?
1.Simple and fast
2.Works well for linearly separable data
3.Gives probabilities, not just labels

Loss Function:
  Uses binary cross-entropy to measure error and adjust weights during training.

![Screenshot 2025-05-27 112741](https://github.com/user-attachments/assets/7d9f7986-9f9c-493e-b1a3-edec1ee4372e)

![Screenshot 2025-05-27 112757](https://github.com/user-attachments/assets/2ebaaa50-344a-4f11-a8b3-f21c8fd7085c)

![Screenshot 2025-05-27 112805](https://github.com/user-attachments/assets/bfb9f674-7ccd-4c85-a23a-359d61b5afe4)

![Screenshot 2025-05-27 112920](https://github.com/user-attachments/assets/59a7b79c-13a5-45de-80da-175501bee9e1)



