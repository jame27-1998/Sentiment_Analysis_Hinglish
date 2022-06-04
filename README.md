# Sentiment_Analysis_Hinglish

<h3><b>Abstract:</b></h3>

Sentiment Analysis plays an Important role in monitoring Social media and as
well customer reviews by obtaining the polarity of a tweet or comment or
statement in social media.These days everyone is active on Social media and
expressing their views in the digital world. Based on these views we can make
decisions like which topic is trending currently or reacting to customer reviews
based on customer feedback etc. Many ML techniques can be used to draw out the
polarity of a statement like MNB , SVM, LR, RF etc and Deep learning
techniques like some extension to RNNs like , LSTM ,GRU ,Bi-LSTM ,Bi-GRU
and some advanced techniques like Transformers and Bert models .For the vector
representation of the words in the sentences we used TF-IDF vectorizer for
machine learning algorithms. This paper gives some rough idea of comparative
study of ML algorithms applied on code mixed/Multi Language mixed data set
like Hinglish i.e where each data point is a combination of english and hindi
words and each english word is followed by ENG and each Hindi word followed
by HIN. We Got this dataset from a codalab competition website named as Task:9
on the Semeval-2020 competition website.So far comparing all the algorithms on
this dataset with F1 score as a metric .we got 0.771 ensemble soft voting
classifier of (MNB , SVM, LR, RF) which is the best among all we have applied.
