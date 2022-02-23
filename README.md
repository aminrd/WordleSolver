# WordleSolver
Solving daily puzzle games using Python. 

[Play Wordle](https://www.nytimes.com/games/wordle/index.html)
[![Open In Colab -- Wordle](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/aminrd/WordleSolver/blob/main/run_me.ipynb)


[Play Nerdle](https://nerdlegame.com/)
[![Open In Colab -- Wordle](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/aminrd/WordleSolver/blob/main/nerdle_solver.ipynb)


Run all cells in `.ipynb` file. Function `solve()` will suggest you and based on the feedback you tell it, it will trim the list of words and suggest you another one. 

For feedbacks you must use one of the following characters: 
* `c`: If the character is correct in that place (green in Wordle)
* `x`: If the character is not in the word (grey in wordle)
* `*`: The character is in the word, but in wrong place (yellow in wordle)

For Wordle only: 
* `-----`: Use this in cases where the word is not recognized in wordle (the nltk.words is used here which might not match the list of English words Wordle uses)
