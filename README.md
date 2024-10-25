# NLP-Sentiment Analysis Predictive Model Project

## Overview
This project involves creating a sentiment analysis model using Natural Language Processing (NLP) techniques. The goal is to classify text reviews as positive or negative based on their sentiment.

Sentiment analysis is a key application of NLP that helps classify textual data based on the expressed emotions or opinions—typically as positive, negative, or neutral.

In this project, I implemented a binary classification approach to determine whether a review is positive or negative. The workflow involved several steps including text preprocessing, feature extraction through vectorization, and model training using multiple machine learning classifiers.

Sentiment analysis has widespread applications in various domains such as customer feedback analysis, social media monitoring, and product review sentiment analysis, where companies can gauge public sentiment toward their products, services, or content.

## Project Workflow

1. **Text Preprocessing**:  
   - Tokenization
   - Lowercasing
   - Stemming (using the Porter Stemmer)
   
2. **Feature Extraction**:  
   - Bag of Words (BoW) vectorization was used to convert textual data into numerical format for model training.

3. **Models Applied**:  
   - Random Forest Classifier  
   - Logistic Regression  
   - Naive Bayes  
   - K-Nearest Neighbors (KNN)  
   - Support Vector Machine (SVM)  

4. **Evaluation Metrics**:  
   - Accuracy  
   - F1 Score  
   - Cross-Validation to ensure generalization

## Results
- **Best Performing Model**: Logistic Regression
  - Test Accuracy: **80.5%**
  - F1 Score: **0.79**
  - Cross-Validation Accuracy: **79.3%**

## Conclusion
- The Logistic Regression model provided the best balance of performance and generalization.
- This project helped deepen my understanding of NLP techniques like text vectorization and classification algorithms.
- I automated the process of model creation, training, testing, and evaluation through custom Python functions.

## Owner

- **Project Owner :-** Shubham Parihar
- **Link Of Linkedin :-** https://www.linkedin.com/in/shubhamparihar7/
