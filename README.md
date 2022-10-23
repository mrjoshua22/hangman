# Hangman

Player tries to guess a random word by suggesting letters within a certain number of guesses. The word to guess is represented by a row of underscores representing each letter of the word. If the guessing player suggests a letter which occurs in the word, this letter appears in all its correct positions. If the suggested letter does not occur in the word, the program draws one element of a hanged stick figure. Player must win by guessing all the letters that appear in the word, thereby completing the word, before the hanged figure is completed.

### Requirements

`ruby >= 2.7.0`

### Installation & using

In `terminal` or `cmd`

`ruby hangman.rb`

### Adding a new word to guess

New words should be added to the `data/words.txt` in uppercase, each word in a new line