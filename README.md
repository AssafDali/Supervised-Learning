# 🚢 Titanic Survival Prediction - Machine Learning Pipeline

## 📌 Project Overview
This project implements an end-to-end Machine Learning pipeline to predict passenger survival on the Titanic. The solution demonstrates a complete data science workflow: from Exploratory Data Analysis (EDA) and Feature Engineering to Model Selection and Hyperparameter Tuning.

The goal was to build a robust classifier that identifies survival probabilities based on features such as passenger class, age, gender, and family size.

## 🛠️ Tech Stack
* **Language:** Python 3.x
* **Libraries:** Pandas, NumPy, Scikit-Learn, Seaborn, Matplotlib
* **Tools:** Jupyter Notebook

## 🚀 Key Features
* **Advanced Feature Engineering:**
    * Created new features like `FamilySize` and `FarePerPerson` to capture hidden patterns.
    * Categorical encoding for `Sex` and `Embarked`.
    * Imputation strategies for missing values in `Age` and `Fare`.
* **Scikit-Learn Pipelines:** Utilized `Pipeline` to streamline preprocessing and modeling, ensuring clean and leak-free code.
* **Model Selection & Tuning:**
    * Compared **Logistic Regression** vs. **Random Forest Classifier**.
    * Performed **GridSearchCV** with 5-fold Cross-Validation to optimize hyperparameters.
* **Visualizations:** Comprehensive EDA using Seaborn to understand data distributions and correlations.

## 📊 Workflow
1.  **Data Loading & Cleaning:** Handling missing values and data types.
2.  **Exploratory Data Analysis (EDA):** Visualizing survival rates by gender, class, and age distributions.
3.  **Preprocessing:** Scaling numerical features and encoding categorical variables.
4.  **Modeling:**
    * *Baseline:* Logistic Regression.
    * *Advanced:* Random Forest (Selected as the best performing model).
5.  **Evaluation:** Analyzing results using Confusion Matrix, F1-Score, and Accuracy metrics.

## 📈 Results
The **Random Forest** model outperformed Logistic Regression during the cross-validation phase.
* **Best CV Score (F1 Macro):** ~0.83
* **Training Accuracy:** ~94%

## 📂 File Structure
* `Titanic_Survival_Prediction_Pipeline.ipynb`: The main notebook containing the full analysis and code.
* `titanic_train.csv` / `titanic_test.csv`: Dataset files.

## 🔧 How to Run
1.  Clone the repository:
    ```bash
    git clone [https://github.com/YourUsername/Titanic-Survival-Project.git](https://github.com/YourUsername/Titanic-Survival-Project.git)
    ```
2.  Install dependencies:
    ```bash
    pip install pandas numpy scikit-learn seaborn matplotlib
    ```
3.  Open the Jupyter Notebook:
    ```bash
    jupyter notebook Titanic_Survival_Prediction_Pipeline.ipynb
    ```

---
*Created by [Your Name]*
