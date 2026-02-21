# 💰 Salary Prediction (ANN)

This repository features a Deep Learning Regression model built with TensorFlow/Keras to predict a customer's estimated salary based on demographic and banking data. The model is deployed via an interactive Streamlit web interface.

# 🔗 Live Demo
[![Open in Streamlit](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://salary-prediction-regression-ann.streamlit.app/)

![UI](/images/image.png)

## ✨ Features

* **🧠 Deep Learning Engine:** Utilizes a multi-layer Artificial Neural Network (ANN) trained on historical bank customer data.

* **⚡ Real-time Probability:** Calculates the exact probability of churn, allowing for nuanced decision-making.

* **🛠️ Advanced Preprocessing:**

     * **Label Encoding:** For binary categorical data like Gender.

     * **One-Hot Encoding:** For multi-class categorical data like Geography.

     * **Feature Scaling:** Uses StandardScaler to optimize neural network convergence.

* **📱 Interactive Dashboard:** A clean Streamlit UI for entering customer details and viewing immediate predictions.

## Skills Developed

- **Deep Learning Workflow:** Designing, training, and saving a Keras model for binary classification.

- **Pipeline Preservation:** Managing multiple transformation objects (encoders and scalers) to ensure data consistency between training and production.

- **Frontend Design:** Mapping complex data structures to user-friendly UI components.

## How it Works
1) User Input: Data is collected through Streamlit's sliders and dropdowns.

2) Transformation:
    - Categorical variables are transformed using the saved Label and One-Hot encoders.
    - The complete feature set is then normalized using the StandardScaler.
    
3) Inference: The processed array is passed to the ANN, which outputs the final estimated salary.

## 🏁 Conclusion

This project successfully demonstrates the power of Artificial Neural Networks in predicting continuous financial outcomes like salary. By integrating TensorFlow with Streamlit, the model transforms raw demographic and banking data into actionable real-time insights. The implementation highlights the importance of consistent data preprocessing—specifically scaling and categorical encoding—to ensure model accuracy during deployment. Ultimately, this tool provides a scalable framework for financial institutions to estimate customer earning potential and refine their targeted marketing strategies.