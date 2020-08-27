# check-Score

## Feature

Checks if computer or player score is equal to 11

## Acceptance Criteria

### Scenario 1: Computer score increases and equal to 11

Given player misses pong ball

When computer score increases by 1

Then if computer score is equal to 11 declare computer as winner

### Scenario 2: Player score increases and equal to 11

Given computer misses pong ball

When player score increases by 1

Then if player score is equal to 11 declare player as winner

### Scenario 3: Computer score increases and not equal to 11

Given player misses pong ball

When computer score increases by 1

Then if computer score is not equal to 11 player plays move and
starts new round

### Scenario 4: Player score increases and not equal to 11

Given computer misses pong ball

When player score increases by 1

Then if player score is not equal to 11 computer plays move and
starts new round
