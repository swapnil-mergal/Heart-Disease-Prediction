# Heart-Disease-Prediction
Introduction: This project uses machine learning techniques to predict the likelihood of heart disease based on medical data. The model evaluates patient attributes such as age, cholesterol levels, blood pressure, and other health metrics. Multiple algorithms are implemented and compared to find the most accurate prediction method.
Features
Preprocesses and analyzes the Cleveland Heart Disease dataset.
Implements four machine learning algorithms:
Decision Tree
Support Vector Machine (SVM)
Naive Bayes
Random Forest
Compares model performance using accuracy scores, classification reports, and confusion matrices.
Visualizes data correlations and model performance for better interpretability.
Technologies Used
Programming Language: Python
Libraries:
Data Manipulation: pandas, NumPy
Data Visualization: Matplotlib, Seaborn
Machine Learning: scikit-learn
Setup and Execution
Clone the Repository:

bash
Copy code
git clone https://github.com/your_username/heart-disease-prediction.git
cd heart-disease-prediction
Install Required Libraries:

bash
Copy code
pip install -r requirements.txt
Dataset:

Ensure the Cleveland Heart Disease dataset (Heart_disease_cleveland_new.csv) is in the project directory.
Run the Project:

Open the notebook or script in your preferred IDE or Colab.
Execute step-by-step to train models and visualize results.
Results
The project achieved the following accuracy for each model:

Decision Tree: ~75.41%
SVM: ~90.16%
Naive Bayes: ~85.25%
Random Forest: ~86.89%
SVM was the most accurate algorithm for heart disease prediction.

Visualization
Correlation Heatmap: Shows relationships between features.
Accuracy Bar Plot: Compares the performance of all models.
Future Enhancements
Add hyperparameter tuning for optimized model performance.
Implement feature selection to identify key contributing factors.
Extend the project to include other datasets or additional health metrics.
