# mancala-madness
Mancala with power-ups

Setup:
Initially, the board will be set up with four marbles in each of the circular pots. Player 2‛s pots are the top row and the leftmost pot. Player 1 is everything else. When inserting marbles, the powerups will be randomly distributed(there can be more than one of the same power up) along with the 44 marbles (2 powerups on each player‛s side).

Overall behavior (2 players):
Players alternate taking turns. The youngest player goes first, deemed Player 1, they select a marble pot and the contents of that pot are distributed around the board in a counterclockwise fashion, 1 in each pot including player 1‛s collection but excluding player 2‛s collection.
- If the last marble dropped is in his/her own collection, they take a free turn.
- If the last marble dropped is in an empty pot on his/her own side, then you capture that piece and any pieces in the pot directly opposite (all go into the current player‛s collection) - If the pot picked up has a marble power-up, the power-up is stored with Player 1 and the turn is continued as if a regular marble (the number of marbles in the pot remains the same regardless of it containing a powerup or not).
Player 1 (if they have any power-ups) has the option to use a powerup (only during their turn). If yes is selected, then the first powerup obtained will be the first executed. If Player 1 has landed in their own pot, then they have the option, once again, to use a power up, the same applies if the power up used is skip. Otherwise, it is Player 2‛s turn (same rules apply).
The game ends when all six spaces on one side are empty. The player with marbles still remaining on his/her side when the game ends collects all of those pieces. Count all the pieces in each player‛s collection, the winner is the player with the most pieces.

Power-ups:
1.Take +2 – when this marble is played, the current player gets two marbles from the opponent‛s collection and places them in their own. If the opponent only has 1 marble in their collection and the powerup is played, the only one marble is collected.
2.Squid – when this marble is played, the opponent cannot tell the number of marbles in the pots on either side for 1 turn
3.Switch – when this marble is played, the contents of the collection pots are switched 
4.Skip – when this marble is played, the current player gets an additional turn/play
