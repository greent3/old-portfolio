{
    "title":"Python Django: RESTful Movie Database API w/ extensive unit testing (Tutorial)",
    "link":"",
    "image":"/img/movies.jpg",
    "description":"A django-implemented movie database similar to IMDB with different permissions for unauth, admin, and authenticated users. The app also uses validators, pagination, and throttling. I felt the unit testing in the tutorial was lacking, so I implemented extensive unit tests.",
    "tags":[
          "Python",
          "Django",
          "RESTful API",
          "SQLite"
        ],
    "fact":"",
    "featured": false
}


#### The project is divided into 2 apps.

 - Movielist app: handles all movie database functionality (adding movies to the database, querying lists of movies, creating/viewing reviews, etc.) along with their associated permissions.
 - User app: handles user functionality (login, register, etc.)


#### The unit testing covers all intented functionality for each level of authentication.  
Employs validators, pagination, and throttling.