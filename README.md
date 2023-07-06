# Final-project-2IMN25

For running simulations open the file Simulator V2 LONG SIMULATIONS and run all cells. At the bottom cell, there are a couple of variables that can be adjusted:
n: number of games simulated
random.seed(xxx): the set seed for the randomizer
show_turns: set to 1 if the results should be displayed after each turn, 0 otherwise
show_rolls: set to 1 if the rolls should be displayed after all dice throws
player_strategy['xxx', 'yyy']: xxx sets the strategy for player0 and yyy sets the strategy for player1

Available strategies:
RANDOM: all actions are randomly chosen
RANDOM-GREEDY: all dice are randomly chosen however takes a tile when possible
GREEDY: a greedy strategy that will always pick the dice that will result in the immediate highest score possible, takes tile when possible
HUMAN: human-controlled, used for testing or for fun
MCST: strategy based on the Monte Carlo Search Tree algorithm
AI: strategy based on a neural network

When the simulations are done running the program will print the average amount of rounds the games took. The average final score of each player, the number of games each player won, and the number of draws.


If you run all the cells in the markov_chain_pickomino file you will generate the Markov Decision Diagram. This diagram will open in a separate tab, if you click the two buttons to the right of the magnifying glass with the cross in it (the clear search button) the diagram will also display the probabilities. By default, the diagram is only displayed partially, as in the 8th cell the root is moved further up the tree. To view the entire diagram you can remove the contents of this cell and run all cells again.
