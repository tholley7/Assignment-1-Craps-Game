# Assignment 1: Craps Game
Write a simulation of the Craps dice game. Craps is a dice game that revolves around rolling two
six-sided dice in an attempt to roll a particular number. Wins and losses are determined by
rolling the dice. This assignment gives practice for: printing, loops, variables, if-statements or
switch statements, generating random numbers, methods, and classes. 

## Craps Rules
### First Roll:
The first roll (“come-out roll”) wins if the total is a 7 or 11. The first roll loses if the total is a 2, 3,
or 12 (“craps”). If any of these five numbers is rolled on the first roll, tally the win or loss, and
the round is over. 

If none of the above is rolled on a first roll, then the total rolled is saved as the point, i.e. a
“point” is established. 

### Subsequent Rolls
Continue rolling the dice until either a 7 is rolled or the point is rolled i.e. the round is over.
For those rolls, if the point is rolled before a 7, then tally a win. If a 7 is rolled before the point,
tally a loss. 

## Requirements
1. Roll 100,000 rounds.
2. Print out information about each round.
3. Keep track of the wins and losses of each round played.
4. Print out the round information for the first 10 rounds.
5. Print out the total number of round wins and losses over 100,000 rounds. 
