# Interaction Sequences

## Startup Sequence

The game starts with the **Idle state** which is a
the first page that is displayed to a user.
This page allows the user **Add player** OR **Invite player** OR **Exit Game** functionality.
After adding two players in the game the user can **Start Game**.
Post this the user is directed to a static **start state** which loads the game.
After the game loads the user is finally redirected to a **Game state**,
which allows the user to play the game

## Movement Initiation

**Handle-Ball-Movements** and **Handle-Bar-Movements** are responsible for the computation
and deciding where the ball will be present on the screen.

## One score

**Handle-Score** is responsible for decrementing the score and declaring the winner.
