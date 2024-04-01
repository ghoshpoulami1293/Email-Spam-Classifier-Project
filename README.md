# Email-Spam-Classifier-Project

Project Title: Email Spam Classification

Description:

In this project, "spam.csv" dataset obtained from Kaggle is analyzed, which contains email messages labeled as "spam" and "ham" (indicating non-spam). Exploratory data analysis (EDA) is performed to understand the dataset better and preprocess the data for further analysis.

The preprocessing steps involve cleaning the data and dropping unnecessary columns. Additionally,a "length" column is added to store the length of each message for further analysis. Visualizations such as countplots and histograms are generated to provide insights into the distribution of spam and non-spam messages.

The EDA leads us to the next part of the project: determining whether an email message is spam or not. The preprocessed data is split into training and testing datasets in a 70:30 ratio. The Support Vector Machine (SVM) algorithm , , a supervised machine learning algorithm commonly used for classification tasks , is then utilized. The Radial Basis Function (RBF) kernel is chosen for the SVM model, which yields the best performance for this dataset.

After training the model on the training dataset, the performance of the model is evaluated using the testing dataset. The model achieves an accuracy of 95.215% on the test set, indicating its effectiveness in classifying email messages as spam or non-spam.
