Detailed Project Report: Predictive Model for Medical Charges
Hugging Face Deployment URL: https://huggingface.co/spaces/mahwishH/MLPORTFOLIO
docler URL: https://github.com/mahwishch/portfolio-Project-..Machine-Learning-Pipeline.git

1. Project Overview
The aim of this project is to build and deploy a predictive model to estimate medical charges based on various personal attributes such as age, BMI, smoking status, and region. The project involves several stages, including data preprocessing, model development, API creation, and deployment with a user interface.

2. Objectives
Primary Goal: Develop a predictive model using linear regression and random forest algorithms to estimate individual medical charges.
Deployment: Create a FastAPI application to serve the model and a Gradio UI for user interaction, deployed on Hugging Face Spaces.
3. Challenges
Data Handling:

Mixed data types: Numerical and categorical data required preprocessing and encoding.
Data quality: Handling missing values and outliers.
Feature Engineering:

Encoding categorical variables (e.g., sex, smoker, region) for model compatibility.
Standardizing numerical features (e.g., age, BMI, children, charges).
Model Selection and Evaluation:

Choosing the right machine learning models.
Evaluating model performance using appropriate metrics.
4. Methodology
4.1 Data Preprocessing
Handling Missing Data: Addressed any missing values in the dataset.
Encoding Categorical Variables: Transformed categorical variables into numerical formats using one-hot encoding.
Standardizing Numerical Features: Scaled numerical features to a standard range.
4.2 Exploratory Data Analysis (EDA)
Variable Distributions: Analyzed the distribution of key variables such as age, BMI, and charges.
Feature Relationships: Investigated the relationships between features and the target variable (medical charges).
4.3 Model Development
Data Splitting: Divided the dataset into training (70%) and testing (30%) sets.

Model Implementation:

Linear Regression: Developed and trained a linear regression model.
Random Forest: Developed and trained a random forest model.
Model Evaluation:

Linear Regression: Evaluated using R-squared and Mean Squared Error.
Random Forest: Evaluated using accuracy.
4.4 FastAPI Application
API Creation: Developed a FastAPI application to serve the trained model.
Endpoint Implementation: Created an endpoint to accept input data, use the model for predictions, and return the results.
4.5 Deployment
Gradio UI: Developed a user interface using Gradio to interact with the FastAPI endpoint.
Hugging Face Deployment: Deployed the Gradio application on Hugging Face Spaces for public access.
5. Solutions and Outcomes
Data Preprocessing: Successfully handled missing data, encoded categorical variables, and standardized numerical features.
EDA Insights: Revealed key insights, including the significant impact of smoking on medical charges.
Model Performance:
Linear Regression: Explained 77% of the variance in medical charges (R-squared = 0.77).
Random Forest: Achieved an accuracy of 86%, showing better performance compared to linear regression.
6. Model Accuracy
Linear Regression: R-squared = 77%
Random Forest: Accuracy = 86%
7. FastAPI Setup
FastAPI Application:

Created an API to serve the model and handle predictions.
Implemented error handling and data validation.
Uvicorn: Used Uvicorn as the ASGI server to run the FastAPI application.

8. Deployment
Gradio UI: Developed a user-friendly interface for model interaction.
Hugging Face Spaces: Deployed the application on Hugging Face Spaces for accessible, public deployment.
9. Usage
FastAPI Server: Launch the server to enable the model for predictions.
Gradio Interface: Access the Gradio application through the provided Hugging Face URL to interact with the model.
10. Additional Notes
Ensure all required libraries and dependencies are installed (fastapi, uvicorn, gradio, joblib, requests).
Place the model file (my_model.pkl) in the correct directory for the FastAPI application to load properly.
11. Future Work
Explore more complex models or techniques to improve predictive accuracy.
Integrate additional features or external data sources for enhanced predictions.

