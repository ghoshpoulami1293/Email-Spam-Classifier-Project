# Email-Spam-Classifier-Project

spam.csv is obtained from kaggel and analysed.
The EDA reveals presence of "spam" and "ham" indicating spam and non spam messages.

Data is cleaned, unnecessary columns dropped for analysis.
A length column is added to calculate and store teh length of teh message for further analysis.
Countplots and histograms are generated for better data visualization.

This EDA then leads to the next part of the project - the determination of an email message being spam or not.

The preprocessed data is split into training and testing datasets in the ration 70:30 and a machine learning algorithm is utilized to fit the data and train the model.
I have implemented the Support Vector Machine Algorithm which is a supervised machine learning algorithm used for classification and regression tasks.
The kernel chosen for this is Radial Basis Function (RBF) Kernel.This yeilded the best score for the model.
The testset is used to make the predictions after training the model and the accuracy obtained for the model is 95.215%
