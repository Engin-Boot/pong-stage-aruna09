# Start state

## Feature

The "Start-Game" functionality

## Acceptance Criteria

### Scenario: the user clicks the "Start Game" button

  Given: the app is open in idle state and
  the two players are in the game

  When: user presses on the "Start Game" button

  Then: Set score of both players to zero
  Redirect to "Game page"
