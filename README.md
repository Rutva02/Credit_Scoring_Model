# Credit Scoring Model

## Project Overview
This project uses Machine Learning classification algorithms to predict an individual's creditworthiness based on financial and personal information.

The model classifies applicants into two categories:
- Good Credit
- Bad Credit

## Dataset
- **Dataset:** German Credit Dataset
- **Source:** UCI Machine Learning Repository
- **Total Records:** 1,000
- **Original Features:** 20
- **Target Classes:** Good Credit and Bad Credit

## Technologies Used
- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib

## Machine Learning Algorithms
1. Logistic Regression
2. Decision Tree Classifier
3. Random Forest Classifier
4. Tuned Logistic Regression

## Project Workflow
1. Data collection and loading
2. Exploratory Data Analysis
3. Data preprocessing
4. Feature engineering
5. Train-test splitting
6. Model training
7. Model evaluation
8. Hyperparameter tuning
9. Model comparison
10. Final model selection and saving

## Final Model Performance

The tuned Logistic Regression model was selected as the final model.

| Metric | Score |
|---|---:|
| Accuracy | 72.50% |
| Precision | 52.81% |
| Recall | 78.33% |
| F1 Score | 63.09% |
| ROC-AUC | 80.94% |

## Project Files
- `Credit_Scoring_Model.ipynb` – Complete project code and analysis.
- `credit_scoring_model.pkl` – Saved trained Machine Learning model.
- `credit_scoring_model_comparison.csv` – Model performance comparison.

## How to Run
1. Download or clone this repository.
2. Open `Credit_Scoring_Model.ipynb` using Google Colab or Jupyter Notebook.
3. Install the required Python libraries if necessary.
4. Run the notebook cells in sequence.

## Conclusion
The project demonstrates how Machine Learning classification algorithms can be used for credit risk prediction. After comparing multiple algorithms and performing hyperparameter tuning, Tuned Logistic Regression was selected based on its overall evaluation results.

## Disclaimer
This project is developed for educational and internship purposes only. Its predictions should not be used as the sole basis for real-world financial or lending decisions.
