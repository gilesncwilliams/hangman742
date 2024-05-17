# Hangman Game Project

## Introdution
Hangman is a classic game in which a player thinks of a word and the other player tries to guess that word within a certain amount of attempts.

This is an implementation of the Hangman game, where the computer thinks of a word and the user tries to guess it. 

## Installation Instructions
Python3 is required to run this game.


## Usage Instructions

To play the game run the Hangman_Game_Final.py script from you Command Line.

- You can also import the script and choose you're own list of words for the computer to choose from at random for you to guess from. You would just need to call the play_game(word_list) function.

- You can adjust the number of lives by updating the default value for the num_lives paramter in the Hangman class constructor.
  
- Please feel free to update the word list to include more words for the computer to choose from.

The game rules are as follows:
- Try guessing a letter for the word chosen by the computer.
- If you guess correctly your letter will be added to the word and display the word on the screen with the correcly guessed letter included. You will be able to see how many letters the word has and how many letters you have left to guess.
- You lose a life for every wrong guess. Once you have reached zero lives the game is over and you have list.
- To win simply guess the word before your lives run out!
 
## File Structure
- Hangman_Game_Final.py contains the game.
- Within the Milestone foler, there are additional 'Milestone' python files which were my step-by-step work-in-progress files as I worked through the milestones of the project. 
- hangman_Template.py is a template file provided by AiCore to help faciliate the creation of the game.

## License Information
This repo is unlicensed as it is intended only for training purposes.
