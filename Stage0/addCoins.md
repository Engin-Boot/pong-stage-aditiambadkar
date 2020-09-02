# add-Coins

## Feature

Adds coins to player account

## Acceptance Criteria

### Scenario 1 : Player wins against computer

Given player scores 11 before computer

When declare-Winner declares player as winner

Then add-Coins adds 50 game coins to player account

### Scenario 2 : Player gets lucky draw cards after winning

Given declare-Winner declares player as winner and player
wins default 50 game coins on winning

When lucky-Draw-Cards display 3 cards to player and player
clicks on one of the cards

Then the card discloses game coins amount and the add-Coins
adds the corresponding game coins amount to player account
