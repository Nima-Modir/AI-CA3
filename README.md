# Text classification using the Naive Bayes Classifier
## Part 1: Data Preprocessing
### Dataset:
The dataset contains Persian-language news articles in categories like sports, politics, technology, health, etc.
The data is divided into training (train.csv) and testing (test.csv) sets.
### Preprocessing Steps:
Use text preprocessing techniques such as tokenization, stopword removal, and lemmatization/stemming.
The Parsivar and Hazm libraries are suggested for Persian text preprocessing tasks.
Normalize the text by removing unnecessary characters like \r and \n, and apply additional cleaning steps.
## Part 2: Model Training
### Naive Bayes Classifier:

Train a Naive Bayes model using a bag of words approach. The feature set consists of tokenized words from the articles.
Implement bigrams for feature extraction to capture word combinations.
Use additive smoothing (Laplace smoothing) to handle unseen words in the test data.
### Feature Extraction:

Create a word cloud to visualize the most frequent words.
Apply bigram extraction and compare the performance with unigram features to assess the impact of n-grams.
## Part 3: Model Evaluation
### Performance Metrics:

Evaluate the model using metrics like accuracy, precision, recall, and F1-score.
Report both macro and micro averages to handle the multi-class classification problem effectively.
### Comparison:

Compare the performance of unigram-based models with bigram-based models.
Use bar plots to visualize the accuracy and F1-scores for each class (e.g., sports, technology).
