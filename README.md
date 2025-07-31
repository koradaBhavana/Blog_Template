Online Payments Fraud Detection


Abstract


Financial transactions have been changed by the exponential expansion of internet payment systems, which now offer speed and ease. But this expansion has also raised the risk of fraud for both financial institutions and users. The increasing use of online payments has led to a rise in the complexity and scope of fraudulent activity, which has resulted in significant financial losses. Hence, there is a compelling demand for improved fraud detection systems that not only detect fraud in real time but also decrease false positives, providing a flawless user experience. This project aims to address online payment fraud by developing a machine learning-based fraud detection system. The research question guiding this study is: How can machine learning algorithms be applied to accurately detect fraudulent online payment transactions while reducing false alarms? and Which transaction amount type is more frequently associated with fraudulent activities? The project will utilize the Online Payment Fraud Detection Dataset from Kaggle, which includes transaction features such as transaction type, amounts, and account balances. The difficulty of the issue is increased by the dataset's inherent class imbalance, of which fraudulent transactions make only a minor portion. The key columns in the dataset include:

step: represents a unit of time where 1 step equals 1 hour
type: type of online transaction
amount: the amount of the transaction
nameOrig: customer starting the transaction
oldbalanceOrg: balance before the transaction
newbalanceOrig: balance after the transaction
nameDest: recipient of the transaction
oldbalanceDest: initial balance of recipient before the transaction
newbalanceDest: the new balance of recipient after the transaction
isFraud: fraud transaction


A combination of supervised learning techniques like logistic regression, decision trees, and random forests will be used for classification. Additionally, unsupervised learning methods such as clustering and anomaly detection will help identify previously unseen fraud patterns. The implementation will use Python along with libraries like Scikit-learn, TensorFlow, and Pandas to develop and evaluate a reliable and flexible model capable of real-time fraud detection. This approach aims to reduce financial losses and enhance trust in online payment systems.

Project Stages


Problem Definition
Understanding the fraud detection data.
Identifying key challenges like class imbalance.
Exploratory Data Analysis (EDA)
Analyzing data characteristics, distribution, and potential outliers.
Visualizing key patterns using plots (e.g., histograms, correlation heatmaps).
Data Preprocessing
Handling missing values, categorical encoding, and scaling.
Addressing class imbalance using techniques like oversampling/undersampling.
Feature Engineering
Applying Principal Component Analysis (PCA) for dimensionality reduction.
Generating new features based on domain knowledge.
Model Development
Training multiple models: Logistic Regression, Random Forest, Decision Tree, etc.
Model Evaluation
Using accuracy, precision, recall, F1-score, and confusion matrix to evaluate models.

Code

Online Payments Fraud Detection.ipynb : Data cleaning , transformation and Visualizations.
model_online_payment_fraud.ipynb : Model training and evaluation scripts (Random Forest, Logistic Regression, Decision Tree).
Dataset: https://www.kaggle.com/datasets/rupakroy/online-payments-fraud-detection-dataset?resource=download
