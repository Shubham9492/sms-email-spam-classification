# SMS/Email Spam Classification Project

A machine learning-based system to classify SMS and email messages as spam or not spam using the SMS Spam Collection Dataset. The project includes data cleaning, exploratory data analysis (EDA), text preprocessing, model building, evaluation, and deployment using Streamlit.

## Dataset
The project uses the [SMS Spam Collection Dataset](https://www.kaggle.com/uciml/sms-spam-collection-dataset) containing 5,574 SMS messages labeled as ham (4,827) or spam (747).

## Steps Performed :
1) Data Cleaning
Performed removal of unnecessary characters, handled missing values, and standardized text formatting.
2) Exploratory Data Analysis (EDA)
Conducted analysis to understand the distribution and patterns in the dataset, including visualization of spam vs. ham messages.
3) Text Preprocessing
Applied tokenization, stop word removal, stemming, and vectorization to convert text data into numerical form suitable for model input.
4) Model Building
Built multiple models including Naive Bayes, SVM, and Logistic Regression etc.. Tuned hyperparameters and selected the best-performing model based on evaluation metrics.
5) Model Evaluation
Calculated precision and accuracy scores to assess model performance. The Naive Bayes model achieved high accuracy and precision in distinguishing spam from ham messages.
6) Deployment
Deployed the model using Streamlit for user interaction, allowing users to input messages and receive spam/ham classification results.
