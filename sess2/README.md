Online Session 2 - Coding Exercise
(The following links will open in new window)

Understanding Feature Engineering (Part 3) - Traditional Methods for Text Data [18 minutes]

You do not need to submit this code again, since it was covered in the first class. For your reference, code is available in Github here.

This article with Jupyter notebook presents the traditional features engineering techniques in text data. After presenting text pre-processing, it will cover the more traditional methods such as bag-of-word or n-grams, and tf-idf. It will also cover the powerful method of document similarity and document clustering using topic models.

Using BERT For Classifying Documents with Long Texts by Armand Olivares, December 18, 2019 [7 minutes]

This article walk-through the step-by-step process of using BERT for text classification (specifically long texts). First, understand the data, then preprocess the data, followed by formatting the data for the BERT model. Next, fine-tune BERT and get the BERT vector as the feature representing the original text. Lastly, create an LSTM model that takes the BERT vector as the input and make a prediction. Please run the code in the Github.

BONUS/EXTRA
Language Model as Text Features

For more advanced feature engineering, use the new state-of-the-art contextual embeddings such as "language models" like FLAIR, BERT, ELMO. To understand fully, please read Language Model (LM) from NLP Course, which covers LM definition, general framework, n-gram LM, Neural LM, general strategies, Evaluation, practical tips, analysis and interpretability. To implement LM in your code, please go through the quick tutorial on language model and use these as features on your project. You may also choose to use the character and word embedding and stacked embedding from this package as well. For advanced feature engineering, there is also document embedding and sentence embedding in this package.

After completing the programming code components, incorporate these features into your project and consider how you would use them.

Topic Modelling with Gensim [Python]

This is a Gensim tutorial that goes through topic modeling, from downloading packages to preparing text, to building the model, to final hyperparameter tuning and interpreting the results. Please note that in topic modeling with Gensim, there are errors related to the Mallet executable. Choose not to install this executable because it cannot be trusted. Therefore treating it as a possible information security risk, do not download and run the executable as part of the notebook.

