# blackjack_game_project-
A simple Blackjack game built with Python for practicing basic programming and game logic.

In other to build this blackjack python projects i followed this following hints

hint 1
Create a deal_card() function that uses the List below to return a random card.
cards = [11, 2, 3, 4, 5, 6, 7, 8, 9, 10, 10, 10, 10]

Remember that 11 is the Ace.

 Hint 2
Deal the user and computer 2 cards each using deal_card() and append().
user_cards = []

computer_cards = []

 Hint 3
Create a function called calculate_score() that takes a List of cards as
input and returns the sum of all the cards in the List as the score.
Google the sum() function to help you do this.

 Hint 4
Inside calculate_score() check for a blackjack
(a hand with only 2 cards: ace + 10) and return 0 instead of the actual score.
0 will represent a blackjack in our game.

 Hint 5
Inside calculate_score() check for an 11 (ace).
If the score is already over 21, remove the 11 and replace it with a 1.
You might need to Google to find the documentation
on the Python built-in functions append() and remove().
https://developers.google.com/edu/python/lists#list-methods

 Hint 6
Call the function calculate_score(). If the computer or the user has a blackjack (0)
 or if the user's score is over 21, then the game ends.

 Hint 7
If the game has not ended, ask the user if they want to draw another card.
 If yes, then use the deal_card() function to add another card to the user_cards List.
  If no, then the game has ended.

 Hint 8
The score will need to be rechecked with every new card drawn and the checks in
 Hint 5 need to be repeated until the game ends.

 Hint 9
Once the user is done, it's time to let the computer play.
 The computer should keep drawing cards as long as it has a score less than 17.

 Hint 10
Create a function called compare() and pass in the user_score and computer_score.
If the computer and user both have the same score, then it's a draw.
If the computer has a blackjack (0), then the user loses.
If the user has a blackjack (0), then the user wins.
If the user_score is over 21, then the user loses.
If the computer_score is over 21, then the computer loses.
If none of the above, then the player with the highest score wins.

 Hint 11
 Ask the user if they want to restart the game. If they answer yes,
 clear the console and start a new game of blackjack and show the logo from art.py.
