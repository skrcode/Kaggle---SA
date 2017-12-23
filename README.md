My published kernel in the Kaggle Contest, Spooky Author Identification. Highest Public LB score (Top 50) - 0.29 for a published kernel in the contest. Uses Simple Feature Engineering like Punctuation,Stop Words,Glove Sentence vectors. In addition, it creates stack features from simple Features such as tfidf and count vectors for words and chars. Multinomial naive bayes(mnb) is then applied with the following combination - tfidf+words+mnb,tfidf+chars+mnb,count+words+mnb,count+chars+mnb. Conv Nets on keras texttosequence, NNs on glove sentence vectors and Fast Text are also used as stack features. XGBoost, which is the final model which will use the simple and stack features as input.
