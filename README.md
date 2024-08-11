**Credit_card_fraud_analysis**

The project uses machine learning to create a fraud detection system that accurately identifies fraudulent transactions. By analyzing various transaction features, the aim is to develop a predictive model that classifies transactions as either fraudulent or legitimate. This system will help reduce financial losses and enhance transaction security.

**Dataset Summary:**

This dataset consists of credit card transactions from the western United States. It has 14,446 entries and 15 columns. 

It includes various information about each transaction, broadly categorized into several types: Transaction Details: Transaction Amount, Transaction Date, and Time indicating the exact date and time when the transaction occurred. 

Customer Information: Customer city, customer state, customer latitude and longitude showing geographic coordinates of the customer's location, customer date of birth which can be used to derive their age.

Fraud Indicator: A binary indicator (0 or 1) showing whether the transaction was fraudulent.



**_Summary of the Model's Performance:**

**Accuracy** (98.26%): Indicates that the model correctly classifies 98.26% of the total instances.

**Precision** (95.71%): Indicates that out of all predicted positive instances, 95.71% are actually positive.

**Recall** (89.68%): Indicates that out of all actual positive instances, the model correctly identifies 89.68%.

**F1 Score** (92.60%): This is a harmonic mean of precision and recall, providing a single metric that balances both.

**Specificity** (99.45%): Indicates that out of all actual negative instances, the model correctly identifies 99.45%

**Summary of the Project**
**Steps Followed:**

**Data Description:**

Explored the dataset to understand features and their distributions, setting the foundation for data analysis and modeling.

**Data Visualization:**

Created visualizations (histograms, scatter plots, etc.) to uncover patterns and relationships in the data, aiding in feature understanding and model preparation.

**Model Training:**

Applied LabelEncoder to convert categorical variables into numerical values and used StandardScaler for feature normalization, ensuring all features are on the same scale.
A 70:30 split was done for training and testing the model.

**Model Training and Evaluation:**

Trained the Random Forest Classifier to predict fraud, achieving approximately 98% accuracy, indicating effective model performance in distinguishing fraudulent transactions from legitimate ones.

**Applications:**

**Fraud Prevention:**

Real-Time Fraud Detection: Identifies and blocks fraudulent transactions in real-time, preventing unauthorized access to accounts and reducing financial losses.
Risk Assessment: Evaluates the risk level of transactions based on historical data, helping to flag potentially suspicious activities before they occur.
Customer Protection:

Account Security: Enhances the security of customer accounts by identifying unusual patterns and behaviors, safeguarding against fraudulent activities.
Alert Systems: Sends alerts to customers and financial institutions when suspicious activity is detected, allowing for immediate action and resolution.
Financial Institutions:

Operational Efficiency: Reduces the manual effort and time required for fraud detection by automating the process with advanced models.
Regulatory Compliance: Assists financial institutions in meeting regulatory requirements by maintaining accurate and up-to-date fraud detection systems.
Consumer Trust:

Enhanced Trust: Builds consumer trust in financial institutions by demonstrating a commitment to protecting customer information and preventing fraud.
Improved Experience: Provides a smoother and safer transaction experience for customers, reducing the risk of fraud-related issues.
