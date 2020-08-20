# Reset score

## Feature

The "Reset-score" functionality

## Acceptance Criteria

### Scenario: when a new player joins the game OR a new game starts

  Given: the app is open

  When: user clicks on the "Start Game" button OR
  a new player joins the game

  Then: Set score of both players to zero
  Redirect to "Game page"
