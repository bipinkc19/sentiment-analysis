# sentiment-analysis

Learning sentiment analysis using various NLP techniques
- Tfidf/Count vectorization coupled with naive bayes, logistic regression, etc.

# Results

## Test metrics

### Using count vectorizer

![Bayes](./images/count_vectorizer.png)

### Using tf idf

![Bayes](./images/tf-idf.png)

## Using wordToVec embeddings and taking average of all word's embedding

![wordtovec](./images/embeddings.png)
![wordtovec](./images/embeddings_test.png)

## Model explanations

### Usin LIME

![Lime](./images/lime.png)
![Lime1](./images/lime.png)


### Using Logistic Regression count vectorizer

Words with their importances in positive or negative prediction

![Logistic](./images/positive_count_vectorizer.png)
![Logistic](./images/negative_count_vectorizer.png)

### Using Logistic Regression tfidf

Words with their importances in positive or negative prediction

![Logistic](./images/positive_tfidf.png)
![Logistic](./images/negative_tfidf.png)

