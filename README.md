# **Titanic Survival Analysis**

## **📌 Project Overview**

This project implements a **Machine Learning–based classification system** to predict passenger survival on the Titanic. By analyzing historical data, the project identifies key factors that influenced survival rates and trains multiple models to classify passengers as survivors or non-survivors.

The analysis includes comprehensive Exploratory Data Analysis (EDA), data preprocessing, feature engineering, and model evaluation.

## **🚀 Features**

* **Data Cleaning:** Handling missing values and inconsistencies in the dataset.  
* **Exploratory Data Analysis (EDA):** Visualizing survival rates (e.g., Pie Charts) and relationships between features like class, gender, and age.  
* **Feature Engineering:** One-Hot Encoding for categorical variables and Standard Scaling for numerical features.  
* **Model Training:** Implementation of multiple classification algorithms.  
* **Evaluation:** Comparing model performance using accuracy metrics.

## **🛠️ Tech Stack**

The project is built using Python and the following data science libraries:

* **Pandas:** Data manipulation and analysis.  
* **NumPy:** Numerical operations.  
* **Matplotlib & Seaborn:** Data visualization.  
* **Scikit-learn:** Machine learning modeling, preprocessing, and evaluation.

## **📂 Project Structure**

The analysis is contained within a Jupyter Notebook (Titanic Survival Analysis.ipynb) which follows this workflow:

1. **Library Import:** Loading necessary Python packages.  
2. **Data Loading:** Reading the Titanic dataset.  
3. **EDA:** Visualizing the distribution of target variables (Survival) and features.  
4. **Preprocessing:**  
   * Splitting data into training and testing sets.  
   * Applying StandardScaler to numerical columns.  
   * Applying OneHotEncoder to categorical columns using ColumnTransformer.  
5. **Model Implementation:**  
   * Logistic Regression  
   * Decision Tree Classifier  
   * Random Forest Classifier  
6. **Performance Analysis:** Evaluating models based on accuracy and other metrics.

## **⚙️ How to Run**

1. **Clone the repository:**  
   git clone \[https://github.com/tirthzz-ctrl/Titanic-Survival-Analysis.git\](https://github.com/tirthzz-ctrl/Titanic-Survival-Analysis.git)

2. **Install dependencies:**  
   Ensure you have Python installed, then run:  
   pip install pandas numpy matplotlib seaborn scikit-learn

3. **Launch the Notebook:**  
   jupyter notebook "Titanic Survival Analysis.ipynb"

4. **Execute Cells:** Run the cells sequentially to reproduce the analysis and model results.

## **📊 Models Used**

The project explores the following algorithms to determine the best predictor:

* **Logistic Regression:** A baseline model for binary classification.  
* **Decision Tree:** Captures non-linear relationships in the data.  
* **Random Forest:** An ensemble method to improve accuracy and reduce overfitting.

## **🤝 Contributing**

Contributions are welcome\! If you have suggestions for improving model accuracy or adding new visualizations, feel free to fork the repo and create a pull request.

## **📜 License**

This project is open-source and available for educational purposes.
