# Start state

## Feature

The "Start-Game" functionality

## Acceptance Criteria

### Scenario: user presses anywhere on the page

  Given: the app is open in start state and
  the two players are in the game

  When: user presses anywhere on the screen

  Then: do nothing
  
### Scenario: user clicks on "Exit" button

  Given: the app is open in start state and
  the two players are in the game

  When: user clicks on the "Exit" button

  Then: Go to exit-state
  
### Scenario: the game has finished loading

  Given: the app is open in start state AND
  the two players are in the game

  When: the game has finished loading

  Then: Display "Game Loaded" AND
  Redirect to "Game State"
