# Public-Relations-Department
Public Relations Department
In this case study we are going to do text analysis on amazon alex dataset.
So we will build the machine learning model and that way we can automate the process and can identify 
that the your customers are happy or not. without manualy going to massive numbers of reviews.

## Data Preprocessing and Cleaning:
1. NLTK used to remove stopwords for Lemmetization and for stemming
2. Removed Puncation from the Review.
3. Change the case for review
4. remove unicode 
5. Remove number from the review
6. Remove repeated spaces
7. Remove URLS

## Model Building:
1. To convert review in vector format used CountVectorizer \
**CountVectorizer:**\
Scikit-learn’s CountVectorizer is used to convert a collection of text documents to a vector of term/token counts. It also enables the ​pre-processing of text data prior to generating the vector representation. This functionality makes it a highly flexible feature representation module for text.
![alt text](https://github.com/Pravin1Borate/Public-Relations-Department/blob/master/CountVectorizer.png "Logo Title Text 1")

### Postive sentense cloud:
![alt text](https://github.com/Pravin1Borate/Public-Relations-Department/blob/master/positive_sentences_word_cloud.png "Logo Title Text 1")

### Negative sentense cloud:
![alt text](https://github.com/Pravin1Borate/Public-Relations-Department/blob/master/negative_senteces_word_cloud.png "Logo Title Text 1")

### Confusion Matrix for classified comments.
![alt text](https://github.com/Pravin1Borate/Public-Relations-Department/blob/master/confusion_matrix.png "Logo Title Text 1")
