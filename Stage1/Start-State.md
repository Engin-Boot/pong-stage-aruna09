# Start state

## Feature

The "Start-Game" functionality

## Acceptance Criteria

### Scenario: user clicks anywhere on the page

  Given: the app is open in "Start-state" and
  two players are in the game

  When: the game is loading AND
  user clicks anywhere on the screen

  Then: do nothing
  
### Scenario: user clicks on "Exit" button

  Given: the app is open in "Start-state" and
  two players are in the game

  When: user clicks on the "Exit" button

  Then: Go to "Exit-state"
  
### Scenario: the game has finished loading

  Given: the app is open in "start state" AND
  two players are in the game

  When: the game has finished loading

  Then: Display "Game Loaded" AND
  Redirect to "Game-State"
