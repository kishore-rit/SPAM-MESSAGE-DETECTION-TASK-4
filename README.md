# SPAM-MESSAGE-DETECTION-TASK-4

*COMPANY*: CODETECH IT SOLUTIONS

*NAME*:KISHORE.R

*INTERN ID*:CTO4DH113

*DOMAIN*:PYTHON PROGRAMMING

*DURATION*:4 WEEKS

*MENTOR*:NEELA SANTOSH

*DESCRIPTION*:

This Python script builds a simple SMS spam filter using TF-IDF and Multinomial Naive Bayes. It processes a small hard‑coded dataset, trains the classifier, evaluates performance, visualizes results, and predicts labels for new messages.


---

Workflow Breakdown

1. Data Setup & Label Encoding
A DataFrame contains ten sample messages, each labeled "ham" (0) or "spam" (1).

2. Train-Test Split
The dataset is split 70/30 into training and testing sets using train_test_split.

3. Text Feature Extraction
A TfidfVectorizer with English stop-words removed transforms messages into weighted TF-IDF feature vectors.

4. Model Training
A MultinomialNB classifier—ideal for discrete features like word frequencies—is trained on the TF-IDF vectors.

5. Evaluation Metrics

Predicts on the test set and prints the accuracy score.

Displays a classification report (precision, recall, F1-score).

Plots a confusion matrix using Seaborn to visualize true/false positives and negatives.


6. Custom Message Prediction
Four new messages are tested against the model, with each labeled “Spam” or “Ham” based on their predictions.


---

Why It Works

TF-IDF weighting emphasizes informative words and reduces the influence of common terms.

Multinomial Naive Bayes suits text classification since it models term frequency distributions efficiently.

Despite assuming feature independence, Naive Bayes classifiers are fast, performant, and well-suited for text domains.

Extensions & Scalability

Apply the pipeline to larger datasets, such as the SMS Spam Collection.

Enhance preprocessing with lemmatization, stemming, or noise removal.

Tune the vectorizer (e.g., include n‑grams, set maximum feature count).

Compare model performance with other classifiers (e.g., SVMs, logistic regression).

Deploy the model using a web interface or integrate it into messaging platforms.

*OUTPUT*:

