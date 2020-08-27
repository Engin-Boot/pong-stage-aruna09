# Handle-Ball-Movements state

## Feature

Handles Ball Movement functionality

## Acceptance Criteria

### Scenario: receives the message "First ball drop"

  Given: the app is open in "Game-state"

  When: receives the message "First ball drop"

  Then: make the ball and drop from a
  predefined height with a given speed

### Scenario: the user has made an "In-app-purchase"

  Given: the app is open in "Game-state"

  When: receives the ball position and coordinates

  Then: double speed and make ball at the relevant position
  
### Scenario: receives the position and the coordinates

  Given: the app is open in "Game-state"

  When: receives ball position and coordinates

  Then: check the position of the ball to find
  whether it has touched the wall
  AND find the player side
  AND Notify "Handle-Score"

  Then:  check the position to find
  whether it has touched the bar
  Make the ball according to the given
  speed and velocity
  
  Then: check the position to find
  whether it has touched the bar
  Make the ball according to the
  given speed and velocity
