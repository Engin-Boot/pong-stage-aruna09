# Game state

## Feature

The "Play-Game" functionality

## Acceptance Criteria

### Scenario: the game state is visible to the user

  Given: the app is open in "Game-state"

  When: the "Game-state" page is visible to the users

  Then: display two bars at both ends AND
  a ball in the middle AND
  a timer which counts down from 3
  
### Scenario: the game state is not visible to the user

  Given: the app is open in "Game-state"

  When: the "Game-state" page is not visible to the users

  Then: Display "Loading Game Page"
  
### Scenario: the timer has reached 0

  Given: the app is open in "Game-state" AND
  the "Game state" page has loaded

  When: the timer reaches 0

  Then: Notify "Handle-Ball-Movements" with message
  "First ball drop"
  
### Scenario: the ball touches the wall

  Given: the app is open in "Game-state"

  When: the ball touches the wall

  Then: Detect ball position AND
  record coordinates AND
  Notify "Handle-Ball-Movements"
  
### Scenario: the ball touches a bar

  Given: the app is open in "Game-state"

  When: the ball touches one of the bars

  Then: Detect ball position AND
  record coordinates AND
  Notify "Handle-Ball-Movements"
  
### Scenario: the ball touches the ground

  Given: the app is open in "Game-state"

  When: the ball touches the ground
  
  Then: Detect ball position AND
  record coordinates AND
  Notify "Handle-Ball-Movements"
  
### Scenario: one of the bars move

  Given: the app is open in "Game-state"

  When: one of the bars move from its previous position

  Then: Detect bar position AND
  record coordinates AND
  Notify "Handle-Bar-Movements"
