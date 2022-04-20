# Question-Duplicate-Detection-in-Quora
In this project with text analysis methods such as TF-IDF, Bag of Words, and machine learning algorithms, similar questions are identified, which can be used to link users to the answers without making them wait for the answer. This can lead to increase user satisfaction and the popularity of the website. In addition, we can prevent data redundancy.         

This goal has been achieved in the following steps to find an appropriate classifier model which automatically identify and label duplicate questions. 
- Download data from [here](https://drive.google.com/file/d/19iWVGLBi7edqybybam56bt2Zy7vpf1Xc/view?usp=sharing).
- Exploration
- Cleaning
- Feature Engineering
- Modeling (XGboost, Naive Bayes Classifier)     

## Exploration
This step includes analysing the dataset, handling null values and doing some satatistical analysis. 

## Cleaning
This has been done by: 
- Change abbreviations to their original terms(UK:England, US/USA:America)
- Convert Unicode characters to ASCII
- Remove punctuations 
- Correct contractions (can’t : can not, i’ll: I will)
- Convert some special characters ($: Dollar, %: Percent, ….)
- Remove stopwords 
- Normalizing
- Stemming

## Feature Engineering
 In this step two techniques are used TF-IDF and Bag Of Words
 - TF-IDF : It Extracs Keywords and gives high score to the most relevant words.       
 - Bag Of Words : It tokenizes the texts and counts the occurrences of token and return them as a sparse matrix.







