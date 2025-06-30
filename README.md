# AIML-DAY5
# 🧠 AI/ML Practice: Decision Trees & Random Forests

This project explores tree-based classification models using a heart disease dataset. It is a hands-on AI/ML practice task involving data preprocessing, model training, evaluation, and visualization.

## 🔍 Objective
To understand how decision trees and random forest classifiers work, analyze their performance, and visualize important features.

## 📁 Dataset
The dataset used is a heart disease dataset (`heart.csv`) extracted from an uploaded ZIP file.

## 🧰 Tools & Libraries
- Python (Pandas, NumPy)
- Scikit-learn
- Matplotlib, Seaborn
- Graphviz

## 📌 Workflow
1. **Data Loading & Preprocessing**  
   Extracted the dataset, handled features, and prepared train-test split.

2. **Model Training**  
   - Trained a Decision Tree Classifier with controlled depth.
   - Trained a Random Forest Classifier for comparison.

3. **Evaluation**  
   - Used accuracy score and classification report.
   - Performed 5-fold cross-validation for both models.

4. **Visualization**  
   - Visualized the Decision Tree using Graphviz.
   - Plotted feature importances from the Random Forest model.

## 📊 Results
- **Decision Tree Accuracy**: ~82%
- **Random Forest Accuracy**: ~89%
- Random Forest performed better in both accuracy and generalization.
- Top features identified include chest pain type and maximum heart rate.

## 💡 Key Concepts Practiced
- Decision Tree structure and entropy-based splitting
- Overfitting control via max depth
- Random Forest and bagging principles
- Cross-validation evaluation
- Feature importance analysis
