# Hangman Game

A simple terminal-based Hangman game written in Python. The player tries to guess a randomly selected word, one letter at a time. Each incorrect guess reduces the number of lives. The game ends when the word is guessed correctly or all lives are lost.


## Project Structure

hangman.py – main game logic,

hangman_words.py – word bank used for random selection,

hangman_shape.py – ASCII visuals for lives and logo.

## 🎮 Gameplay
```text
The game randomly selects a word.
The player guesses one letter at a time.
Correct guesses reveal letters in the word.
Incorrect guesses reduce lives.
The game ends when:
  The word is fully guessed → You win!
  Lives reach zero → You lose!
```


### Requirements
- Python 3.x
- Two additional Python files:
  - `hangman_words.py` – contains the list of words (`word_list`)
  - `hangman_shape.py` – contains ASCII art for game stages and logo (`stages`, `logo`)


### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/Siddikaslan/Hangman.git
   cd Hangman
   python hangman.py
   ```
