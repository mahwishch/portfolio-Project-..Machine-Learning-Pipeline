# portfolio-Project-..Machine-Learning-Pipeline
                        Medical Charges Prediction Project -

Hugging Face URL: https://huggingface.co/spaces/mahwishH/MLPORTFOLIO
Objective
The primary objective of this project was to develop a predictive model using linear regression to estimate medical charges based on personal attributes like age, BMI, smoking status, and more.

Challenges
Handling a mix of numerical and categorical variables.
Ensuring data quality and dealing with any missing or anomalous data.
Encoding categorical features to a numerical format for model compatibility.
Understanding which features are the most important in predicting medical charges.
Key Tasks
Data Preprocessing:

Handled missing or anomalous data to ensure data quality.
Encoded categorical variables such as sex, smoker, and region into numerical formats using label encoding.
Standardized numerical features such as age, BMI, and charges to make them compatible with the model.
Exploratory Data Analysis (EDA):

Analyzed key features like age, BMI, and medical charges.
Discovered that smoking status, age, and BMI were key factors influencing medical charges.
Visualizations like scatter plots and correlation matrices were used to identify important relationships.
Model Development:

The dataset was split into a training set (70%) and a testing set (30%).
A linear regression model was implemented using Scikit-learn.
The model was evaluated based on R-squared (R²) and Mean Squared Error (MSE).
Solutions and Outcomes
Used Python libraries such as Pandas, Matplotlib, and Scikit-learn to process the data and develop the model.
Successfully cleaned and transformed the data, including encoding categorical variables and standardizing numerical features.
Conducted comprehensive Exploratory Data Analysis (EDA), revealing that smoking status, age, and BMI were significant predictors of medical charges.
Developed a linear regression model that explains approximately 77% of the variance in medical charges (R² = 0.77).
The Mean Squared Error (MSE) of the model was approximately 0.27, indicating reasonable accuracy in predictions.
Conclusion
The project successfully demonstrated the application of linear regression in predicting medical charges based on demographic and health-related attributes.
Key findings: Smoking status, age, and BMI are significant predictors of medical charges.
Future work could involve exploring more complex models or additional techniques, such as regularization or tree-based models, to further improve predictive accuracy.
