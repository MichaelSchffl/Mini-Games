# Mini-Games

This is a series of Mini Games I programmed.

### Mini-Game 1: TicTacToe
This is a 2 player game that is played against an opponent, where every player makes their move alternately by entering the coordinates of a field. The goal of the game is to complete a column, row or diagonal before the opponent does. At the beginning of the game the user can determine the size of the game board. For non-quadratic game boards there are four diagonals running from each corner. Have fun!

### Mini-Game 2: Cows and Bulls (aka Mastermind)
This fun and strategic game is played against the computer. The player has to guess a 4-digit number correctly in as few tries as possible. The player starts with guessing a number. The number can contain any digit from 0 to 9 and may embrace duplicats or even triplets. The computer's response is the number of cows and bulls. A cow is a right digit at the right place and a bull is a right digit at the wrong place. The computer doesn't tell you which of the digits in your guess are the cows and the bulls. Let's try with an example:

The number is "0123"\
The guess is "4135"\
The computer's response is "bulls: 1 cows: 1"\

The computer shows 1 bull (the 3) and 1 cow (the 1).\
A special case arises if the guess contains a duplicate or a triplet:

The number is "0123"\
The guess is "0909"\
The computer's response is "bulls: 0 cows: 1"\

The computer goes through the guess and eliminates a digit once it's a cow or a bull, so it will only show up once in that case!
Based on the  computer's response the player can make their next guess and gets another response from the computer, until the player's guess matches the number.
Once the player guessed right, it's the computer's turn to guess. It will try to beat you in guessing the number with fewer tries than you! Can you beat the computer?
My goal with this is to develope an algorithm to guess the number is as few tries as possible and ultimately implementing a machine learning algorithm that let's the computer learn from previous guesses.
