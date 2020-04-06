# Hangman
 Hangman Game(python 3)

PROBLEM STATEMENT
Hangman is a paper and pencil guessing game for two or more players. One player thinks of a word and the other tries to guess it by suggesting the letters.The word to guess is represented by a row of dashes, giving the number of letters. If the guessing player suggests a letter which occurs in the word, the program writes it in all its correct positions. If the suggested letter does not occur in the word, the other player draws one element of the hangman diagram as a tally mark. The game is over when:

The guessing player completes the word, or guesses the whole word correctly.

HOW TO PLAY: Our code will generate a word which has to be guessed by the player. So,at the output screen will exist marked out blanks (short lines) for each letter of a word.Then the player will guess a letter. If that letter is in the word(s) then the project will write the letter at everyplace it appears, and cross out that letter in the alphabet. If the letter isn't in the word then we cross out the lifelines (which are usually a finite no. of chances) from the list. The player will continue guessing the letters until he can either solve the word (or phrase) or he will end up losing all the lifelines and he will be declared a LOSER.