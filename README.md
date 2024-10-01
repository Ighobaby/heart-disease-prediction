# Heart Disease Prediction Project

# Overview/Introduction
Heart disease is one of the leading causes of death worldwide. This project aims to build a machine learning model that can predict whether a person is likely to develop heart disease based on several key health metrics. The project uses various machine learning techniques to analyze patient data and predict the likelihood of heart disease, assisting healthcare professionals in making informed decisions.

# Business Problem
Early detection of heart disease can significantly improve patient outcomes by allowing for timely intervention and management. The challenge lies in accurately predicting heart disease using available patient data. In this project, we aim to build a model that helps predict the likelihood of heart disease, providing healthcare institutions with a tool to prioritize high-risk patients and focus medical resources more effectively.

# Technologies Used
The following technologies and libraries were used in this project:

    Python
        Libraries: numpy, pandas, scikit-learn, matplotlib, seaborn, pickle
    Streamlit: For deploying the model as an interactive web application.
    Git: Version control for the project.
    GitHub: For hosting the project.
    Jupyter Notebooks: For experimentation, data analysis, and model building.

  # Key Findings
    Variables like age, cholesterol levels, resting blood pressure, and thalassemia are significant predictors of heart disease.
    The models showed varying performance, with Logistic Regression and Random Forest delivering promising accuracy in predicting heart disease.
    Hyperparameter tuning, AUC-ROC curve analysis, and cross-validation revealed that the Logistic Regression model offered the best balance between interpretability and performance.

# Results and Model Evaluation
After fine-tuning the models, the key metrics achieved are as follows:

    Logistic Regression:
        Accuracy: 85%
        AUC-ROC: 0.89
    Random Forest:
        Accuracy: 84%
        AUC-ROC: 0.87

These models offer robust predictions based on the patient’s medical data.

# Model Deployment
The heart disease prediction model is deployed using Streamlit, which provides an interactive web interface where users can input medical data and get real-time predictions. The model is saved using Pickle and loaded in the Streamlit app for use in real-world scenarios.

To access the web app, clone this repository, install the required dependencies, and run the app.py file using Streamlit.

# Limitations
    Data Size: The dataset used for training is relatively small, which could limit the model's generalization to new, unseen data.
    Feature Availability: The model depends on 13 specific features for prediction. Any real-world application would need to ensure that all these features are available.
    Model Bias: The dataset may not represent a wide variety of demographics, meaning the model could perform worse on certain populations.


# Next Steps
    Larger Dataset: Collect more patient data to improve model accuracy and generalizability.
    Feature Engineering: Explore additional features such as lifestyle factors, genetic history, and mental health metrics.
    Model Optimization: Experiment with more complex models such as neural networks or boosting algorithms.
    Integration with Healthcare Systems: Collaborate with healthcare providers to integrate the model into clinical workflows and electronic health records (EHRs).

# Conclusions and Recommendations

This project demonstrates the potential for using machine learning to predict heart disease based on patient data. While the models perform well, further improvements could be made by gathering a larger dataset and refining the feature set. The tool could be highly valuable in assisting doctors and medical professionals in making timely, data-driven decisions, ultimately saving lives. It is recommended that further work be done to address the model’s limitations and enhance its practical usability in clinical settings.
