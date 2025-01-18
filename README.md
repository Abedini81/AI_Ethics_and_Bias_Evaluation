# AI Ethics and Bias Evaluation

## Project Overview:
This project evaluates the fairness of a machine learning model trained to predict income levels based on the **Adult Income Dataset**. The focus is on identifying and mitigating biases, especially regarding gender, using fairness metrics like **Disparate Impact** and **Mean Difference**. The project also applies **Reweighing**, a bias mitigation technique, to enhance fairness across demographic groups.

## Tools and Libraries Used:
- **Python**: Primary programming language.
- **TensorFlow**: For training the machine learning model.
- **AIF360**: To compute fairness metrics and apply bias mitigation techniques.
- **Scikit-learn**: For training the logistic regression model.
- **Matplotlib & Seaborn**: For data visualization and plotting.
- **Pandas**: For data manipulation and preprocessing.

## Key Steps in the Project:
1. **Data Preprocessing**: The **Adult Income Dataset** is cleaned, categorical variables are encoded, and missing values are handled.
2. **Model Training**: A **Logistic Regression** model is trained to predict whether an individual earns more than $50,000.
3. **Fairness Evaluation**: Fairness metrics such as **Disparate Impact** and **Mean Difference** are computed to evaluate model fairness.
4. **Bias Mitigation**: The **Reweighing** technique is applied to address any biases identified during the fairness evaluation.

## Fairness Metrics:
- **Disparate Impact**: Measures the ratio of favorable outcomes for unprivileged vs. privileged groups (e.g., females vs. males).
- **Mean Difference**: Measures the average difference in predicted probabilities of earning more than $50,000 between groups.

## Bias Mitigation:
- **Reweighing**: A method that adjusts the weights of samples in the training data to ensure more equitable treatment of underrepresented groups.

## Acknowledgements:
- The **Adult Income Dataset** is sourced from the **UCI Machine Learning Repository**.
- Fairness evaluation and mitigation techniques are powered by **AIF360** and **TensorFlow Model Analysis (TFMA)**.
