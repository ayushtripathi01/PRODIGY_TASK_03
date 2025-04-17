# PRODIGY_TASK_03
This project implements a Decision Tree Classifier using scikit-learn, The dataset is split into training and testing sets to assess accuracy. The project demonstrates the effectiveness of decision trees in classification tasks.

Importing Required Libraries
pandas, numpy for data handling
sklearn for model building
matplotlib, seaborn for visualization

Data Collection & Loading
Used [dataset name, e.g., banking marketing / any other]
Loaded using pandas.read_csv()

Data Preprocessing
Handled missing values (if any)

Label encoding or one-hot encoding (for categorical variables)

Feature selection (based on correlation or domain knowledge)

Splitting the Dataset
Used train_test_split() to divide data into training and testing sets

Model Training
Initialized and trained a DecisionTreeClassifier from sklearn.tree

Model Evaluation

Accuracy score

Confusion Matrix

Classification Report

Model Visualization
Visualized the decision tree using plot_tree() from sklearn.tree

Experimented with parameters like max_depth, criterion, min_samples_split

Saving the Model (optional)

Used joblib or pickle to save the trained model

Conclusion

Final observations and accuracy achieved were recorded
