# Heart Disease Assessment Model

## Objective
The objective of this project is to create a model that assesses the risk of heart disease based on basic patient data. The project will start by using simple regression techniques to predict the likelihood of heart disease. An advancement of this project includes using deep learning methods to develop a more robust model for assessing heart disease risk based on the same patient data.

## Data Required
To build and validate our models, the following patient data will be required:

- **Age:** Patient's age in years.
- **Sex:** Patient's gender (0 = female, 1 = male).
- **Chest_Pain_Type:** Type of chest pain experienced (0 = typical angina, 1 = atypical angina, 2 = non-anginal pain, 3 = asymptomatic).
- **Resting_bp_s:** Resting blood pressure (in mm Hg).
- **Cholesterol:** Serum cholesterol level in mg/dl.
- **Fasting_blood_Sugar:** Fasting blood sugar (0 = < 120 mg/dl, 1 = > 120 mg/dl).
- **Resting_ecg:** Resting electrocardiographic results (0 = normal, 1 = ST-T wave abnormality, 2 = probable/definite left ventricular hypertrophy).
- **Max_heart_rate:** Maximum heart rate achieved during exercise.
- **Exercise_angina:** Exercise-induced angina (0 = No, 1 = Yes).
- **Oldpeak:** ST depression induced by exercise relative to rest.
- **ST_slope:** Slope of the peak exercise ST segment (0 = upsloping, 1 = flat, 2 = downsloping).
- **Target:** Presence of heart disease (0 = No, 1 = Yes).

## Potential Outcome
The primary outcome of this project is to develop a predictive model that can accurately assess the risk of heart disease. This model will aid in early detection and support preventive healthcare planning.

## Report
For a detailed report on the project, including methodology, analysis, and conclusions, please refer to the full report available [here](https://docs.google.com/document/d/1Jt6RywyD9YCvIIcezEJz1pjR-1z9-R56Ws_B3oGQuqM/edit?usp=sharing).


## Resources

### Datasets
- **[Heart Disease Dataset on IEEEDataPort](https://ieee-dataport.org/open-access/heart-disease-dataset-comprehensive):**
  A comprehensive dataset that combines five popular heart disease datasets over 11 common features, making it one of the largest datasets available for heart disease research.

- **[Heart Disease Dataset on Kaggle](https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset):**
  This dataset, dating from 1988, includes four databases: Cleveland, Hungary, Switzerland, and Long Beach V. It contains 76 attributes, though most published experiments use a subset of 14 features. The "target" field indicates the presence of heart disease.

- **[Cardiovascular Disease Dataset on Kaggle](https://www.kaggle.com/datasets/sulianova/cardiovascular-disease-dataset):**
  A dataset consisting of 70,000 patient records with 11 features and a target variable.

## Steps to Implement the Project

### 1. Data Collection and Preparation
- **Download the Dataset:** Obtain the dataset from the provided links.
- **Data Cleaning:** Handle missing values and encode categorical variables.
- **Feature Selection:** Select relevant features such as age, sex, chest pain type, and cholesterol levels.
- **Data Splitting:** Split the data into training and testing sets (e.g., 80% training, 20% testing).

### 2. Exploratory Data Analysis (EDA)
- **Descriptive Statistics:** Calculate mean, median, standard deviation, etc., for numerical features.
- **Data Visualization:** Use histograms, box plots, and scatter plots to visualize distributions and relationships between features.

### 3. Model Building
- **Choose a Regression Model:** Start with logistic regression for binary classification (e.g., predicting the presence of heart disease) and linear regression for risk scores.
- **Train the Model:** Fit the model on the training data.
- **Hyperparameter Tuning:** Use cross-validation to fine-tune model parameters.

### 4. Deep Learning Model
- **Model Selection:** Develop an Artificial Neural Network (ANN) to enhance the predictive capability for heart disease risk assessment.
- **Model Training:** Train the ANN using the processed dataset, experimenting with different architectures (e.g., varying the number of layers and neurons per layer).
- **Evaluation:** Compare the performance of the deep learning model against the simple regression model using metrics such as accuracy, precision, recall, F1-score, and ROC-AUC.

### 5. Model Evaluation
- **Evaluation Metrics:** For classification, use accuracy, precision, recall, F1-score, and ROC-AUC. For regression, use mean squared error (MSE) and R-squared.
- **Model Validation:** Evaluate the model on the testing set to assess generalizability.

## Rules of Engagement

### Communication:
- Maintain clear and regular communication within the team.
- Use project management tools (e.g., Trello, Slack) to track progress and issues.
- Set up a Google Doc for collaborative project documentation.

### Data Handling:
- Ensure data privacy and security at all times.
- Document all data cleaning and preprocessing steps.

### Coding Standards:
- Follow consistent coding practices and style guidelines (e.g., PEP 8 for Python).
- Write clear, concise, and well-documented code.
- Use Google Colab for collaborative coding and experimentation.

### Collaboration:
- Use version control (e.g., Git) for all code and documentation.
- Conduct regular code reviews and provide constructive feedback.

### Model Development:
- Start with simple models before moving to more complex ones.

## Project Structure
```plaintext
.
Team-Project-Part-2/
├── data/
│   ├── raw/                  # Raw data files
│   └── processed/            # Processed data files
├── reports/                  # Jupyter notebooks for simple model exploration and analysis
├── deep_learning_analysis/   # Jupyter notebooks for deep learning model exploration and analysis 
│   ├── ANN/                  # Exploration and analysis of ANN model
├── README.md                 # Project documentation
