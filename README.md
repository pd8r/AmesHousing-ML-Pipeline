# AmesHousing End-to-End ML & Data Pipeline

This project demonstrates a complete, reproducible data engineering and machine learning pipeline built to predict housing prices using the Ames Housing dataset. The focus of this project is heavily placed on rigorous data preprocessing, feature engineering, and robust model evaluation.

## 🛠️ Tech Stack & Tools
* **Language:** Python 3.13
* **Libraries:** Pandas, NumPy, Scikit-Learn
* **Environment:** Jupyter Notebook / Google Colab

## ⚙️ Data Pipeline Architecture & Features

The pipeline processes raw data through the following key stages to ensure data quality and model readiness:

1. **Exploratory Data Analysis (EDA):** Analyzed variable distributions, checked for missing values, and performed correlation analysis to identify key features.
2. **Data Cleaning & Preprocessing:**
   * Handled missing values systematically across numerical and categorical features.
   * Detected and treated statistical outliers to prevent model distortion.
   * Applied feature scaling using `StandardScaler` and `RobustScaler` depending on outlier presence.
3. **Feature Engineering:**
   * Encoded categorical variables using appropriate encoding techniques.
   * Applied **Log Transformations** to highly skewed numerical variables to normalize distributions.
4. **Model Selection & Evaluation:**
   * Trained and evaluated multiple regression algorithms, including Linear Regression, Random Forests, Gradient Boosting, XGBoost, and LightGBM.
   * Utilized **Mean Squared Error (MSE)** as the primary metric for hyperparameter tuning and local evaluation.
   * Developed an ensemble blending approach to optimize final prediction accuracy.

## 📂 Project Structure
* `AmesHousing.ipynb` -> Main Jupyter Notebook containing the executable pipeline code.
* `data/` -> Directory containing the raw `train.csv` and `test.csv` datasets.
* `sample_submission.csv` -> Final generated output file matching production requirements.

## 🚀 How to Run
1. Clone the repository: `git clone https://github.com/pd8r/AmesHousing-ML-Pipeline.git`
2. Install dependencies: `pip install pandas numpy scikit-learn jupyter`
3. Open the notebook: `jupyter notebook`
