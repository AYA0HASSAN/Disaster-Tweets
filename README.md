# Disaster-Tweets
NLP classification for tweets to disaster or not
Using NLP preprocessing techniques to tweets to be ready for model prediction.
Preprocessing Steps :
  - Remove Punctuations
  - Remove Links, HTML tags, Numbers
  - Convert Text to Lower case
  - Remove Stopwords 
  - Steeming (remove ing,s,...)
  - Lemmatization (to make sure the token keeps its meaning)
 now we have tokens, the next step is to convert these tokens to numbers/vectors as models understand only numbers.
 Bag of Words Technique => doesn't provide semantic meaning it is just a matrix/vectors of zeros ones
 Model:
 LSTM: it's good with sequence data knows when to remember and when to forget
 Bidirectional LSTM: it's LSTM enhancement 
 
