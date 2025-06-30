# AIML-intern-task-5
# Heart Disease Prediction using Decision Trees and Random Forests

This project demonstrates the use of **Decision Tree** and **Random Forest** classifiers to predict heart disease using a structured dataset. It includes data preprocessing, model training, pruning, visualization, feature importance analysis, and evaluation using cross-validation.

## Dataset

The dataset used (`heart.csv`) contains 1,025 samples with 13 features and 1 target variable:
- Features include age, sex, chest pain type, cholesterol, fasting blood sugar, resting ECG, etc.
- Target: `0` (no heart disease), `1` (presence of heart disease)

## Workflow Steps

1. **Train a Decision Tree Classifier**
   - Fit a model to the training set
   - Visualize the decision tree structure

2. **Analyze Overfitting**
   - Compare train/test accuracy
   - Apply tree pruning using `max_depth`

3. **Train a Random Forest Classifier**
   - Fit an ensemble model for improved accuracy
   - Evaluate model performance

4. **Interpret Feature Importances**
   - Visualize which features most influence the prediction

5. **Evaluate using Cross-Validation**
   - Use 5-fold cross-validation to assess model generalizability

## Results

| Model                    | Test Accuracy |
| Decision Tree (unpruned) | 98.5%         |
| Decision Tree (pruned)   | 80%           |
| Random Forest            | 98.5%         |
| Random Forest CV Mean    | ~99.7%        |



