# Heart Disease Assessment Model

## Objective
The objective of this project is to create a model that assesses the risk of heart disease based on basic patient data. The model will use simple regression techniques to predict the likelihood of heart disease. An advancement of this project is to use deep learning methods to develop a model in order to assess the risk of heart disease based on patient data. The deep learning models include CNN and neural networks. 

## Data Required
To build and validate our model, the following patient data will be required:
- Age
- Sex 
- Chest_Pain_Type
- Resting_bp_s
- Cholesterol
- Fasting_blood_Sugar
- Resting_ecg
- Max_heart_rate
- Exercise_angina
- Oldpeak
- ST_slope
- target


## Potential Outcome
The primary outcome of this project is to develop a predictive model that can accurately assess the risk of heart disease. This model will help in early detection and preventive healthcare planning.

## Resources
### Datasets
- [Heart Disease Dataset on IEEEDataPort] (https://ieee-dataport.org/open-access/heart-disease-dataset-comprehensive)
  - This heart disease dataset is curated by combining 5 popular heart disease datasets already available independently but not combined before. In this dataset, 5 heart datasets are combined over 11 common features which makes it the largest heart disease dataset available so far for research purposes.
- [Heart Disease Dataset on Kaggle] (https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset)
  - This data set dates from 1988 and consists of four databases: Cleveland, Hungary, Switzerland, and Long Beach V. It contains 76 attributes, including the predicted attribute, but all published experiments refer to using a subset of 14 of them. The "target" field refers to the presence of heart disease in the patient. It is integer valued 0 = no disease and 1 = disease.
- [Cardiovascular Disease Dataset on Kaggle] (https://www.kaggle.com/datasets/sulianova/cardiovascular-disease-dataset)
  - The dataset consists of 70 000 records of patients data, 11 features + target.


## Project Structure
The repository is structured as follows:

Team-Project-Part-1/

├── data/
│   ├── raw/                  # Raw data files
│   └── processed/            # Processed data files
├── reports/                  # Jupyter notebooks for simple model exploration and analysis
├── deep_learning_analysis/   # Jupyter notebooks for deep learning model exploration and analysis 
    ├── CNN/                  # Exploration and analysis of CNN model
    └── .../                  # Further exploration and analysis of deep learning models
├── README.md                 # Project documentation



# Steps to Implement the Project

## 1. Data Collection and Preparation
### Download the Dataset
- Obtain the dataset from the provided [Kaggle link](https://www.kaggle.com/datasets).

### Data Cleaning
- Handle missing values.
- Encode categorical variables (e.g., gender) into numerical values.

### Feature Selection
- Select relevant features such as age, gender, BMI, blood pressure, and cholesterol levels.

### Data Splitting
- Split the data into training and testing sets (e.g., 80% training, 20% testing).

## 2. Exploratory Data Analysis (EDA)
### Descriptive Statistics
- Calculate mean, median, standard deviation, etc., for numerical features.

### Data Visualization
- Use histograms, box plots, and scatter plots to visualize the distributions and relationships between features.

## 3. Model Building
### Choose a Regression Model
- For binary classification (e.g., predicting the presence of heart disease), use logistic regression.
- For risk scores, use linear regression.

### Train the Model
- Fit the model on the training data.

### Hyperparameter Tuning
- Use cross-validation to fine-tune model parameters.

## 4. Model Evaluation
### Evaluation Metrics
- For classification: accuracy, precision, recall, F1-score, ROC-AUC.
- For regression: mean squared error (MSE), R-squared.

### Model Validation
- Evaluate the model on the testing set.


# Rules of Engagement

- **Communication**:
  - Maintain clear and regular communication within the team.
  - Use project management tools (e.g., Trello, Slack) to track progress and issues.
  - Set up a Google Doc for collaborative project documentation.

- **Data Handling**:
  - Ensure data privacy and security at all times.
  - Document all data cleaning and preprocessing steps.

- **Coding Standards**:
  - Follow consistent coding practices and style guidelines (e.g., PEP 8 for Python).
  - Write clear, concise, and well-documented code.
  - Use Google Colab for collaborative coding and experimentation.
  - https://docs.google.com/document/d/1L2cROCImqeD0IeTs_kHh-K9OchutrMf_jFZsD74gYHM/edit
  - https://colab.research.google.com/drive/1Bks9TTB_4FXTsdNo7EY4QEc96DPh5_nN?usp=sharing
      

- **Collaboration**:
  - Use version control (e.g., Git) for all code and documentation.
  - Conduct regular code reviews and provide constructive feedback.

- **Model Development**:
  - Start with simple models before moving to complex ones.

