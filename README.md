# Wine Quality Prediction using Machine Learning

This project uses machine learning to predict the quality of red wine based on various physicochemical properties such as acidity, alcohol content, pH level, and more. A **Random Forest Classifier** is used to classify wine samples into quality categories.

---

## Dataset

- **Source**: [UCI Wine Quality Dataset – Red Wine](https://www.kaggle.com/datasets/uciml/red-wine-quality-cortez-et-al-2009)
- **Features**: Fixed acidity, volatile acidity, citric acid, residual sugar, chlorides, free sulfur dioxide, total sulfur dioxide, density, pH, sulphates, alcohol
- **Target**: Wine quality score (integer between 0 and 10)

---

## Technologies Used

- Python  
- Pandas & NumPy  
- Seaborn & Matplotlib  
- scikit-learn  
- RandomForestClassifier

---

## Workflow

1. Import and explore the dataset  
2. Perform data cleaning and preprocessing  
3. Visualize feature distributions and correlations  
4. Binarize or categorize wine quality scores (optional)  
5. Train a Random Forest Classifier  
6. Evaluate performance using accuracy metrics  
7. Build a prediction system for new samples

---

## Results

- **Model Used**: Random Forest Classifier  
- **Evaluation**: Accuracy on test data (typically ~93%, depending on how quality is grouped or binarized)  
- **Classification Objective**: Predict whether a wine sample is of good or poor quality

---

## How to Run

1. Clone the repository or download the notebook  
2. Install required libraries:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
   ```bash
3. Run the notebook in Jupyter or Google Colab step-by-step

---

## Future Improvements

- Try other models (Logistic Regression, XGBoost, etc.)
- Perform hyperparameter tuning with GridSearchCV
- Convert this into a regression task (predict exact quality score)
- Build a web interface using Streamlit
- Add feature importance visualizations from the Random Forest model

--- 

## Acknowledgments

- Kaggle: Red Wine Quality Dataset
- scikit-learn and the open-source Python community
