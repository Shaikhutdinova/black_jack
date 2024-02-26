# Blackjack app

The goal of the game is to score more points than the dealer, but not more than 21. If you have more points than 21,
then your score is highlighted in red and you lose.

## Project structure
1. **main.dart** for run app with ThemeData and home page BlackJackScreen().
2. **black_jack_screen.dart** contains Stateful Widget with application logic and visual design.
   - There is a list of cards, dealer's and player's cards in *changeCards* method that sets the first two cards
   for players.
   - The *addCard* method allows the player to add one card to the game.
3. **cards_grid_view.dart** contains StatelessWidget widget that places the player's and dealer's cards in a grid
   of 3 in a row.
4. **my_button.dart** - button for "Start game", "Another card" and "Next Round".
