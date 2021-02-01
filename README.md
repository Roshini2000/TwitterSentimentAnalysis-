# TwitterSentimentAnalysis-
In this sentiment analysis problem our task is to classify a set of tweet into two categories

        --> racist/sexist
        --> non racist/sexist
        
Sentiment analysis is one of the many applications od Natural Language Processing. It is a set of methods and techniques used for extracting subjective information from text or speech.

Modules:

1. Text Prepocessing
2. Data Exploration
3. Feature Extraction
4. Model Building

In the training sample of tweets and labels, label '1' denotes the tweet is racist/sexist and label '0' denotes not racist/sexist.

Features Extraction:
1. Bag of Words Features:
     Bag of Words considers a COrpus C of documents{d1,d2...} and N unique tokens extracted out of the corpus C. The N tokens(words) will form a dictionary and the size of the bag-of-words matrix M will be given by D* N. Each row in the matrix M contains the frequency of tokens in document D(i).
2. TF-IDF Features:
     This method is based on the frequency method but it is different to the bag-of-words approach in the sense that it takes into account not just the occurence of the word in  a single document but in the entire corpus. TF-IDF works by penalising the common words by assigning them lower weights while giving importance to words which are rare in the entire corpus but appear in good numbers in few documents.
3. Word2Vec Features:
      The objective of word embeddings is to redefine the high dimensional word features into low dimensional feature vectors by preserving the similarity in the corpus. Word2Vec is a combination of two techniques CBOW - Continuous bag of words and Skip-gram model. Both of these are shallow neural networks which map word to the target variable which is also a word. 
