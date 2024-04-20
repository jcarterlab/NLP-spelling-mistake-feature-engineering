# NLP spelling mistake feature engineering

When attempting to predict scores from a Kaggle competition essay text dataset, spelling mistakes could be a potentially useful feature. Yet creating an accurate spelling mistakes feature is not as easy as it seems. 

The spellchecker Python library can indicate if a word is recognized or not, but it doesn't account for punctuation stripped contractions, digits, decades nor a variety of other common word types. As can be seen below, applying some general remedies for these shortcomings improves our spelling mistake feature's correlation with the y variable (essay scores) by 2.09% and likely improves its generalizability on unseen data.  

The notebook can be found [here.](nlp_spelling_mistake_feature_engineering.ipynb)
