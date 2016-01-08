#The plan
Starts with a 10x20 grid where each square is 6x6 pixels.
The grid will be a bitarray with 7200 bits, aka 900 bytes.
Each time a piece falls it will:
- update the four grid spaces that changed
- if a button has been pressed, do the thing (if possible)
- if a row is to be cleared, clear it
- if a level is passed, increase the speed
- update score? not sure how scores work
