# Exit state

## Feature

The "Exit-Game" functionality

## Acceptance Criteria

### Scenario: when the user presses the "Exit Game" button

  Given: the app is open

  When: user presses on the "Exit Game" button

  Then: Alert user with the message
  "Are you sure you want to exit" AND
  exit if the user presses YES otherwise
  redirect to the previous state
