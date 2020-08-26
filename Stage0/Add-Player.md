# Add new player

## Feature

Add new player functionality

## Acceptance Criteria

### Scenario: when the user clicks on the "Add Player" button

  Given: the app is open and is in "Add-player" state

  When: user clicks the "Add Player" button AND
  either there are 0 players OR
  there is not more than one player in the game

  Then: Initiate a new player and Reset score
  
### Scenario: User clicks on "Start game" button

  Given: the user is in the "Add-player" page AND
  there are two players in the game
  
  When: user clicks on "Start-game" button

  Then: Redirect to the "Start-game" page
  
### Scenario: User clicks on "Start game" button

  Given: the user is on the "Add-player-state" page AND
  there is no more than one player
  
  When: user clicks on "Start-game" button

  Then: Alert user
  "Game cannot begin with just one player!"
  
