# Idle State

## Feature

This screen is the first screen, which displays a static background
image of the 'pong game'

## Acceptance Criteria

### Scenario: The game is in an idle state, and is yet to begin

  Given: the user has downloaded the app
  
  When: user opens the app

  Then: Display
  
  A static image of the pong game as the background image
  
  "Add player" button
  
 "Invite player" button
  
  "Exit" button
  
### Scenario: the user clicks anywhere on the screen
  
  Given: the user has downloaded the app
  
  When: user opens the app

  Then: do nothing

### Scenario: User wants to invite a new player to the game

  Given: the user is on the "Idle-state" page
  
  When: user clicks on "Invite player" button

  Then: Redirect to "Invite-a-player" page
  
### Scenario: User wants to add a new player to the game

  Given: the user is on the "Idle-state" page
  
  When: user clicks on "Add a new player"

  Then: Redirect to "Add player" page
  
### Scenario: User wants to exit the game

  Given: the user is on the "Idle-state" page
  
  When: user clicks on "Exit"

  Then: Redirect to "Exit-state"
