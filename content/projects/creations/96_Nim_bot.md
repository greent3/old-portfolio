{
    "title":"M. Teaching a robot NIM",
    "link":"https://github.com/greent3/Harvards_AI_Programming_W_Python/tree/main/Chapter_4_Learning/nim/nim",
    "image":"/img/nim.webp",
    "description":"In the game Nim, we begin with some number of piles, each with some number of objects. Players take turns: on a player’s turn, the player removes any non-negative number of objects from any one non-empty pile. Whoever removes the last object loses.",
    "tags":[
        "Python",
        "ML",
        "Unsupervised Learning"
        ],
    "featured": true
}


By playing against itself repeatedly and learning from experience, eventually our AI will learn which actions to take and which actions to avoid. We do this through Q-learning, or assigning a reward value for every (state, action) pair. We’ll represent the game as an array (game board) of numbers (# of pieces in each row).
