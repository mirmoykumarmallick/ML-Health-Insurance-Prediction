# Health Insurance Premium Prediction Using Machine Learning

This project aims to predict health insurance premiums based on various factors such as age, BMI, smoking status, number of children, and geographic region. By utilizing different machine learning models, including Linear Regression, Random Forest, and XGBoost, we can achieve accurate predictions and gain insights into the influencing factors of insurance costs.

## Project Overview

The repository contains a Jupyter Notebook that demonstrates the end-to-end machine learning workflow, including data preprocessing, exploratory data analysis (EDA), model building, evaluation, and visualization. The models are assessed using performance metrics like R-squared and RMSE to compare their effectiveness.

## Features

- **Data Preprocessing**: Handles categorical variables using one-hot encoding and scales numerical features.
- **Exploratory Data Analysis (EDA)**: Visualizes data relationships through heatmaps, distribution plots, and box plots.
- **Modeling**: Implements Linear Regression, Random Forest, and XGBoost models.
- **Model Comparison**: Compares the performance of models based on R-squared and RMSE scores.
- **Hyperparameter Tuning**: Optimizes model performance using hyperparameter tuning.
- **Visualizations**: Colorful and intuitive visualizations for data and model performance.

## Technologies Used

- Python
- Pandas
- Scikit-learn
- Seaborn
- Matplotlib
- XGBoost
- Google Colab

## Dataset

The dataset used in this project is a health insurance dataset that contains the following features:
- `age`: Age of the insured.
- `sex`: Gender of the insured.
- `bmi`: Body Mass Index.
- `children`: Number of children/dependents covered by health insurance.
- `smoker`: Smoking status (yes/no).
- `region`: Geographic region of the insured.
- `charges`: The insurance premium.

## How to Use

1. **Clone this Repository**:
   ```bash
   git clone <https://github.com/mirmoykumarmallick/ML-Health-Insurance-Prediction>
2. **Open the Notebook**:
   - Navigate to the cloned directory and open the .ipynb file in Google Colab or Jupyter Notebook.
     
3. **Install Dependencies: If running locally, make sure to install the required libraries**:
   ```bash
   pip install pandas seaborn scikit-learn xgboost
   
4. **Run the Code**:
   - Follow the steps in the notebook to load the data, preprocess it, and build machine learning models.
   - Analyze the performance of different models and visualize the results.
     
5. **Explore Further**:
   - Feel free to experiment with hyperparameter tuning and adding new features for better predictions.
     
## Results
- The Random Forest and XGBoost models significantly outperform the Linear Regression model in terms of prediction accuracy.
- Key insights reveal that smoking status, BMI, and age are the most significant factors influencing insurance premiums.
  
## License
- This project is licensed under the MIT License - see the LICENSE file for details.
  
## Author
- Mirmoy Kumar Mallick
- LinkedIn Profile: linkedin.com/in/mirmoy-kumar-mallick
- Email: mirmoykumarmallick10@gmail.com
