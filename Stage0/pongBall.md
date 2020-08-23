# pongGame

## Feature

initx = initial position of ball in x-axis.
inity = initial position of ball in y-axis.
xSpeed = speed of ball in x axis.
ySpeed = speed of ball in y axis.
move() = moves the ball.
bounce() = ball bounces .
getX() = position of ball on x-axis.
getY() = position of ball on y-axis.

## Acceptance Criteria

### Scenario: when ball touches a safe boundary

  Given - The ball is moving.

  When - ball touches horizontal boundary or paddle.

  Then - ball will bounce.

### Scenario: when ball touches unsafe boundary

  Given - The ball is moving
  
  When - Ball touches the unsafe boundary of left side.
  
  Then - Player on the right side gets one point and
         ball moves to initial position.
