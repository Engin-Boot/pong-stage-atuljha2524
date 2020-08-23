# pongPaddle

## Feature

width = width of the paddle.
height = height of the paddle.
moveDown() = paddle moves down.
moveUp() = paddle moves up.
getPosition() = gives the position of paddle.

## Acceptance Criteria

### Scenario: ball hits paddle or not.

  Given - The ball is moving.

  When - ball reaches at a position where paddle might be available.

  Then - ball will bounce if paddle is present there.
  score will be changed if paddle is not present there
