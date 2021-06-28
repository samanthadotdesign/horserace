# A drinking game inspired by horse racing

## :horse_racing: How To Play
1. Players play against the dealer (computer). The objective of the game is to bet shots on a "horse", one of the four suits to win. 
2. The payout for the winning horse depends on the dealer. 
3. When the players's horse doesn't win, they lose all shots in their bet. 
4. Players start with 10 shots. 
5. The game ends when any player reaches 0 shots. 
6. The other players distributes their shots.

## :black_joker: Gameplay
1. Game starts with all aces face up, each ace represents its suit or "horse". Then 8 random cards are generated face up.
2. Based on the 8 random cards, dealer comes up with the bet payouts if each suit wins. 
3. At the beginning of the game, players enter their name. Each player starts with a hand of 10 shots and decides how many shots to bet on one suit. 
4. Dealer deals cards from the deck face up according to the suit. 
5. (Advanced mode) The initial bet is the number of shots placed in the beginning of the game. When one of the suits reaches the halfway mark (first suit that has 4 cards on the table), players can double down on their current suit by placing the same initial bet for the same suit or place the initial bet on a different suit. 
6. The suit which reaches 8 cards first wins. 
7. Players add and deduct shots to their hand based on the payout. 
8. The game ends when a player reaches 0 shots. The players with shots left distribute the shots in their hand to the other players.

## :anchor: Features

###### REGISTRATION
1. User registration
2. User login
3. User forgets password (nice-to-have)
4. Multiple users can use the same URL to play the game (nice-to-have)

###### ADDING PLAYERS, BETS, SCORES
1. AJAX: After the 8 random cards are dealt, they are used to determine the bet payouts for the dealer
2. AJAX: When the users input their names and bets, using Sequelize to store users

###### CARD DEAL
1. DOM manipulation: For the cards to be dealt from the deck


## :construction: ERD
![erd](https://user-images.githubusercontent.com/31368622/123602097-fbd1f880-d82a-11eb-8fd1-af7c830ac588.png)
