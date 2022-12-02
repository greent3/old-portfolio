{
    "title":"F. Ecommerce Purchase Predictor",
    "link":"https://github.com/greent3/Harvards_AI_Programming_W_Python/blob/main/Chapter_4_Learning/shopping/shopping/shopping.py",
    "image":"/img/ecommerce.png",
    "description":"Given information about a user — how many pages they’ve visited, whether they’re shopping on a weekend, what web browser they’re using, etc. — the classifier will predict whether or not the user will make a purchase.",
    "tags":[
          "Python",
          "ML",
          "KNN",
          "Classification"
        ],
    "featured": true
}


When we run our program, we pass the location of a CSV file containing data about website shoppers as a command line argument. Our program:

- loads in that data
- reformats it into the correct data type
- splits it into training and testing data
- uses that data to train a k-nearest neighbors classification model
- and outputs the sensitivity (true positive rate) and specificity (true negative rate) of our trained model on our testing data.
