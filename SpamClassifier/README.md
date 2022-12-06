## Spam Classifier
Dataset : UCI ML repo

### Flow
Collected data from UCI and started to clean the data by removing the un-necessary data and also STOP WORDS.We did Stemming on the remaining words by using `PorterStemmer()`.
And to create BOW(bag of words) we used `countvectorizer()` from sklearn to encode the text into machine-readable data.
Finally built model using Multinominal-Navies_Bias to detec **SPAM** or **HAM**

We could see **80%** as the `accuracy_score()` from sklearn metrics.