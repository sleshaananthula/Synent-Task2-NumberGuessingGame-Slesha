<h1 align="center" style="font-size: 42px;"> Number Guessing Game (CLI)</h1>
<p align="center">

<h2 style="font-size: 28px;"> Objective</h2>

Create an interactive command-line game where the user tries to guess a randomly generated number within a limited number of attempts.

<h2 style="font-size: 28px;"> Description</h2>

The program generates a random number within a defined range (e.g., 1–100). The user repeatedly enters a guess, and the program provides feedback ("Too High" or "Too Low") until the correct number is guessed or the attempt limit is reached.

<h2 style="font-size: 28px;">Features</h2>

- Random number generation using the `random` module
- Hint system: tells the user if their guess is too high or too low
- Tracks and displays the number of attempts taken
- Input validation to handle non-numeric entries
- Option to play again after a round ends

<h2 style="font-size: 28px;">Tech Stack</h2>

- **Language:** Python 3.x
- **Modules:** `random`

<h2 style="font-size: 28px;"> How to Run</h2>

```bash
git clone https://github.com/<your-username>/synent-task2-numberguessinggame-<yourname>.git
cd synent-task2-numberguessinggame-<yourname>
python number_guessing_game.py
```

<h2 style="font-size: 28px;"> Sample Output</h2>

```
Welcome to the Number Guessing Game!
I'm thinking of a number between 1 and 100.

Enter your guess: 50
Too High! Try again.

Enter your guess: 25
Too Low! Try again.

Enter your guess: 37
Correct! You guessed it in 3 attempts.
```


