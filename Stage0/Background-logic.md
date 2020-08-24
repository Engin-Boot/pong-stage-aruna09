# Background Logic

## Feature

Provides all the background logic of the game

## Acceptance Criteria

### Scenario: Receives coordinates and ball position

  Given: the ball touches the wall or bar
  
  When: the coordinates and ball position are supplied

  Then: calculate the position and player
  
### Scenario: Receives player number for score increment

  Given: Player number and information on
  whether the ball has touched the bar or the wall

  When: receives player number

  Then: if the ball has touched the wall
  increment score for player
  otherwise do nothing
  
### Scenario: when the score reaches max score

  Given: a game is currently going on

  When: max score is reached

  Then: Record player no and declare winner
