[Rock-Paper-Scissors README (1).md](https://github.com/user-attachments/files/24597074/Rock-Paper-Scissors.README.1.md)
Abigail Beyrich

Stephen Connelly

Chloe de Leon

DOCUMENTATION

* About/ Read me  
  * This project runs a digital version of rock-paper-scissors. The player first chooses how many series they would like to play, then they choose the type of computer they would like to play against, then they choose how many games they want in each series of the tournament. After they submit these inputs, the games in each series will play. The AI will choose a move according to the player’s choice of computer. For each game, the move the AI played and the corresponding winner will be printed before the next game starts. After all of the games are played, a statistics report will be printed  
* Built With  
  * Python: Game logic and structure  
  * Jupyter notebook: interactive execution and testing  
  * ‘time’ and ‘iPython.display’ modules for gameplay pace and updating game output, respectively.  
* Getting Started  
  * This game requires Python 3 and the iPython package. Install these if needed.  
  * Open the .py file in a program or notebook that can run Python.  
  * If you are running the program in a notebook, run all cells.  
  * Once you run the program, follow all prompts. When the program is finished, your stats will print.  
* Each Team Member’s Contributions  
  * Chloe (Student A)  
    * Student A: Core Game Logic & AI \- Implement basic rock-paper-scissors rules \- Random AI (completely random choices) \- Pattern AI (looks for player patterns in last 3-5 moves) \- Counter AI (plays what would beat player’s most common choice) \- Input validation for player choices.  
    * Implemented updating display.  
    * For Documentation, About, Built With, and Getting started sections  
  * Abigail (Student B)  
    * Use loops to create a best of three, five, and seven game tournament, testing for edge cases  
    * Display the current round and the score during each rounds  
    * Define and print match and series winner, use loops to make the ability to have multiple series  
  * Stephen (Student C)  
    * Created the analysis and statistics to keep track of the results of each match, the longest win streaks, the win percentages, the most common player and AI choices, and tracking the results of each match by throw type.   
    * Worked on testing the final results, fixing typos, overall debugging  
* Challenges & Wins  
  * It was difficult deciding to make certain variables global, and determining whether that would be good practice.  
  * There were A LOT of variables, and therefore a lot of variable names. It got confusing to keep track of when we were putting each contributor's sections together.  
  * Sometimes our variable names and function names overlapped, so we had to go back and correct those parts.    
  * A lot of the code lines were similar to each other meaning that they could be copy and pasted to be reused for a different variable, leading to some errors/typos being repeated throughout the code.   
  * This experience will benefit us with future projects because we learned a lot about working with other people and working on multiple parts of the project at the same time

EDGE CASES/ TESTING? PROBLEMS/ IMPROVEMENTS:

- Handling invalid/ inputs using else statements  
- Ties could be considered an edge case. This was handled by making the winner/loser in all cases None  
- If someone input zero to the amount of series, this would break our code.   
- We could display the statistics in a data frame to make it look better to the user
