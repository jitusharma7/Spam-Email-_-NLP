# Spam-Email-_-NLP
This project aims is to classify mail into spam and non-spam category based on the content of mail using Natural Language Processing (NLP)


## Table of Content
  * [Problem_Definition](#Problem_Definition)
  * [Dataset_Description](#Dataset_Description)
  * [Data_Preprocessing](#Data_Preprocessing)
  * [Model_Building](#Model_Building)
  * [Result](#Result)
  * [Credit](#Credit)
  
 
 ## Problem_Definition
 This is a very tedious task to move mail from an inbox to a spam folder for a person. if the classification is not proper. Especially from the perspective of the organization where Fishing is a major IT threat for any organization, the correct mail classification category is a prerequisite for any organization.
 
 So, the model will enable classification mail based on the content.
 
 
 ## Dataset_Description
 The dataset consists of the following attributes:
This dataset consists of the content of mail with the respective category of mail.

 


## Data_Preprocessing
* Step1   - Tokenize the text
* Step2 -    Remove the Stop word, Punctuation
* Step 3 -   Data Cleaning using Steeming ( We can use Lematizing also ) 
* Step 4 -   Vectorize the column  ( Convert column into numerical form 
   We can use - COunt vectorizer, N-Gram Vectorizer, or TFIDF vectorizer
* Step 5 - Create text length and punctuation percentage - two new feature

   


## Model_Building
* Applying RandomForest and XGBoost classifier  with and without hyperparameter tuning using GridSearchCV
* Precision and Accuracy score is better in Random forest classifier but Recall score is less


## Result
*  XG Boost classifier takes more time to fit the model but less time to predict than Random Forest classifier.
* Randomforest classifier and XG Boost classifier accuracy are 97.4 % & 96.30 respectively.


## Credit
 This project has been done as an NLP LinkedIn learning course project.
