{
    "title":"Python ML: Constraint Satisfication Crossword Solver",
    "link":"https://www.youtube.com/watch?v=864kTdvNl_I",
    "image":"/img/crossword.webp",
    "description":"Building an AI to satisfy the binary and unary constraints of a crossword puzzle",
    "tags":[
          "Python",
          "AI",
          "Constraint Satisfaction"
        ],
    "featured": true
}


Brute force solving a crossword puzzle with unary constraints (length of words) and binary constraints (overlapping letters between words).

The AI uses domains to manage possible words that can be used in the puzzle. When the program reaches a point where a constraint is no longer satisfied, it backtracks and removes unusable words from the domain.

Completed as part of Harvard's AI programming with Python course.