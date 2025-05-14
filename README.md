# Titanic-survival-prediction-using-ML
In this project, I analyzed the Titanic dataset to predict passenger survival using logistic regression. The process began with data loading and initial inspection for missing values and duplicates. To streamline the analysis, non-essential columns such as Cabin, PassengerId, Name, and Ticket were removed. Missing values in the Age and Embarked columns were addressed by imputing the mean and mode, respectively, and duplicate entries were eliminated.

Next, I conducted exploratory data analysis (EDA) to explore the distribution and relationships of key variables, including Survived, Pclass, Sex, Age, and Fare. Various visualization techniques such as bar plots, pie charts, histograms, and box plots were used to uncover patterns and gain insights into the dataset.

For modeling, categorical features like Sex and Embarked were transformed into numerical format using one-hot encoding. The dataset was then split into training and testing sets in an 80:20 ratio using scikit-learn.

A logistic regression model was trained on the training data to predict survival outcomes. The model's performance was evaluated using metrics such as accuracy, precision, recall, F1 score, and a confusion matrix. The results, summarized in a classification report, demonstrated that the model achieved an accuracy of approximately 78%, indicating its effectiveness in predicting passenger survival.
