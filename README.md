# Tweet-sentiment-analysis
Kaggle project version 2.0


Sentiment analysis is a common use case of NLP where the idea is to classify the tweet as positive, negative or neutral depending upon the text in the tweet. This problem goes a way ahead and expects us to also determine the words in the tweet which decide the polarity of the tweet.

## Table of Contents
<details open>
<summary>Show/Hide</summary>
<br>

1. [ File Descriptions ](#File_Description)
2. [ Technologies Used ](#Technologies_Used)    
3. [ Structure ](#Structure)
4. [ Future Development ](#Executive_Summary)
</details>

## File Descriptions
<details>
<a name="File_Description"></a>
<summary>Show/Hide</summary>
<br>
  
* train.csv  - the training set
* test.csv - the test set
* sample_submission.csv - a sample submission file in the correct format

*Columns*
* textID - unique ID for each piece of text
* text - the text of the tweet
* sentiment - the general sentiment of the tweet
* selected_text - [train only] the text that supports the tweet's sentiment
</details>

## Technologies Used:
<details>
<a name="Technologies_Used"></a>
<summary>Show/Hide</summary>
<br>
    
* <strong>Python</strong>
* <strong>Pandas</strong>
* <strong>Numpy</strong>
* <strong>Matplotlib</strong>
* <strong>Seaborn</strong>
* <strong>NLTK</strong>
* <strong>CountVectorizer</strong>
* <strong>Scikit-Learn</strong>
* <strong>Keras</strong>
* <strong>Tensorflow</strong>
* <strong>Spacy</strong>
* <strong>wordcloud</strong>
</details>

## Structure of Notebooks:
<details>
<a name="Structure"></a>
<summary>Show/Hide</summary>
<br>
  

    
1. Import packages

2. Load Data

3. Data Exploration
   * 3.1 Analysis of the Sentiment Column
   * 3.2 Distribution of the Sentiment Column
   * 3.3 What do we currently Know About our Data

4. Generating Meta-Features
   * 4.1 Jaccard Similarity Scores between text and Selected_text
   * 4.2 Number of words in selected text and main text
   * 4.3 Length of words in text and selected
   * 4.4 Difference In Number Of words of Selected_text and Text
   
5. Exploration on the meta-features

6. Conclusion of EDA

7. Text Data Preprocessing

8. Most common words

    * 8.1 Most Common words in our Target-Selected Text
    * 8.2 Most Common words in Text
    * 8.3 Most common word for each sentiments
    * 8.4 Unique word for each sentiments
    
9. It's Time For WordClouds 
    * 9.1 Dimensionality Reduction with t-SNE (Doc2Vec)
    * 9.2 Dimensionality Reduction with PCA (Doc2Vec)
 
10. Ngram exploration
    * 10.1 Distribution of bigram
    * 10.2 Distribution of trigram

11. Extracting the part of the tweet that reflects the sentiment : Resources
    * 11.1 Question-Answering
    * 11.2 Method with Pytorch and BERT

</details>  


<a name="Executive_Summary"></a>
## Future Development
    
* Maybe later, I will focus my attention on BERT and create a model but not for now.
