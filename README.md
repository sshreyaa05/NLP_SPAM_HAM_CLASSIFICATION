### Spam-Ham Classification using Multinomial Naive Bayes with Text Preprocessing Techniques

### Overview:
The project focuses on classifying text messages as either spam or ham (non-spam) using Natural Language Processing (NLP) techniques. We preprocess the data by tokenizing the text, removing stop words, and utilizing two vectorization methods: Bag of Words (BoW) and Term Frequency-Inverse Document Frequency (TF-IDF). After preprocessing, we apply the Multinomial Naive Bayes classifier to predict whether a message is spam or ham. The effectiveness of both vectorization methods is compared, with Bag of Words yielding better accuracy.

### Steps:

#### Text Preprocessing

1. Tokenization: The text data is split into individual words (tokens).

2. Stop Words Removal: Commonly used words that do not add significant meaning (e.g., "the", "is", "in") are removed from the text.
Vectorization

3. Bag of Words (BoW): This method converts the text into a matrix of token counts. Each word’s frequency in the corpus is used to represent the text.
   
4. TF-IDF (Term Frequency-Inverse Document Frequency): This method transforms the text into numerical data, accounting for both the frequency of words and their importance within the corpus.

### Model Training

A Multinomial Naive Bayes classifier is trained on the transformed data. This classifier is ideal for text classification problems where features are based on word counts.

### Model Evaluation

We compare the performance of both BoW and TF-IDF using accuracy metrics.

### Results:
After applying both vectorization methods and training the Multinomial Naive Bayes classifier, it was observed that Bag of Words produced higher accuracy in classifying spam and ham messages compared to the TF-IDF method. The accuracy of the Bag of Words model was higher, indicating it was more effective for this classification task.
