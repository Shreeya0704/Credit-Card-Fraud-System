Credit Card Fraud Detection System

Project Description

The Credit Card Fraud Detection System is designed to identify fraudulent credit card transactions using machine learning techniques. This project aims to develop a model that can differentiate between legitimate and fraudulent transactions based on historical data.

Dataset
The dataset used in this project contains transactions made by credit cards in September 2013 by European cardholders. This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, with the positive class (frauds) accounting for 0.172% of all transactions.

Installation

To run this project, you need to have Python and Jupyter Notebook installed. The required libraries can be installed using the following command:

pip install -r requirements.txt

The requirements.txt file should include the following libraries:

numpy

pandas

matplotlib

seaborn

scikit-learn

Usage

Clone the repository to your local machine, navigate to the project directory, and open the Jupyter Notebook using the command jupyter notebook CREDIT_CARD_FRAUD_DETECTION_SYSTEM.ipynb. Run the cells in the notebook sequentially to train and evaluate the model.

Methodology

The methodology of this project includes several key steps. First, during data preprocessing, the dataset is loaded and understood, missing values (if any) are handled, and data normalization and scaling are performed. Next, exploratory data analysis (EDA) is conducted to visualize the distribution of the classes, analyze the correlation between features, and plot various graphs to better understand the data. In the model building phase, the data is split into training and testing sets, and various machine learning models (e.g., Logistic Regression, Decision Tree, Random Forest, etc.) are trained. Hyperparameter tuning is then performed to optimize the models. Finally, during model evaluation, the models are assessed using appropriate metrics such as accuracy, precision, recall, F1-score, and ROC-AUC, and the best-performing model is selected.

Results

The final model achieved a notable performance in detecting fraudulent transactions. The model demonstrated high precision and recall, indicating its effectiveness in identifying fraud. The exact accuracy and ROC-AUC score can be found by running the evaluation cells in the provided Jupyter Notebook.

Contributing

Contributions to this project are welcome. If you have any suggestions or improvements, feel free to create a pull request or open an issue.

