# buy-Item

## Feature

Buy item from pong game store and add to player account

## Acceptance Criteria

### Scenario 1 : Player has sufficient game coins to buy an item

Given player clicks on one of the three categories on store and
display-Store-Items displays the items for purchase

When player clicks on any item to buy it

Then buy-Item checks if the player has sufficient game coins to
purchase it and adds the item to player items and deducts game
coins from player account

### Scenario 2 : Player does not have sufficient game coins to buy an item

Given player clicks on one of the three categories on store and
display-Store-Items displays the items for purchase

When player clicks on any item to buy it

Then buy-Item checks if the player has sufficient game coins to
purchase it and displays message "Insufficient Coins"
