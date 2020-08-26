# get-Game-Level

## Feature

Accept the game level (Easy, Medium or Hard) from the player

## Acceptance Criteria

### Scenario 1 : Player completes Player Selection and chooses "Easy" Level

Given player is on game level selection page after player selection

  When player clicks on one of "Easy" option

  Then the pong ball direction randomness is set to 50% which increases
  by 10% after subsequent player point and pong ball speed is set to 1
  which increases by 1 after subsequent player point
  
### Scenario 2 : Player completes Player Selection and chooses "Medium" Level

Given player is on game level selection page after player selection

  When player clicks on one of "Medium" option

  Then the pong ball direction randomness is set to 70% which increases
  by 15% after subsequent player point and pong ball speed is set to 2
  which increases by 2 after subsequent player point
  
### Scenario 3 : Player completes Player Selection and chooses "Hard" Level

Given player is on game level selection page after player selection

  When player clicks on one of "Hard" option

  Then the pong ball direction randomness is set to 90% which increases
  by 20% after subsequent player point and pong ball speed is set to 3
  which increases by 3 after subsequent player point  
