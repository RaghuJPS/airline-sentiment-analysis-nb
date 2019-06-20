# airline-sentiment-analysis-nb
airlines sentiment analysis using NB classifier 

The dataset has been taken from Kaggle. (https://www.kaggle.com/crowdflower/twitter-airline-sentiment/home) This is a dataset having tweets about 6 US Airlines along with their sentiments: positive, negative and neutral. 

 data set contains two files: ‘Tweets-train.csv” and ‘Tweets-test.csv” 
 
 The train data contains about 11000 tweets and test contains 4000 tweets. 
 
 Following are the operations that were carried out:
 
 • Read the training data using pandas module and select only the sentiment and text columns 
 
• Observe randomly generated 10 tweets for each sentiment with respect to the following: 

o Text contains references with ‘@’ 
o Text contains links (http , https ) 
o Text contains punctuations o Text contains Emoticons  
 
• clean all the above observed tokens from the tweet text. Save changes in a new column  
 
 
• List down the most common 15 words for each sentiment. Observe the results 
 
 
• Remove Stopwords from all the tweets. Save changes in a new column and list down most common 15 words. 
 
  
• Remove these words from all the tweets. 

  americanair, united, delta, southwestair, jetblue, virginamerica, usairways, flight, plane 
 
Save changes in a new column and list down most common 15 words. Comment your observations  
 
 
• Encode Sentiments using Label Encoder 
 
• Vectorize the Text Column () --Count Vectorizer used
 
 
• Prepare a multiclass Classification model using Naive Bayes classifier  
 
• Read the test data and carry our data cleaning, encoding and vectorising operations on the test data 
 
 
• Predict the sentiments for test data 
 
 
• Print and explain the Confusion Matrix  
 
 
• Compute Accuracy of your model  
 
