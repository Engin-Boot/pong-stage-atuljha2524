# pong Game

## Feature

initial position of ball in x-axis
initial position of ball in y-axis
speed of ball in x axis
speed of ball in y axis
moves the ball
ball bounces
position of ball on x-axis
position of ball on y-axis

## Acceptance Criteria

### Scenario: when ball touches a safe boundary

  Given : The ball is moving

  When : ball touches horizontal boundary or paddle.

  Then : ball will bounce.

### Scenario: when ball touches unsafe boundary

  Given : The ball is moving
  
  When : Ball touches the unsafe boundary of left side.
  
  Then : Player on the right side gets one point and
         ball moves to initial position.
