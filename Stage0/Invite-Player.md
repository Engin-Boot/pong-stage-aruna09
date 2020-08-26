# Invite Player

## Feature

Inviting player functionality

## Acceptance Criteria

### Scenario: the user clicks on "Send Invite" button without typing a valid id
  
  Given: the user is on the "Invite-player" page
  
  When: user clicks on the "Send Invite" button

  Then: Alert user "Enter valid player id"

### Scenario: the user clicks on "Send Invite" button after typing a valid id
  
  Given: the user is on the "Invite-player" page
  
  When: user clicks on the "Send Invite" button

  Then: send an invite link to the player
  
### Scenario: the user clicks on "Send Invite" button after typing an invalid id

  Given: the user is on the "Invite-player" page
  
  When: user clicks on the "Send Invite" button

  Then: Alert user "No results found. Enter valid player id"
  
### Scenario: the user clicks on "Cancel" button
  
  Given: the user is on the "Invite-player" page
  
  When: user clicks on the "Cancel" button

  Then: Revert back to the previous state
  
### Scenario: the user clicks on "Cancel Invite" button after sending an invite
  
  Given: the user is on the "Invite-player" page
  
  When: user clicks on the "Cancel Invite" button

  Then: Display "Invite Cancelled"
  
### Scenario: the user clicks on "Start Game" button
  
  Given: the user is on the "Invite-player" page AND
  two players have joined the game
  
  When: user clicks on the "Start Game" button

  Then: Display "Starting Game" AND
  Redirect to Start-State Page
