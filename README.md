
# NLP Project : Spam or Ham Message Detection

The model will predict if a text message is Spam or Ham.


## Problem Statement
The model takes in text messages and input and predicts if it is a Spam or Ham message with the help of TfidfVectorizer and RandomForestClassifier.

TfidfVectorizer - It is used to convert text into vectors(numbers) that the Machine Learning model can understand. It also provides information about which words are important in sentences or documents.

 Tf is referred as Term Frequency and provides the information about how many times a word appears in a document.

 Idf is referred as Inverse Document Frequency and provides information about how rare a word is across all documents.

RandomForestClassifier - It is a Machine Learning classification algorithm that is used to predict categories or classes. It is a tree based approach. 


## Dataset

The dataset is collected from the Kaggle website that are publicly available.

https://www.kaggle.com/datasets/thedevastator/sms-spam-collection-a-more-diverse-dataset

It consists of two columns:  
1 : sms - this contains the text dataset  
2 : label - whether the sms is spam or ham
     
## Tools and Technologies

Libraries used :  
1 : numpy  
2 : pandas  
3 : spacy  
4 : scikit-learn   
5 : seaborn  
## Project Architecture
The model has the Pipeline of TfidfVectorizer followed by RandomForestClassifier.

![image alt](https://github.com/Rimpa271/spam-message-spacy/blob/main/pipeline.jpg?raw=true)
## Steps
1 : Loading dependencies - All the libraries that are used in this project is imported.  
                                          2 : Loading the dataset - The dataset is uploaded.  
3 : Data Preprocessing - Performing Lemmatization. It converts a word into its base form and uses a vocabulary to ensure the resultant word is a valid word.  
4 : Tokenization and Stopwords removal - Tokenization is the process of breaking down text into smaller units known as tokens which can be words , phrases or characters.         Stopwords are the words which do not have a valid meaning individually, they are important parts of speech but does not play an important role in NLP tasks. 

5 : Implementing the pipeline  
6 : Prediction and Evaluation - The model is evaluated on the basis of accuracy and classification report is also produced.



                                    
## Final Results

The model is evaluated on the basis of Accuracy and it has achieved an accuracy of 97.84 on this dataset.
