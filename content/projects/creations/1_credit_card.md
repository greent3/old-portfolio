{
  "title": "Django/ML: Credit Card approval website with custom ML models and REST API",
  "date": "",
  "image": "/img/credit_card.png",
  "link": "",
  "description": "In Progress! Django App where users get approved/denied a credit card via REST APIs containing Logisitic Regression Model endpoints",
  "tags": ["Python", "Django", "REST", "AWS"],
  "featured":true
}

In Progress!  
Django app where users can:
 - Create accounts
 - View available credit cards and their specs
 - Create a preset application and apply for credit cards

Users are approved/denied by a Logistic Regression model trained on demographic data from good/bad borrowers.  
Each credit card has it's own ML model (trained on same data, but with different labels to ensure profitable profit/risk tradeoff)

Includes:
 - EDA/Data Cleaning
 - Logistic Regression Model training and testing
 - JavaScript for DOM manipulation
 - Django Rest Framework API for accessing ML models

Utilizes:
 - unit testing (models, views, urls, and forms)
 - class based views 
 - fixtures (default credit card data)


 