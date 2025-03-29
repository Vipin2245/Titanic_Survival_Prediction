# Titanic Survival Prediction

This project analyzes the Titanic dataset and builds a machine learning model to predict passenger survival based on available features.

## Objectives
- Load and preprocess the Titanic dataset.
- Perform exploratory data analysis (EDA) using visualizations.
- Handle missing data and feature encoding.
- Train and evaluate a Random Forest classifier to predict survival.

## Requirements
Ensure you have the following Python libraries installed:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn
```

## Steps to Run the Project
1. **Download Dataset:** Place `tested.csv` in the project directory.
2. **Run the Notebook:** Open `Titanic.ipynb` in Jupyter Notebook or Google Colab.
3. **Execute Cells:** Run all cells sequentially to process the data, perform EDA, and train the model.
4. **Check Results:** The notebook prints model accuracy and a classification report.

## Output
- The model's accuracy score.
- A classification report detailing precision, recall, and F1-score.

## Notes
- The dataset must be available in the project directory for the notebook to function correctly.
- Feature engineering includes handling missing values and encoding categorical variables.
- The trained model is a Random Forest classifier with 100 estimators.

