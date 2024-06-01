# KAGGLE PROJECTS

This repository contains various data science projects focusing on different datasets and machine learning tasks. Each project includes data preprocessing, exploratory data analysis, model training, and evaluation.


1. [KaggleX Skill Assessment Challenge](#kagglex-skill-assessment-challenge)
2. [Liver Disease Prediction in India](#liver-disease-prediction-in-india)
3. [Recipe for Rating: Predict Food Rating Using ML](#recipe-for-rating-predict-food-rating-using-ml)

### KaggleX Skill Assessment Challenge

This project involves predicting the price of used cars based on various features such as brand, model, fuel type, transmission, and more.

#### Files
- `train.csv`: Training dataset
- `test.csv`: Test dataset

#### Steps
1. **Data Loading and Exploration**:
   - Load data and inspect for missing values and data types.
   
2. **Data Preprocessing**:
   - Convert categorical variables into numerical ones using one-hot encoding.
   - Handle missing values using median imputation.
   - Extract numerical values from text (e.g., horsepower from the engine description).
   
3. **Model Training and Evaluation**:
   - Split the data into training and validation sets.
   - Train multiple models: Linear Regression, Random Forest, and Gradient Boosting.
   - Evaluate models using RMSE (Root Mean Squared Error).

4. **Prediction**:
   - Preprocess the test data and use the best-performing model to make predictions.
   - Prepare the submission file for Kaggle.

### Liver Disease Prediction in India

This project focuses on predicting liver disease presence using a dataset of Indian patient records.

#### Files
- `indian_liver_patient.csv`: Dataset containing patient records.

#### Steps
1. **Data Loading and Exploration**:
   - Load data and inspect for missing values and duplicates.
   - Visualize distributions of various features.

2. **Data Preprocessing**:
   - Handle missing values using backfill method.
   - Convert categorical variables into numerical ones (e.g., Gender).
   - Apply Min-Max scaling to normalize the features.

3. **Exploratory Data Analysis**:
   - Analyze correlations between features.
   - Identify key features indicative of liver disease.

4. **Model Training and Evaluation**:
   - Split the data into training and testing sets.
   - Standardize features using StandardScaler.
   - Train multiple classifiers: Logistic Regression, Decision Tree, Gradient Boosting, Random Forest, SVM, Naive Bayes, KNN, and Neural Network.
   - Evaluate models using accuracy and classification reports.

5. **SMOTE and Gender-Specific Analysis**:
   - Apply SMOTE to handle class imbalance.
   - Conduct separate analyses for male and female patients.

### Recipe for Rating: Predict Food Rating Using ML

This project aims to predict food ratings based on various recipe features using machine learning techniques.

#### Files
- Dataset files (specific paths not provided).

#### Steps
1. **Data Loading and Exploration**:
   - Load data and inspect for missing values and data types.

2. **Data Preprocessing**:
   - Handle missing values and convert categorical variables.
   - Normalize and scale features as needed.

3. **Model Training and Evaluation**:
   - Split the data into training and testing sets.
   - Train multiple models and evaluate their performance.
   - Models include: Linear Regression, Decision Trees, Random Forest, Gradient Boosting, SVM, and more.

4. **Feature Engineering**:
   - Explore feature importance and engineer new features if necessary.
   - Optimize model parameters using techniques like Grid Search.

5. **Prediction and Submission**:
   - Make predictions using the best-performing model.
   - Prepare submission files as required.

## Usage

1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/datascience-projects.git
   ```

2. Navigate to the project directory:
   ```sh
   cd datascience-projects
   ```

3. Install the required dependencies:
   ```sh
   pip install -r requirements.txt
   ```

4. Run the notebooks:
   ```sh
   jupyter notebook
   ```

## License

This repository is licensed under the MIT License.

## Acknowledgments

- Kaggle for providing the datasets and competition platforms.
- Contributors and reviewers for their valuable feedback.

---

This README file provides an overview of each project, guiding users on how to replicate the analysis and predictions. Adjust the repository name, paths, and other specific details according to your actual setup.
