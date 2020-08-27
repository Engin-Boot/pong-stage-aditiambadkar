# declare-Winner

## Feature

Declare the player or computer as the winner

## Acceptance Criteria

### Scenario: Player score equals to 11

  Given computer misses pong ball
and player score increases

  When player score equals to 11

  Then declare player as winner and end pong game

### Scenario: Computer score equals to 11

  Given player misses pong ball
and computer score increases

  When computer score equals to 11

  Then declare computer as winner and end pong game
