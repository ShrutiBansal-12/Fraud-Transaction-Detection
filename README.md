# Fraud-Transaction-Detection

•	Data Preparation
During this internship, a dataset of online bank transactions with associated labels with them was taken. Dataset was cleaned, null and missing values were removed to make dataset more relevant. Feature Engineering (mainly one-hot encoding) was performed with the aim to convert categorical variables (‘type’ in dataset) into binary form. Unnecessary columns (or features) were dropped from the main database so that the relevant features are used for the training purpose. The dataset was divided into training and testing with percentage of 20% of testing data. To increase the diversity and resilience of the model, data augmentation techniques SMOTE was implemented on the training dataset.

•	Exploratory Data Analysis
As part of the internship, Exploratory data analysis was performed and Data visualization was done by plotting distplots, histplots, barplots, jointplots, scatterplots, countplots and boxplots to gain insightful information from the dataset before going into the training phase of the machine learning models using this dataset. This analysis yielded information about the class balance. Univariate, Bivariate and Multivariate analysis was done for better visualization.

•	Model Application
The internship involved testing multiple machine-learning models for fraud transaction detection, including Logistic Regression, K-Nearest Neighbours, Decision Tree classifier and Random Forest classifier. The models were evaluated on the performance metric-accuracy, precision, recall and F1 score. The corresponding confusion matrix was plotted for each model before and after the data
augmentation for training and testing of all the above-mentioned ML models.

•	Model Training and Evaluation
The models selected for testing were trained on the training dataset, with performance monitored on the validation dataset. The training was executed for a specified number of epochs. Various metrics, including accuracy, precision, recall, and F1 score, were calculated using the test dataset to assess model performance. These metrics provided a comprehensive view of each model's effectiveness in the study.

•	Results
Metrics like accuracy, precision, recall and f1 score have been tabulated for seamless comparison and analysis. Decision Tree classifier and Random Forest classifier performed the best in fraudulent transaction detection tasks across all performance metrics and have almost similar F1 score of 0.8697 and 0.8635 respectively after implementation of data augmentation techniques on training dataset.
