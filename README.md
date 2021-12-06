# Classifying Products of Amazon India based on the product description
### TEAM: DATA 404
## Content
  1. **[Introduction](https://github.com/abhishek-pes/DA-Project-Amazon-product-listing#problem-statement)**
  2. **[Model Evaluation](https://github.com/abhishek-pes/DA-Project-Amazon-product-listing/blob/main/docs/modelPerformance.md)**
  3. **[Contribution](https://github.com/abhishek-pes/DA-Project-Amazon-product-listing/blob/main/docs/contribution.md)**

## Problem statement
The problem statement we are trying to solve is to create a multi-class classifier model , which will help to classify products based on the product description given. This is intended to improve the overall search and user experience while searching for any product on an ecommerce website like Amazon.

## About Dataset
The dataset chosen is the Amazon product listing India dataset available on [Kaggle](https://www.kaggle.com/promptcloud/product-listing-on-amazon-india)
This dataset was created by our in house teams at PromptCloud and DataStock. This dataset holds around 30K records. This dataset contains all the products from Amazon India. You can download the full dataset here.

## Problem Significance
  1. The problem statement we are trying to solve is to create a multi-class classifier model , which will help to classify products based on the product description given. This is intended to improve the overall search and user experience while searching for any product on an ecommerce website like Amazon.
  
  2. Since the proposed solution is focussing on the NLP techniques , this can also be further extended to voice based assistants , where users just tell the product description they are looking for and they will be landed to the right category of product they were looking for.

## Approach
![image](https://user-images.githubusercontent.com/54106076/144754817-8b5d72bd-7d0a-403a-b8cc-4ef77bfec125.png)

### Data cleaning
  1. **Missing values in columns:** some of the attributes in the dataset like the brand column and the price column had missing values which could be imputed.

  2. **Changing the datatype:** A few of the attributes were present in data type format which was not very helpful during exploratory data analysis and had to be changed to numerical values for better data analysis.

  3. **Inconsistency of categorical variables:** A few attributes with the categorical variables had values which were the same in meaning but were presented differently
### Text Preprocessing
  1. **converting to lowercase** so as to maintain a uniformity across the text data , which makes it easier for further pre processing.
  
  2. **removing punctuation and numerical values** , since these do not hold much significance for text classification they can be removed.
  
  3. **removing stopwords** is removing the most commonly used words like ‘is’,’are’,’the etc.
  
  4. **Tokenization** this is splitting of the text data into smaller parts of words, phrases etc. each of these smaller units is called tokens.
  
  5. **Stemming** is the process of producing morphological variants of a root/base word. For example, the word ‘likes’ will be converted to its base form ‘like’.
  
  6. **Lemmatization** and stemming is usually done together and the major difference between them is that lemmatization brings context to the word.
### Models used for classification
![image](https://user-images.githubusercontent.com/54106076/144754956-7b8f4275-8002-4fa2-8821-e2865a05e4a4.png)
