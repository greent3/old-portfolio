{
    "title":"H. Whisky Review Sentiment Classifier",
    "link":"",
    "image":"/img/hibiki.jpg",
    "description":"Classifying Japanese Whisky reviews as positive or negative using TFIDF & Naive Bayes",
    "tags":[
          "Python",
          "Classification",
          "TFIDF",
          "Naive Bayes"
        ],
    "featured": true
}

Classifying Japanese Whisky reviews using TFIDF/Naive Bayes

Given a CSV file with 200 Japanese whisky reviews labeled "positive" or "negative", and 900 unlabeled reviews, let's train a Naive Bayes model on TFIDF data so we can predict the labels for the remaining 900.

Note: The dataset was not that great (small, lots of typos, many negative reviews with positive sentiment words "ex: not that good"), but it still served as good practice for cleaning data, NB, vectorizers, working with dataframes, and even a little bit of SQL at the end.
