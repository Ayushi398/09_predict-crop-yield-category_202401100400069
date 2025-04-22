# 09_predict-crop-yield-category_202401100400069
This project uses machine learning to classify crop yield levels (low, medium, high) based on features such as soil quality, rainfall, and seed type.

🔍 Problem Statement

Predicting crop yield is important for planning and increasing food production. This model helps in categorizing yield levels using easy-to-collect data.

🎯 Objective

Predict crop yield category (low/medium/high)

Evaluate model performance using accuracy, precision, recall, and F1-score

Visualize predictions with a confusion matrix heatmap

📁 Dataset

The dataset includes the following features:

soil_quality (numerical)

rainfall (numerical)

seed_type (categorical: A, B, C)

yield_category (categorical target: low, medium, high)

🧹 Data Preprocessing

One-hot encoding for seed_type

Label encoding for yield_category

Train-test split (75% training, 25% testing)

🧠 Model

Algorithm: Random Forest Classifier (from scikit-learn)

Chosen for its performance with mixed data types and robustness to overfitting

📈 Evaluation Metrics

Accuracy: 48%

Precision: 52%

Recall: 48%

F1 Score: 47%

Confusion matrix and classification report show the performance of the model across each class.

📊 Visualization

A heatmap of the confusion matrix is generated to visually represent model performance.

🛠️ Technologies Used

Python

pandas, seaborn, matplotlib, scikit-learn

📌 How to Run

Load the dataset from crop_yield.csv

Run the Python script to preprocess data and train the model

View evaluation results and confusion matrix plot

✅ Conclusion

This model demonstrates how machine learning can help predict crop yields based on a few key inputs. Accuracy can improve with more data and additional features such as temperature, humidity, or soil pH.

📚 References

scikit-learn: https://scikit-learn.org/

seaborn: https://seaborn.pydata.org/

pandas: https://pandas.pydata.org/

