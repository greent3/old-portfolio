{
  "title": "AWS RDS/Django/PostgreSQL: Serverless investment tracking app",
  "date": "",
  "image": "/img/stock_portfolio.png",
  "link": "https://github.com/greent3/django_stock_portfolio",
  "description": "Django CRUD app to track profits and losses from past investments. Updated daily via AWS Lambda. ",
  "tags": ["Python", "Django", "AWS", "Docker", "PostgreSQL", "JavaScript", "HTML", "CSS"],
  "featured":true
}

A django app I built from scratch.  
All visitors can view a list of my past investments. To create, update, or delete items, I can simply login and make selections in the UI.  
The trading price of US-based stocks (listed on NYSE/NASDAQ) is updated daily via AWS Lambda.


Uses:
 - Django MVC w/ fat models and skinny views
 - PostgreSQL database
 - Docker
 - Javascript for DOM manipulation & variable computation
 - AWS Lambda
 - AWS RDS

Utilizes:
- unit testing (models, views, urls, and forms)
- class-based views
- fixtures (for default stock data)
- Template inheritance
- virtual environment & protected environment variables
- gitignore & dockerignore

Video demo link here: https://youtu.be/4Tu6catIE70 