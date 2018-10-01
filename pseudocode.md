# Hangman (Pseudocode)

```
- Create 2 variables, one named player_1 (which will represent the player who will input the word) and player_2 (which will represent the player that will attempting to guess the word).

- Another variable will be made representing the amount of body parts.

- The variable player_1 will allow the user to input a string, the variable player_2 will allow for the the player to input a single word.

- Another variable (perferably named word_length) will determine the number of letters in the string player_1 inputed.

- A number of blanks will be printed out according to the number of letters gathered in word_length (this too will be assigned to a variable)

- The character of variable player_2 will be considered, if it matches any character in the word player_1 inputed (which can be done via a loop and an if statement) it will replace that blank and substract one to another variable with the length of word player_1 inputed.  If it does not match a word, it will reduce 1 from the body part counter.

- If the body counter reaches 0, the player_1 will win the game.

- If the body counter is not 0 and all the blanks are filled [which will be considered via the variable keeping track of the amount of words left (if it reaches 0)] player_2 wins

- Loop the code again an again (but not the input of the first player) and have it update with the data from the last loop until either player wins.

```
