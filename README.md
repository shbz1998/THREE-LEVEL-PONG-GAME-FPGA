# PONG GAME ON FPGA
## BY SHAHBAZ MALIK

This is a three level Pong Game on ZYBO Z7-10 FPGA board. User can switch between level using the on-board switches.

Switches  &nbsp; &nbsp; &nbsp;  Level 

0001 &nbsp; &nbsp; &nbsp;  &nbsp; &nbsp; &nbsp; &nbsp;  1

0011 &nbsp; &nbsp; &nbsp;  &nbsp; &nbsp; &nbsp; &nbsp;  2

0111 &nbsp; &nbsp; &nbsp;  &nbsp; &nbsp;  &nbsp; &nbsp; 3

### Level 1
This is a solo-practise mode where user can just play against the wall and each time the ball hits the racket, the user will get 1 point added

### Level 2
This is a PVE mode where the user plays against the computer racket. Anytime one side misses the ball, the other side gets the point. Whoever reaches 0x0F points
first wins the game

### Level 3
The rules are the same as Level 2 but in this level, there are wandering ghosts that appear randomly. If the user hits the wandering ghost, they get 1 point.
If the computer hits the wandering ghost, the point will be removed from the user. 

Video Demo: https://www.youtube.com/watch?v=saYAQrAT0_o
