# NYT_Digits
Utilities for people who love the New York Times "Digits" game

Each gzip CSV file has a simple structure, in a specific sequence, for anyone who codes an NYT-like "Digits" game. Each CSV line contains six numbers, a result value, and one correct solution (identical to "Our Solution" in the NYT "Digits" game) using the fewest arithmetic operations. Every line within a CSV is guaranteed unique. "nnnyears" in the filename tells you how many years' worth of games it contains if you allow one game per day. The date in the filename tells its creation. If the filename says "06puzzles," it means every six lines of the CSV constitute one game. The six lines of a game start with a "prime numbers" puzzle, followed by five puzzles in the form of the NYT "Digits" game, each with a result in the range of 51-99, 101-199, 201-299, 301-399, and 401-499. If the filename says "11puzzles," it means every eleven lines of the CSV constitute one game. It starts off like a "06puzzles" game (see above) plus five more puzzles, each with a result in the range of 501-599, 601-699, 701-799, 801-899, and 901-999. Some math-teacher-edition files include "ao" followed by five numbers representing the minimum arithmetic operators needed to solve each of the five NYT-like puzzles per game.
