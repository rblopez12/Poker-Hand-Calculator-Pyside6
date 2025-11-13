# Poker-Hand-Calculator-Pyside6
This GUI application will come in handy when there is confusion at the poker table between two hands!

This project is a GUI application named “Poker Hand Calculator.” The application
allows the user to manually enter card values (suit and rank) into the board which consists of the
flop (first 3 cards), the turn (the 4th card), and the river (5th and last card). The user then enters
the hands for player 1 and player 2. The program then will display which player wins and what
hand they win with. The following hand rankings go from lowest to highest: high card, one pair,
two pair, three of a kind, straight, flush, full house, four of a kind, straight flush, and royal flush.
When both players have the same hand, the program will determine which hand has the higher
card within the hand. For example, if player 1 has two pair consisting of a pair of 10’s and a pair
of 6’s and player 2 has two pair consisting of a pair of J’s and a pair of 4’s. Player 2 would win
because their highest pair beats player 1’s highest pair. If player 1 has a straight with the
numbers 2, 3, 4, 5, 6, and player 2 has a straight with the numbers 4, 5, 6, 7, 8, player 2 wins
because they have a higher straight. Essentially, if the players have the same hand, the program
will confirm which player has the better version based on the numbers, just like the real
gameplay of poker.
The GUI has five push buttons on the top of the window, representing the board.
Below that there are two more push buttons representing player 1 and another two below
representing player 2. At the very bottom there is a grid layout. The grid layout acts like a
calculator, where the user chooses the suit and the rank of the card. There are 52 cards in a
standard deck, so when the user chooses a suit, a separate instance of ranks displays that
include ranks from 2-10 and J-A. A reset button is on the bottom right to reset the whole
calculator. This project is inspired from an app called Evenbet Poker Calculator by Enterra.
4. Tools
- This project uses Python and PySide6 modules.
- Card images are from deckofcardsapi.com

Feature Tools
1. While playing the game of poker, if there’s any confusion, the user can use this app to figure
out and decide which player wins the particular hand
2. The user will be able to specifically modify the ‘Flop’, ‘Turn’, and ‘River’ QLabels. These
QLabels are known as the community cards (Shared cards, dealt face up for the players’ use in
Poker)
3. The user will also be able to customize and select the cards the players have
4. The app will then calculate which player wins the hand
For more information on the game of poker, this video explains the basic rules of poker. This
program does not include betting. Soley the determination of which hand wins.
https://www.youtube.com/watch?v=CpSewSHZhmo&t=109s
