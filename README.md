 **Obesity Classification Project**

This project classifies obesity levels in individuals based on their personal, dietary, and lifestyle attributes. Using machine learning, it identifies patterns in the data and evaluates multiple classification models to determine the most accurate predictors.

 **Project Description**
This project aims to predict obesity levels using data preprocessing, exploratory data analysis, and machine learning. The dataset includes information about individuals’ health metrics and habits, enabling the development of predictive models for obesity classification.

Key tasks include:
- Data cleaning and preprocessing
- Exploratory data analysis (EDA)
- Training and evaluating machine learning models
- Visualizing results and metrics

## **Features**
- **Data Preprocessing**:
  - Handles missing values, encodes categorical data, and scales numerical features.
- **EDA Visualizations**:
  - Gender-based obesity analysis, eating habits, and physical activity trends.
- **Model Evaluation**:
  - Tests multiple classifiers for accuracy and performance metrics.
- **Pipeline Integration**:
  - Combines preprocessing and modeling for streamlined execution.


## **Models Used**
This project uses the following machine learning algorithms:
- **K-Nearest Neighbors (KNN)**
- **Support Vector Classifier (SVC)**
- **Decision Trees**
- **Random Forest**
- **AdaBoost**
- **Gradient Boosting**
- **Stochastic Gradient Descent (SGD)**

The models are evaluated on accuracy and their ability to classify obesity levels effectively.


## **Dataset**
The dataset `ObesityDataSet_raw_and_data_sinthetic.csv` includes:
- **Features**: Age, Gender, Height, Weight, physical activity frequency, eating habits, and more.
- **Target Variable**: Obesity level, with categories such as:
  - Normal weight
  - Overweight
  - Obesity Type I, II, III
  - Insufficient weight
## **Installation**

1. **Clone the Repository**:
   ```bash
   git clone <repository-url>
   cd Obesity_Classification

   Install Dependencies: Make sure you have Python installed, then run:

bash

pip install -r requirements.txt
python Obesity_Classification.py
