# Sentiment-Analysis--Amazon-Reviews

Analysis of emotion is omnipresent, and is a method of classification based on natural language processing. Use of Sentiment Analysis helps us identify the sentiments of a review of a product, feedback from our customers which can further be utilized for decision making. 

1. Reviews Preprocessing and Cleaning
2. Story Generation and Visualization from reviews
3. Extracting Features from Cleaned reviews
4. Model Building: Sentiment Analysis

• To perform text reading, the wording is in a simplified format. The first word gives the mark, so we need to translate that to a number and then take the rest as the statement.
• For data cleaning, normalization is performed using a regular expression.
• A regular expression is a special sequence of characters that helps you match or find other strings or sets of strings, using a specialized syntax held in a pattern. Regular expressions are widely used in UNIX world. The module re provides full support for Perl-like regular expressions in Python.
• Tokenization is the process of tokenizing or splitting a string, text into a list of tokens. 
• Tokenizer in our project is running using the top 12000 words as features.
• Performed the Convolutional Neural Net model wherein it has 64, 3-layer embedding with the first two matching normalization and max pooling. The results are the dense layers followed by the output. 
• We perform the Recurrent Neural Net model on the train and test datasets and we get an accuracy score of 95%. 
• Given a character, or a sequence of characters, what is the most probable next character? This is the task we're training the model to perform. The input to the model will be a sequence of characters, and we train the model to predict the output—the following character at each time step.
• Since RNNs maintain an internal state that depends on the previously seen elements, given all the characters computed until this moment, the next character can be predicted.
