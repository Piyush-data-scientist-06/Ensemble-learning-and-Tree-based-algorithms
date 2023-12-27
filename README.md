# Ensemble-learning-and-Tree-based-algorithms:
## Objective: 
To understand and implement various tree-based algorithms and ensemble methods (Decision trees, Bagging, Random Forest, Gradient Boosting), evaluate their performance, and interpret their results.
## Dataset selection:
- Credit Card Fraud Detection dataset chosen from Kaggle.
- The datasets contain transactions made by credit cards in September 2013 by European cardholders.
- This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions.
- The Credit Card Fraud Detection dataset is a collection of transactions made by credit cards, where the task is to classify each transaction as fraudulent or legitimate, characterized by a highly imbalanced distribution of the two classes.
## Modeling (Tasks performed):
**Part 1: Decision Trees**
1. Dataset Selection: Choose a dataset suitable for classification. 
2. Data Exploration: Conduct a brief exploratory data analysis (EDA) to understand the dataset's features and target variables.
3. Decision Tree Implementation: Train a decision tree classifier. Visualize the tree and interpret the results.
4. Evaluation: Use appropriate metrics (e.g., accuracy, precision, recall, F1-score) to evaluate the model's performance on a test set. <br>

**Part 2: Bagging**
1. Bootstrap Sampling: From the dataset used in Part 1, create 10 bootstrap samples.
2. Model Training: Train a decision tree on each bootstrap sample.
3. Aggregation: Aggregate predictions from all trees to make the final prediction.
4. Evaluation: Compare the bagging ensemble's performance against the single decision tree from Part 1. <br>

**Part 3: Random Forest**
1. Model Implementation: Train a Random Forest classifier on the dataset.
2. Feature Importance: List the top 5 features based on their importance.
3. Evaluation: Compare the Random Forest's performance against the models from previous parts. <br>

**Part 4: Gradient Boosting**
1. XGBoost Implementation: Train an XGBoost classifier. Adjust hyperparameters like learning_rate, max_depth, and n_estimators.
2. Feature Importance with XGBoost: Identify and visualize the importance of features in the trained model.
3. Evaluation: Compare the XGBoost model's performance against the other models. <br>

**Part 5: Comparative Analysis**
1. Performance Metrics: Tabulate the performance metrics (accuracy, precision, recall, F1-score) of all models side by side. <br>

## Performance Observations:

![image](https://github.com/Piyush061990/Ensemble-learning-and-Tree-based-algorithms/assets/134443316/b126cbea-2e1f-4fa1-b1f8-53ffb9e13491)

Each model has its strengths and weaknesses. Simpler models like Decision Trees are highly interpretable, whereas complex models like XGBoost provide superior accuracy and balance across metrics, making them more suitable for nuanced tasks like fraud detection.
