# Handle Bar type

## Feature

Handles Bar types and its features

## Acceptance Criteria

### Scenario: user has not made any In-app purchase

  Given: two users are in the game AND
  the game has not yet begun

  When: user clicks on the "Start-game" button
  
  Then: Paint a normal bar for both players
  
### Scenario: user has made an In-app purchase of a customized bar

  Given: the user has successfully completed the payment for the new
  bar and launched the game
  
  When: user clicks on "Start-game" button

  Then: Paint the "customized bar" AND
  Notify "Handle-ball-movements"

  Given: the user is on the "Add-player-state" page AND
  there is no more than one player
  
  When: user clicks on "Start-game" button

  Then: Alert user
  "Game cannot begin with just one player!"
